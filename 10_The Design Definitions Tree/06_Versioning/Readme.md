# Versioning

Your Design Defintions Tree can be just any regular directory, but after a certain point it often makes sense to keep it in a [Git repository](https://git-scm.com/). This lets multiple authors collaborate in a more structured fashion, but it also comes with an added benefit: using Git you can have DSK display multiple versions of your design system. This is a powerful feature in larger organisations, were different products might have been built with different versions of the design system.

When you keep your design system in a Git repository, all you have to do is [create a tag](https://git-scm.com/book/en/v2/Git-Basics-Tagging) for the version you want to expose and tell DSK about it by adding the tags name to the versions property of [DSK’s configuration file](/The-Design-Definitions-Tree/Configuration). The built-in frontend will now display a dropdown with all your versions in the lower left-hand corner and lets users select which one to look at.

The configuation functions as a whitelist, meaning you have to manually add all versions that you want to expose. By default only the `live` version – the current state of your directory – is whitelisted.

<CodeBlock title="dsk.yaml" language="yaml">
<script>
org: ACME Corp.
project: Example
lang: en
versions:
  - live
  - build-2
</script>
</CodeBlock>

In this example users will be able to either look at the state of your DDT as it is right now, or select the state that was tagged `build-2`.

When using the built-in frontend DSK’s search is always scoped to the version of the DDT that is currently selected.
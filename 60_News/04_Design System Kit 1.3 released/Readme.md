# Design System Kit 1.3 Released

## New feature: Multiple Versions
In larger organizations it is common for multiple projects to work with a design system. But not every project has the resources necessary to always keep in sync with the latest changes to the design system. To help with the issues that abound DSK is now tightly integrated with version control and supports documenting multiple versions of a design system simultaneously.

When you keep your design system in a Git repository, all you have to do is [create a tag](https://git-scm.com/book/en/v2/Git-Basics-Tagging) for the version you want to expose and tell DSK about it by adding the tags name to the versions property of [DSK’s configuration file](https://rundsk.com/tree/The-Design-Definitions-Tree/Configuration). The built-in frontend will now display a dropdown with all your versions and lets users select which one to look at.

For a complete list of what other improvements and changes this update introduces please take a look at our comprehensive [changelog](https://github.com/rundsk/dsk/blob/1.3/CHANGELOG.md#130-unreleased).

## dpa is running DSK with a custom-built frontend
Germany’s largest news agency, “Deutsche Presse-Agentur” (dpa), is now using DSK to present the documentation for its new “dpa ID Partnerprogramm”. Its three installations of DSK – used for different bodies of documentation – are complete with a custom-built frontend and several purpose-built documentation components:

* [Developer Documentation](https://developerdocs.dpa-id.de)
* [Design Kit](https://designkit.dpa-id.de)
* [Design Docs](https://designdocs.dpa-id.de)

dpa was also kind enough to agree to open source the new Code Embed documentation components, which are now available in the built-in frontend: [DSK / Code Embeds](https://rundsk.com/tree/The-Design-Definitions-Tree/Documents/Components/Code-Embeds).

## DSK is now its own organization
While DSK started as a project at Atelier Disko, it has now grown into its own, separate organization. As of now it is hosted at [github.com/rundsk](http://github.com/rundsk/) and is being maintained by the core team, [Marius](https://mariuswilms.com) and [Christoph](https://www.christophlabacher.com).

DSK now also has its own Twitter account, which you should follow to stay informed about future updates and the ongoing development of new features: [twitter.com/_rundsk](https://twitter.com/_rundsk).
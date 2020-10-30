# dotnet-template-templates

Templates for "dotnet new" for creating project and item templates.

These are a work-in-progress; feel free to raise an issue if you have questions or would like to help out :-)

# Installing

To install the templates, see the instructions for the [latest release](https://github.com/tintoy/dotnet-template-templates/releases/latest).

# Using

* To create a new project template, run `dotnet new project-template`.
* To create a new item template, run `dotnet new item-template`.

Note - both these templates create projects; those projects produce packages which, when installed, will make project or item templates available.

Also, there is a Template packaging template, to create a new package project, run `dotnet new packaging-template`.

# Run from source

To install the templates directly from the repository, run the following command from the root of this repository:

```
dotnet new -i src/Templates/content
```

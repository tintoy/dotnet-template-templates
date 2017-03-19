# dotnet-template-templates

Templates for "dotnet new" for creating project and item templates.

These are a work-in-progress; feel free to raise an issue if you have questions or would like to help out :-)

# Installing

To install the templates, run:

```
dotnet new -i FiftyProtons.Templates.DotNetNew::0.1.0-alpha3
```

Note that running `dotnet new -l` in a non-empty directory will only show item templates, whereas running it in an empty directory will only show project templates.

# Using

* To create a new project template, run `dotnet new project-template`.
* To create a new item template, run `dotnet new project-template`.

Note - both these templates create projects; those projects produce packages which, when installed, will make project or item templates available.

# Run from source

To install the templates directly from the repository, run the following command from the root of this repository:

```
dotnet new -i src/Templates/content/ProjectTemplate
dotnet new -i src/Templates/content/ItemTemplate
```

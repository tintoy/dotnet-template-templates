# dotnet-template-templates

Templates for "dotnet new" for creating project and item templates.

These are a work-in-progress; feel free to raise an issue if you have questions or would like to help out :-)

Note that if you are _not_ using the latest code from [dotnet/templating](https://github.com/dotnet/templating) (i.e. `dotnet new3`) the you will need to manually rename `.template.config/_template.json` to `.template.config/template.json` in the new template project after running `dotnet new`. This is due to a bug in the templating engine that will be resolved sometime after VS2017 has been released.

# Installing

To install the templates, run:

```
dotnet new -i FiftyProtons.Templates.DotNetNew::0.1.0-alpha4
```

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

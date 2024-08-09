# Instructions 

To create a new project: 

```bash
dotnet new mvc -n MyAspNetApp
```

Delete the .sln file since we are not going to be having multiple projects in this solution.

```bash
rm MyAspNetApp.sln
```

To run the project, navigate to the project directory and run:

```bash
dotnet run
```

Or with hot reload can do:

```bash
dotnet watch run
```
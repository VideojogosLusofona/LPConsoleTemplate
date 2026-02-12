# LP Console Template

## Summary

Template for .NET 10.0 console projects with the following characteristics for
compatibility with Unity 6.3 LTS:

- Contains `Program` class with `Main()` method.
- No reference nullables.
- Language version: C# 9.0

## Installation instructions

Open a console and run the following commands:

```bash
$ git clone https://github.com/VideojogosLusofona/LPConsoleTemplate.git
$ dotnet new install LPConsoleTemplate
```

## Creating a new project

After the template is installed, new console projects can be created as follows:

```bash
dotnet new lpconsole --name MyProject
```

## Other useful commands

* Uninstall an old version of this template:
    ```bash
    $ dotnet uninstall /full/path/to/the/old/template
    ```
* How to find what `/full/path/to/the/old/template` should actually be?
  ```bash
  $ dotnet uninstall
  ```
  (this lists all templates you have installed and can uninstall)


## Metadata

* License: [Public Domain](https://en.wikipedia.org/wiki/Public-domain-equivalent_license)
* Author: [Nuno Fachada](https://github.com/nunofachada)
* Institution: [Universidade Lusófona](https://www.ulusofona.pt/)

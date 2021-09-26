# ManagePackageVersionsCentrallyFSharp

Minimal example of [centrally managing NuGet package versions](https://github.com/NuGet/Home/wiki/Centrally-managing-NuGet-package-versions) of F# projects.

The only additional thing required for F# use is to set the property `DisableImplicitFSharpCoreReference` to true in `Directory.build.props`, then either explicitly add a package reference (without a version) to `Fsharp.Core` to each F# project, or do the equivalent of this automatically in the `Directory.Build.props` file (as is done here).

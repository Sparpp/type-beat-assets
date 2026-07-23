# type-beat-assets

Resources for [type!beat](https://github.com/Sparpp/type-beat), packaged as the `typebeat.Game.Resources` nuget package.

This is a modified fork of [ppy/osu-resources](https://github.com/ppy/osu-resources) (snapshot of upstream commit `d8d01c29ce0f298159aea3644b947d8b4a1882a2`), renamed from `osu.Game.Resources` to `typebeat.Game.Resources` (package ID, assembly name, namespaces, and embedded-resource manifest names). Asset content is otherwise unmodified unless noted in the commit history.

## Licence

All original resources are copyright (c) ppy Pty Ltd, licensed under [CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/legalcode); see [the licence file](LICENCE.md). This fork is likewise non-commercial and retains that licence.

Some fonts have separate licencing; check their local licence files before distributing them.

The "osu!" and "ppy" branding is protected by trademark and is not covered by the licence.

## Building the package

```
dotnet pack typebeat.Game.Resources/typebeat.Game.Resources.csproj -c Release -p:Version=<yyyy.Mdd.r> -o artifacts
```

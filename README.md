UniIx - Interactive Extensions for Unity
===

[Interactive Extensions (Ix)](https://github.com/Reactive-Extensions/Rx.NET) is a library which extends LINQ to Objects to provide many of the operators available in Rx but targeted for IEnumerable.



Installation
---

Use [UniIx.unitypackage](./UniIx.unitypackage) to install.  
Requires [UniRx](https://github.com/neuecc/UniRx) or [UniRx(AssetStore)](https://www.assetstore.unity3d.com/jp/#!/content/17276) to be imported.
(Only for `Do` operator.)



How To Update UniIx
---

1. Copy .cs files from [Interactive Extensions](https://github.com/Reactive-Extensions/Rx.NET/tree/master/Ix.NET/Source/System.Interactive).
2. Paste to Assets/UniIx directory.
3. Convert `nameof(xxx)` to `"xxx"` in .cs files.
4. Add `using UniRx;` to Do.cs.



License
---
This library is under the MIT License.

Some code is borrowed from [Rx.NET](https://rx.codeplex.com/) and [mono/mcs](https://github.com/mono/mono).

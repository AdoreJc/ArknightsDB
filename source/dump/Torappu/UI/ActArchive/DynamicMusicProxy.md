# DynamicMusicProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnMusicItemClicked(ActArchiveType, String)`

- `Void _OnSetHomeTheme()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class DynamicMusicProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnMusicItemClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnSetHomeTheme; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override String compType { get; }

	// RVA: 0x3009374 VA: 0x7595621374
	protected override String get_compType() { }
	// RVA: 0x30093f0 VA: 0x75956213f0
	protected override String GetPrefabPath() { }
	// RVA: 0x3009478 VA: 0x7595621478
	protected override Void InitComp() { }
	// RVA: 0x3009790 VA: 0x7595621790
	private Void _OnMusicItemClicked(ActArchiveType type, String musicID) { }
	// RVA: 0x30098a8 VA: 0x75956218a8
	private Void _OnSetHomeTheme() { }
	// RVA: 0x3009990 VA: 0x7595621990
	public Void .ctor() { }
}
```
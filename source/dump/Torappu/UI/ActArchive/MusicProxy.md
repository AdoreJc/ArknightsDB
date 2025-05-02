# MusicProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnMusicItemClicked(ActArchiveType, String)`

- `Void _OnSetHomeTheme()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class MusicProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_InitComp; // 0x8
	private static DelegateBridge __Hotfix0__OnMusicItemClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnSetHomeTheme; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x300cb74 VA: 0x7595624b74
	protected override String get_compType() { }
	// RVA: 0x300cbf0 VA: 0x7595624bf0
	protected override Void InitComp() { }
	// RVA: 0x300cf08 VA: 0x7595624f08
	private Void _OnMusicItemClicked(ActArchiveType type, String musicID) { }
	// RVA: 0x300d020 VA: 0x7595625020
	private Void _OnSetHomeTheme() { }
	// RVA: 0x300d108 VA: 0x7595625108
	public Void .ctor() { }
}
```
# PicProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnPicItemClicked(ActArchiveType, String)`

- `Void _OnFullscreenToggled(Boolean)`

- `Void _OnSetHomeKV()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class PicProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_InitComp; // 0x8
	private static DelegateBridge __Hotfix0__OnPicItemClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnFullscreenToggled; // 0x18
	private static DelegateBridge __Hotfix0__OnSetHomeKV; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override String compType { get; }

	// RVA: 0x300d198 VA: 0x7595625198
	protected override String get_compType() { }
	// RVA: 0x300d214 VA: 0x7595625214
	protected override Void InitComp() { }
	// RVA: 0x300d58c VA: 0x759562558c
	private Void _OnPicItemClicked(ActArchiveType type, String picID) { }
	// RVA: 0x300d6a4 VA: 0x75956256a4
	private Void _OnFullscreenToggled(Boolean on) { }
	// RVA: 0x300d7a8 VA: 0x75956257a8
	private Void _OnSetHomeKV() { }
	// RVA: 0x300d890 VA: 0x7595625890
	public Void .ctor() { }
}
```
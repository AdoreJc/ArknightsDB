# DynamicPicProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnPicItemClicked(ActArchiveType, String)`

- `Void _OnFullscreenToggled(Boolean)`

- `Void _OnSetHomeKV()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class DynamicPicProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnPicItemClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnFullscreenToggled; // 0x20
	private static DelegateBridge __Hotfix0__OnSetHomeKV; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override String compType { get; }

	// RVA: 0x3009a20 VA: 0x7595621a20
	protected override String get_compType() { }
	// RVA: 0x3009a9c VA: 0x7595621a9c
	protected override String GetPrefabPath() { }
	// RVA: 0x3009b24 VA: 0x7595621b24
	protected override Void InitComp() { }
	// RVA: 0x3009e9c VA: 0x7595621e9c
	private Void _OnPicItemClicked(ActArchiveType type, String picID) { }
	// RVA: 0x3009fb4 VA: 0x7595621fb4
	private Void _OnFullscreenToggled(Boolean on) { }
	// RVA: 0x300a0b8 VA: 0x75956220b8
	private Void _OnSetHomeKV() { }
	// RVA: 0x300a1a0 VA: 0x75956221a0
	public Void .ctor() { }
}
```
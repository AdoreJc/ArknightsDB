# DisasterProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class DisasterProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x301311c VA: 0x759562b11c
	protected override String get_compType() { }
	// RVA: 0x3013198 VA: 0x759562b198
	protected override String GetPrefabPath() { }
	// RVA: 0x3013220 VA: 0x759562b220
	protected override Void InitComp() { }
	// RVA: 0x30133f8 VA: 0x759562b3f8
	private Void _OnItemClicked(ActArchiveType type, String id) { }
	// RVA: 0x3013528 VA: 0x759562b528
	public Void .ctor() { }
}
```
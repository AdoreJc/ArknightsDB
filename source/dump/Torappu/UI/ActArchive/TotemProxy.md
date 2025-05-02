# TotemProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class TotemProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x3010334 VA: 0x7595628334
	protected override String get_compType() { }
	// RVA: 0x30103b0 VA: 0x75956283b0
	protected override String GetPrefabPath() { }
	// RVA: 0x3010438 VA: 0x7595628438
	protected override Void InitComp() { }
	// RVA: 0x3010610 VA: 0x7595628610
	private Void _OnItemClicked(ActArchiveType type, String id) { }
	// RVA: 0x301072c VA: 0x759562872c
	public Void .ctor() { }
}
```
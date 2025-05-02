# BuffProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class BuffProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x300fdd4 VA: 0x7595627dd4
	protected override String get_compType() { }
	// RVA: 0x300fe50 VA: 0x7595627e50
	protected override String GetPrefabPath() { }
	// RVA: 0x300fed8 VA: 0x7595627ed8
	protected override Void InitComp() { }
	// RVA: 0x3010190 VA: 0x7595628190
	private Void _OnItemClicked(ActArchiveType type, String buffID) { }
	// RVA: 0x30102a4 VA: 0x75956282a4
	public Void .ctor() { }
}
```
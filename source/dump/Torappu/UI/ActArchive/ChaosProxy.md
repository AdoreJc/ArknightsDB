# ChaosProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ChaosProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x30107bc VA: 0x75956287bc
	protected override String get_compType() { }
	// RVA: 0x3010838 VA: 0x7595628838
	protected override String GetPrefabPath() { }
	// RVA: 0x30108c0 VA: 0x75956288c0
	protected override Void InitComp() { }
	// RVA: 0x3010a98 VA: 0x7595628a98
	private Void _OnItemClicked(ActArchiveType type, String id) { }
	// RVA: 0x3010bb4 VA: 0x7595628bb4
	public Void .ctor() { }
}
```
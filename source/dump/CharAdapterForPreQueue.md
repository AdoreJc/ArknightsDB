# CharAdapterForPreQueue

**Namespace:** ` `


## Fields

- `BuildingStationManagePreQueueView m_closure`

- `Int32 preQueueIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CharAdapterForPreQueue : CharAdapter
{
	private BuildingStationManagePreQueueView m_closure; // 0x20
	public Int32 preQueueIndex; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x3db2004 VA: 0x75963ca004
	public Void .ctor(BuildingStationManagePreQueueView closure) { }
	// RVA: 0x3db2448 VA: 0x75963ca448
	public override Int32 get_count() { }
	// RVA: 0x3db24d4 VA: 0x75963ca4d4
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```
# SlotListAdapter

**Namespace:** ` `


## Fields

- `RL04AlchemySlotListView m_view`


## Methods

- `Void set_slotDataList(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SlotListAdapter : SimpleLayoutAdapter
{
	private RL04AlchemySlotListView m_view; // 0x20
	private List`1 <slotDataList>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_slotDataList; // 0x0
	private static DelegateBridge __Hotfix0_set_slotDataList; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_get_count; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20

	public List`1 slotDataList { get; set; }
	public override Int32 count { get; }

	// RVA: 0x2b0d63c VA: 0x759512563c
	public List`1 get_slotDataList() { }
	// RVA: 0x2b0d4b4 VA: 0x75951254b4
	public Void set_slotDataList(List`1 value) { }
	// RVA: 0x2b0d538 VA: 0x7595125538
	public Void .ctor(RL04AlchemySlotListView view) { }
	// RVA: 0x2b0d6a4 VA: 0x75951256a4
	public override Int32 get_count() { }
	// RVA: 0x2b0d728 VA: 0x7595125728
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```
# TaskListAdapter

**Namespace:** ` `


## Fields

- `DailyMissionSimpleView m_closure`


## Methods

- `Void SetParams(IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TaskListAdapter : AsyncDataViewListAdapter`2
{
	private DailyMissionSimpleView m_closure; // 0x18
	private IList`1 m_dataList; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetParams; // 0x8
	private static DelegateBridge __Hotfix0_GetCount; // 0x10
	private static DelegateBridge __Hotfix0_GetData; // 0x18
	private static DelegateBridge __Hotfix0_GetListContainer; // 0x20
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x28
	private static DelegateBridge __Hotfix0_CostPerItem; // 0x30


	// RVA: 0x273b6c0 VA: 0x7594d536c0
	public Void .ctor(DailyMissionSimpleView closure) { }
	// RVA: 0x273b768 VA: 0x7594d53768
	public Void SetParams(IList`1 dataList) { }
	// RVA: 0x273bc2c VA: 0x7594d53c2c
	protected override Int32 GetCount() { }
	// RVA: 0x273bcac VA: 0x7594d53cac
	protected override MissionViewModel GetData(Int32 index) { }
	// RVA: 0x273bd9c VA: 0x7594d53d9c
	protected override Transform GetListContainer() { }
	// RVA: 0x273be10 VA: 0x7594d53e10
	protected override GameObject GetPrefab() { }
	// RVA: 0x273be8c VA: 0x7594d53e8c
	protected override UInt32 CostPerItem() { }
}
```
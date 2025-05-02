# Act20sideMilestoneViewModel

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String activityId`

- `MilestoneStateInfo _mileStoneData`

- `Int32 milestonePointInterval`

- `Int32 packageNum`

- `Int32 remainProgressNum`

- `Int32 colNum`

- `Int32 collectedPartNum`

- `Int32 totalPartNum`

- `String obtainItemRangeTip`

- `String actCurrencyName`


## Methods

- `Void LoadData(String)`

- `Void InitItemGetTip()`

- `Void RefreshProgress()`

- `Void RefreshCollectNum()`

- `RecycleInfo GetRecyclePartValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideMilestoneViewModel : IHotfixable
{
	public String activityId; // 0x10
	private MilestoneStateInfo _mileStoneData; // 0x18
	public Int32 milestonePointInterval; // 0x20
	public Int32 packageNum; // 0x24
	public Int32 remainProgressNum; // 0x28
	public Int32 colNum; // 0x2c
	public Int32 collectedPartNum; // 0x30
	public Int32 totalPartNum; // 0x34
	public String obtainItemRangeTip; // 0x38
	public String actCurrencyName; // 0x40
	private List`1 _cachedLoopItemList; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_InitItemGetTip; // 0x8
	private static DelegateBridge __Hotfix0_RefreshProgress; // 0x10
	private static DelegateBridge __Hotfix0_RefreshCollectNum; // 0x18
	private static DelegateBridge __Hotfix0_GetRecyclePartValue; // 0x20
	private static DelegateBridge __Hotfix0_GetItemListForAnim; // 0x28
	private static DelegateBridge __Hotfix0_RearrangeItemList; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x32f8694 VA: 0x7595910694
	public Void LoadData(String activityId) { }
	// RVA: 0x3303da0 VA: 0x759591bda0
	private Void InitItemGetTip() { }
	// RVA: 0x3304004 VA: 0x759591c004
	private Void RefreshProgress() { }
	// RVA: 0x3304094 VA: 0x759591c094
	private Void RefreshCollectNum() { }
	// RVA: 0x32f9e54 VA: 0x7595911e54
	public RecycleInfo GetRecyclePartValue() { }
	// RVA: 0x32f891c VA: 0x759591091c
	public List`1 GetItemListForAnim(Int32 rowNum) { }
	// RVA: 0x33042ac VA: 0x759591c2ac
	public List`1 RearrangeItemList(Int32 rowNum) { }
	// RVA: 0x3303cdc VA: 0x759591bcdc
	public Void .ctor() { }
}
```
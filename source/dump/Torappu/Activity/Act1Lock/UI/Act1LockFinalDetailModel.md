# Act1LockFinalDetailModel

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `StageAdditionData m_additionData`

- `StageViewModel m_commonStageModel`

- `Boolean m_hasInited`


## Properties

- `StageViewModel basicStageModel`

- `StageAdditionData additionData`

- `Boolean finalStagePass`

- `Int32 interlockCount`


## Methods

- `StageViewModel get_basicStageModel()`

- `StageAdditionData get_additionData()`

- `Boolean get_finalStagePass()`

- `Int32 get_interlockCount()`

- `Void _InitInterlockListIfNot()`

- `Void UpdateStageData()`

- `Void _UpdateInterlockList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockFinalDetailModel : Act1LockDetailModelBase
{
	private StageAdditionData m_additionData; // 0x20
	private StageViewModel m_commonStageModel; // 0x28
	private List`1 m_interlockList; // 0x30
	private Boolean m_hasInited; // 0x38
	private static DelegateBridge __Hotfix0_get_basicStageModel; // 0x0
	private static DelegateBridge __Hotfix0_get_additionData; // 0x8
	private static DelegateBridge __Hotfix0_get_interlockList; // 0x10
	private static DelegateBridge __Hotfix0_get_finalStagePass; // 0x18
	private static DelegateBridge __Hotfix0_get_interlockCount; // 0x20
	private static DelegateBridge __Hotfix0_get_stageType; // 0x28
	private static DelegateBridge __Hotfix0__InitInterlockListIfNot; // 0x30
	private static DelegateBridge __Hotfix0_LoadStageData; // 0x38
	private static DelegateBridge __Hotfix0_UpdateStageData; // 0x40
	private static DelegateBridge __Hotfix0__UpdateInterlockList; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public StageViewModel basicStageModel { get; }
	public StageAdditionData additionData { get; }
	public List`1 interlockList { get; }
	public Boolean finalStagePass { get; }
	public Int32 interlockCount { get; }
	public override InterlockStageType stageType { get; }

	// RVA: 0x33d55ac VA: 0x75959ed5ac
	public StageViewModel get_basicStageModel() { }
	// RVA: 0x33d5614 VA: 0x75959ed614
	public StageAdditionData get_additionData() { }
	// RVA: 0x33d567c VA: 0x75959ed67c
	public List`1 get_interlockList() { }
	// RVA: 0x33d56e4 VA: 0x75959ed6e4
	public Boolean get_finalStagePass() { }
	// RVA: 0x33d57e4 VA: 0x75959ed7e4
	public Int32 get_interlockCount() { }
	// RVA: 0x33d58c4 VA: 0x75959ed8c4
	public override InterlockStageType get_stageType() { }
	// RVA: 0x33d592c VA: 0x75959ed92c
	private Void _InitInterlockListIfNot() { }
	// RVA: 0x33d5ce8 VA: 0x75959edce8
	public override Void LoadStageData(String stageId) { }
	// RVA: 0x33d5ed0 VA: 0x75959eded0
	public Void UpdateStageData() { }
	// RVA: 0x33d5d98 VA: 0x75959edd98
	private Void _UpdateInterlockList() { }
	// RVA: 0x33d5f4c VA: 0x75959edf4c
	public Void .ctor() { }
}
```
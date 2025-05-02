# Act1LockNormalDetailModel

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `StageAdditionData m_additionData`

- `Boolean m_isExpand`

- `StageViewModel m_commonStageModel`


## Properties

- `StageViewModel basicStageModel`

- `StageAdditionData additionData`

- `Boolean isExpand`


## Methods

- `StageViewModel get_basicStageModel()`

- `StageAdditionData get_additionData()`

- `Boolean get_isExpand()`

- `Void set_isExpand(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockNormalDetailModel : Act1LockDetailModelBase
{
	private StageAdditionData m_additionData; // 0x20
	private Boolean m_isExpand; // 0x28
	private StageViewModel m_commonStageModel; // 0x30
	private static DelegateBridge __Hotfix0_get_basicStageModel; // 0x0
	private static DelegateBridge __Hotfix0_get_additionData; // 0x8
	private static DelegateBridge __Hotfix0_get_isExpand; // 0x10
	private static DelegateBridge __Hotfix0_set_isExpand; // 0x18
	private static DelegateBridge __Hotfix0_get_stageType; // 0x20
	private static DelegateBridge __Hotfix0_LoadStageData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public StageViewModel basicStageModel { get; }
	public StageAdditionData additionData { get; }
	public Boolean isExpand { get; set; }
	public override InterlockStageType stageType { get; }

	// RVA: 0x33d1ee4 VA: 0x75959e9ee4
	public StageViewModel get_basicStageModel() { }
	// RVA: 0x33d1f4c VA: 0x75959e9f4c
	public StageAdditionData get_additionData() { }
	// RVA: 0x33d1b88 VA: 0x75959e9b88
	public Boolean get_isExpand() { }
	// RVA: 0x33d2e14 VA: 0x75959eae14
	public Void set_isExpand(Boolean value) { }
	// RVA: 0x33d50c8 VA: 0x75959ed0c8
	public override InterlockStageType get_stageType() { }
	// RVA: 0x33d5130 VA: 0x75959ed130
	public override Void LoadStageData(String stageId) { }
	// RVA: 0x33d51d4 VA: 0x75959ed1d4
	public Void .ctor() { }
}
```
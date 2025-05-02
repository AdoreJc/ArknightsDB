# Act1LockInterlockDetailModel

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `StageAdditionData m_additionData`

- `Boolean m_isExpand`

- `StageViewModel m_commonStageModel`

- `CharacterCardViewModel m_assistCharModel`


## Properties

- `StageViewModel basicStageModel`

- `StageAdditionData additionData`

- `Boolean isExpand`

- `Boolean useSpecialAssist`

- `CharacterCardViewModel assistCharModel`


## Methods

- `StageViewModel get_basicStageModel()`

- `StageAdditionData get_additionData()`

- `Boolean get_isExpand()`

- `Void set_isExpand(Boolean)`

- `Boolean get_useSpecialAssist()`

- `CharacterCardViewModel get_assistCharModel()`

- `Void UpdateInterlockList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockInterlockDetailModel : Act1LockDetailModelBase
{
	private StageAdditionData m_additionData; // 0x20
	private Boolean m_isExpand; // 0x28
	private StageViewModel m_commonStageModel; // 0x30
	private List`1 m_interlockCharList; // 0x38
	private CharacterCardViewModel m_assistCharModel; // 0x40
	private static DelegateBridge __Hotfix0_get_stageType; // 0x0
	private static DelegateBridge __Hotfix0_get_basicStageModel; // 0x8
	private static DelegateBridge __Hotfix0_get_additionData; // 0x10
	private static DelegateBridge __Hotfix0_get_isExpand; // 0x18
	private static DelegateBridge __Hotfix0_set_isExpand; // 0x20
	private static DelegateBridge __Hotfix0_get_useSpecialAssist; // 0x28
	private static DelegateBridge __Hotfix0_get_assistCharModel; // 0x30
	private static DelegateBridge __Hotfix0_get_interlockCharList; // 0x38
	private static DelegateBridge __Hotfix0_LoadStageData; // 0x40
	private static DelegateBridge __Hotfix0_UpdateInterlockList; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override InterlockStageType stageType { get; }
	public StageViewModel basicStageModel { get; }
	public StageAdditionData additionData { get; }
	public Boolean isExpand { get; set; }
	public Boolean useSpecialAssist { get; }
	public CharacterCardViewModel assistCharModel { get; }
	public List`1 interlockCharList { get; }

	// RVA: 0x33d5280 VA: 0x75959ed280
	public override InterlockStageType get_stageType() { }
	// RVA: 0x33cc354 VA: 0x75959e4354
	public StageViewModel get_basicStageModel() { }
	// RVA: 0x33cc15c VA: 0x75959e415c
	public StageAdditionData get_additionData() { }
	// RVA: 0x33cbb08 VA: 0x75959e3b08
	public Boolean get_isExpand() { }
	// RVA: 0x33cd8a4 VA: 0x75959e58a4
	public Void set_isExpand(Boolean value) { }
	// RVA: 0x33cc034 VA: 0x75959e4034
	public Boolean get_useSpecialAssist() { }
	// RVA: 0x33cd7cc VA: 0x75959e57cc
	public CharacterCardViewModel get_assistCharModel() { }
	// RVA: 0x33cbfcc VA: 0x75959e3fcc
	public List`1 get_interlockCharList() { }
	// RVA: 0x33d52e8 VA: 0x75959ed2e8
	public override Void LoadStageData(String stageId) { }
	// RVA: 0x33cd1e4 VA: 0x75959e51e4
	public Void UpdateInterlockList() { }
	// RVA: 0x33d54b0 VA: 0x75959ed4b0
	public Void .ctor() { }
}
```
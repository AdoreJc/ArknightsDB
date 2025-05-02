# Act1LockZoneMapStateBean

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `String zoneId`

- `Act1LockZoneMapViewModel zoneViewModel`

- `Act1LockZoneMapViewProperty property`

- `Act1LockDetailAutoBattleProperty autoBattleProperty`

- `Act1LockStageViewModel m_selectedStageModel`


## Properties

- `Act1LockStageViewModel selectedStageModel`


## Methods

- `Act1LockStageViewModel get_selectedStageModel()`

- `Void InitData()`

- `Void _AddDetailProp()`

- `Act1LockStageViewModel FindStageModelByStageId(String)`

- `Void RefreshAct1LockZoneMapData()`

- `Void SelectStage(Act1LockStageViewModel)`

- `Void BindDetailProp(Act1LockDetailViewBase, InterlockStageType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockZoneMapStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public String zoneId; // 0x18
	public Act1LockZoneMapViewModel zoneViewModel; // 0x20
	public Act1LockZoneMapViewProperty property; // 0x28
	public Act1LockDetailAutoBattleProperty autoBattleProperty; // 0x30
	public List`1 detailPropList; // 0x38
	private Act1LockStageViewModel m_selectedStageModel; // 0x40
	private static DelegateBridge __Hotfix0_get_selectedStageModel; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0__AddDetailProp; // 0x10
	private static DelegateBridge __Hotfix0_FindStageModelByStageId; // 0x18
	private static DelegateBridge __Hotfix0_RefreshAct1LockZoneMapData; // 0x20
	private static DelegateBridge __Hotfix0_SelectStage; // 0x28
	private static DelegateBridge __Hotfix0_BindDetailProp; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Act1LockStageViewModel selectedStageModel { get; }

	// RVA: 0x339d78c VA: 0x75959b578c
	public Act1LockStageViewModel get_selectedStageModel() { }
	// RVA: 0x339e5b0 VA: 0x75959b65b0
	public Void InitData() { }
	// RVA: 0x VA: 0x0
	private Void _AddDetailProp() { }
	// RVA: 0x339d4c8 VA: 0x75959b54c8
	public Act1LockStageViewModel FindStageModelByStageId(String stageId) { }
	// RVA: 0x339f700 VA: 0x75959b7700
	public Void RefreshAct1LockZoneMapData() { }
	// RVA: 0x339d0c4 VA: 0x75959b50c4
	public Void SelectStage(Act1LockStageViewModel stageViewModel) { }
	// RVA: 0x339e7f0 VA: 0x75959b67f0
	public Void BindDetailProp(Act1LockDetailViewBase detailView, InterlockStageType stageType) { }
	// RVA: 0x33a7470 VA: 0x75959bf470
	public Void .ctor() { }
}
```
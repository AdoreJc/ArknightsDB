# ZoneViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String id`

- `Boolean isUnlock`

- `String defaultFocusStage`

- `String zoneMapAssetPath`

- `String timelyDropId`

- `StageDiffGroup m_currentDiffGroup`

- `ZoneData zoneData`

- `StageData mainlinePreposedStageData`

- `ZoneRewardBuffViewModel rewardBuffViewModel`

- `SelectedStageViewModel selectedViewModel`

- `Int32 <sortIndex>k__BackingField`

- `String focusStageId`


## Properties

- `String wrappedDefaultFocusStage`

- `StageDiffGroup currentZoneDiffGroup`

- `StageViewModel selectedStageNormal`

- `StageViewModel selectedStageHard`

- `SpecialStageType stageSelectedType`

- `StageViewModel selectedStageSixStar`

- `StageViewModel selectedStage`

- `Int32 sortIndex`

- `String focusStageIdNormal`


## Methods

- `String get_wrappedDefaultFocusStage()`

- `StageDiffGroup get_currentZoneDiffGroup()`

- `Void set_currentZoneDiffGroup(StageDiffGroup)`

- `Boolean ApplySelectedViewModel(String)`

- `StageViewModel get_selectedStageNormal()`

- `StageViewModel get_selectedStageHard()`

- `SpecialStageType get_stageSelectedType()`

- `Void set_stageSelectedType(SpecialStageType)`

- `StageViewModel FindNormalStageFromSpecialStage(String, SpecialStageType)`

- `StageViewModel FindSpecialStageFromNormal(String, SpecialStageType)`

- `StageViewModel GetStageByType(SpecialStageType)`

- `StageViewModel get_selectedStageSixStar()`

- `StageViewModel get_selectedStage()`

- `Int32 get_sortIndex()`

- `Void set_sortIndex(Int32)`

- `String get_focusStageIdNormal()`

- `Boolean IsCompleteCountExceeded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneViewModel : IComparable`1, IStageSelectHandler
{
	public String id; // 0x10
	public Boolean isUnlock; // 0x18
	public String defaultFocusStage; // 0x20
	public Dictionary`2 defaultFocusStageDiffGroup; // 0x28
	public String zoneMapAssetPath; // 0x30
	public String timelyDropId; // 0x38
	private StageDiffGroup m_currentDiffGroup; // 0x40
	public ZoneData zoneData; // 0x48
	public ListDict`2 stages; // 0x50
	public List`1 diffGroup; // 0x58
	public StageData mainlinePreposedStageData; // 0x60
	public ZoneRewardBuffViewModel rewardBuffViewModel; // 0x68
	public ListDict`2 stageEntries; // 0x70
	public SelectedStageViewModel selectedViewModel; // 0x78
	private Int32 <sortIndex>k__BackingField; // 0x80
	public String focusStageId; // 0x88

	public String wrappedDefaultFocusStage { get; }
	public StageDiffGroup currentZoneDiffGroup { get; set; }
	public StageViewModel selectedStageNormal { get; }
	public StageViewModel selectedStageHard { get; }
	public SpecialStageType stageSelectedType { get; set; }
	public StageViewModel selectedStageSixStar { get; }
	public StageViewModel selectedStage { get; }
	protected Int32 sortIndex { get; set; }
	public String focusStageIdNormal { get; }

	// RVA: 0x2fc9aa0 VA: 0x75955e1aa0
	public String get_wrappedDefaultFocusStage() { }
	// RVA: 0x2fc9b9c VA: 0x75955e1b9c
	public StageDiffGroup get_currentZoneDiffGroup() { }
	// RVA: 0x2fc9ba4 VA: 0x75955e1ba4
	public Void set_currentZoneDiffGroup(StageDiffGroup value) { }
	// RVA: 0x2fc9cf8 VA: 0x75955e1cf8
	public ListDict`2 LoadDiffGroupShuffleStages() { }
	// RVA: 0x2fc9f30 VA: 0x75955e1f30
	public Boolean ApplySelectedViewModel(String normalStageId) { }
	// RVA: 0x2fca244 VA: 0x75955e2244
	public StageViewModel get_selectedStageNormal() { }
	// RVA: 0x2fca258 VA: 0x75955e2258
	public StageViewModel get_selectedStageHard() { }
	// RVA: 0x2fca274 VA: 0x75955e2274
	public SpecialStageType get_stageSelectedType() { }
	// RVA: 0x2fca28c VA: 0x75955e228c
	public Void set_stageSelectedType(SpecialStageType value) { }
	// RVA: 0x2fca29c VA: 0x75955e229c
	public StageViewModel FindNormalStageFromSpecialStage(String notNormalStageId, SpecialStageType sourceStageType) { }
	// RVA: 0x2fca3c0 VA: 0x75955e23c0
	public StageViewModel FindSpecialStageFromNormal(String normalStageId, SpecialStageType targetStageType) { }
	// RVA: 0x2fca4e8 VA: 0x75955e24e8
	public StageViewModel GetStageByType(SpecialStageType stageType) { }
	// RVA: 0x2fca534 VA: 0x75955e2534
	public StageViewModel get_selectedStageSixStar() { }
	// RVA: 0x2fca5c0 VA: 0x75955e25c0
	public StageViewModel get_selectedStage() { }
	// RVA: 0x2fca5e8 VA: 0x75955e25e8
	protected Int32 get_sortIndex() { }
	// RVA: 0x2fca5f0 VA: 0x75955e25f0
	public Void set_sortIndex(Int32 value) { }
	// RVA: 0x2fca5f8 VA: 0x75955e25f8
	public String get_focusStageIdNormal() { }
	// RVA: 0x2fca658 VA: 0x75955e2658
	public virtual Int32 CompareTo(ZoneViewModel otherModel) { }
	// RVA: 0x2fca71c VA: 0x75955e271c
	public Boolean IsCompleteCountExceeded() { }
	// RVA: 0x2fca724 VA: 0x75955e2724
	public virtual Void LoadExtraData(String zoneId) { }
	// RVA: 0x2fca728 VA: 0x75955e2728
	public virtual Void LateInitAfterStageLoaded() { }
	// RVA: 0x2fca72c VA: 0x75955e272c
	public Void .ctor() { }
}
```
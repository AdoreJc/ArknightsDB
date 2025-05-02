# ActivityCustomZoneMapViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String actId`

- `String zoneId`

- `String zoneMapHolderPrefabPath`

- `String zoneMapPrefabPath`

- `String stagePreviewHolderPrefabPath`

- `String stagePreviewPrefabPath`

- `String selectingStageId`

- `Object actMeta`


## Properties

- `SpecialStageType stageSelectedType`

- `StageViewModel selectedStage`


## Methods

- `SpecialStageType get_stageSelectedType()`

- `StageViewModel FindNormalStageFromSpecialStage(String, SpecialStageType)`

- `StageViewModel FindSpecialStageFromNormal(String, SpecialStageType)`

- `StageViewModel GetStageByType(SpecialStageType)`

- `StageViewModel get_selectedStage()`

- `Boolean IsStageSelected(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ActivityCustomZoneMapViewModel : IStageSelectHandler, IHotfixable
{
	public String actId; // 0x10
	public String zoneId; // 0x18
	public String zoneMapHolderPrefabPath; // 0x20
	public String zoneMapPrefabPath; // 0x28
	public String stagePreviewHolderPrefabPath; // 0x30
	public String stagePreviewPrefabPath; // 0x38
	public ListDict`2 stages; // 0x40
	public String selectingStageId; // 0x48
	public Object actMeta; // 0x50
	private static DelegateBridge __Hotfix0_get_stageSelectedType; // 0x0
	private static DelegateBridge __Hotfix0_FindNormalStageFromSpecialStage; // 0x8
	private static DelegateBridge __Hotfix0_FindSpecialStageFromNormal; // 0x10
	private static DelegateBridge __Hotfix0_GetStageByType; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedStage; // 0x20
	private static DelegateBridge __Hotfix0_IsStageSelected; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public SpecialStageType stageSelectedType { get; }
	public StageViewModel selectedStage { get; }

	// RVA: 0x2f75968 VA: 0x759558d968
	public SpecialStageType get_stageSelectedType() { }
	// RVA: 0x2f759cc VA: 0x759558d9cc
	public StageViewModel FindNormalStageFromSpecialStage(String notNormalStageId, SpecialStageType sourceStageType) { }
	// RVA: 0x2f75a4c VA: 0x759558da4c
	public StageViewModel FindSpecialStageFromNormal(String normalStageId, SpecialStageType targetStageType) { }
	// RVA: 0x2f75acc VA: 0x759558dacc
	public StageViewModel GetStageByType(SpecialStageType stageType) { }
	// RVA: 0x2f75b44 VA: 0x759558db44
	public StageViewModel get_selectedStage() { }
	// RVA: 0x2f75bc8 VA: 0x759558dbc8
	public Boolean IsStageSelected(String stageId) { }
	// RVA: 0x2f75c78 VA: 0x759558dc78
	public Void .ctor() { }
}
```
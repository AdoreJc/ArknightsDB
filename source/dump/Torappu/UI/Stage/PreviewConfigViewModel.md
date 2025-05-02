# PreviewConfigViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String stageId`

- `Boolean isAutoBattle`

- `Boolean canAutoBattle`

- `Boolean shouldAutoBattleHidden`

- `Boolean canPractice`

- `Boolean canReplayStory`

- `Boolean canHardBattle`

- `Boolean canSixStarBattle`

- `Boolean stageDiffGroupActive`

- `Int32 baseApCost`

- `Boolean canContinuousBattle`

- `Int32 continuousBattleTimes`

- `Boolean hasHardToShow`

- `Boolean hasSixStarToShow`

- `SpecialStageType stageSelectType`

- `Int32 noCostCnt`

- `Boolean isUsingEt`

- `OverrideDropInfo overrideDropInfo`

- `Boolean isSkillSelectablePredefined`

- `StageDiffGroup stageDiffGroup`

- `StageBattleDiffGroupInfo battleDiffGroupInfo`

- `String startBattleStyle`

- `Int32 styleCost`

- `IPreviewConfigViewModelPlugin plugin`


## Properties

- `Int32 apCost`

- `Boolean isContinuousBattle`


## Methods

- `Int32 get_apCost()`

- `Boolean get_isContinuousBattle()`

- `Boolean CheckIfToUseAutoBattle(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class PreviewConfigViewModel : IHotfixable
{
	public String stageId; // 0x10
	public Boolean isAutoBattle; // 0x18
	public Boolean canAutoBattle; // 0x19
	public Boolean shouldAutoBattleHidden; // 0x1a
	public Boolean canPractice; // 0x1b
	public Boolean canReplayStory; // 0x1c
	public Boolean canHardBattle; // 0x1d
	public Boolean canSixStarBattle; // 0x1e
	public Boolean stageDiffGroupActive; // 0x1f
	public Int32 baseApCost; // 0x20
	public Boolean canContinuousBattle; // 0x24
	public Int32 continuousBattleTimes; // 0x28
	public Boolean hasHardToShow; // 0x2c
	public Boolean hasSixStarToShow; // 0x2d
	public SpecialStageType stageSelectType; // 0x30
	public Int32 noCostCnt; // 0x34
	public Boolean isUsingEt; // 0x38
	public OverrideDropInfo overrideDropInfo; // 0x40
	public Boolean isSkillSelectablePredefined; // 0x48
	public StageDiffGroup stageDiffGroup; // 0x4c
	public StageBattleDiffGroupInfo battleDiffGroupInfo; // 0x50
	public String startBattleStyle; // 0x58
	public Int32 styleCost; // 0x60
	public IPreviewConfigViewModelPlugin plugin; // 0x68
	private static DelegateBridge __Hotfix0_get_apCost; // 0x0
	private static DelegateBridge __Hotfix0_get_isContinuousBattle; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfToUseAutoBattle; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Int32 apCost { get; }
	public Boolean isContinuousBattle { get; }

	// RVA: 0x2f77334 VA: 0x759558f334
	public Int32 get_apCost() { }
	// RVA: 0x2f773b8 VA: 0x759558f3b8
	public Boolean get_isContinuousBattle() { }
	// RVA: 0x2f77438 VA: 0x759558f438
	public Boolean CheckIfToUseAutoBattle(Boolean isPratice) { }
	// RVA: 0x2f774c8 VA: 0x759558f4c8
	public Void .ctor() { }
}
```
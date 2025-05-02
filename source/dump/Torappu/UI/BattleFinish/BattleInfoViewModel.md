# BattleInfoViewModel

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `StageType stageType`

- `String stageCode`

- `String stageName`

- `PlayerBattleRank battleRank`

- `Difficulty difficulty`

- `StageDiffGroup diffGroup`

- `Boolean hasFavor`

- `Boolean isCampaign`

- `Boolean isContinuousBattle`

- `Int32 curContinueTimes`

- `Boolean isSpecialNormalStageForFourStarVoice`


## Properties

- `Boolean isHardStageAndCompleted`

- `Boolean isSixStarStageAndCompleted`


## Methods

- `Boolean get_isHardStageAndCompleted()`

- `Boolean get_isSixStarStageAndCompleted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleInfoViewModel : IHotfixable
{
	public StageType stageType; // 0x10
	public String stageCode; // 0x18
	public String stageName; // 0x20
	public PlayerBattleRank battleRank; // 0x28
	public Difficulty difficulty; // 0x2c
	public StageDiffGroup diffGroup; // 0x30
	public Boolean hasFavor; // 0x34
	public Boolean isCampaign; // 0x35
	public Boolean isContinuousBattle; // 0x36
	public Int32 curContinueTimes; // 0x38
	public Boolean isSpecialNormalStageForFourStarVoice; // 0x3c
	private static DelegateBridge __Hotfix0_get_isHardStageAndCompleted; // 0x0
	private static DelegateBridge __Hotfix0_get_isSixStarStageAndCompleted; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isHardStageAndCompleted { get; }
	public Boolean isSixStarStageAndCompleted { get; }

	// RVA: 0x2e8b89c VA: 0x75954a389c
	public Boolean get_isHardStageAndCompleted() { }
	// RVA: 0x2e8b908 VA: 0x75954a3908
	public Boolean get_isSixStarStageAndCompleted() { }
	// RVA: 0x2e8a0e4 VA: 0x75954a20e4
	public Void .ctor() { }
}
```
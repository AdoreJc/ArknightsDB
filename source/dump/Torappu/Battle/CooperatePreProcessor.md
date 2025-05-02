# CooperatePreProcessor

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_waveCnt`

- `Int32 m_lastWaveIndex`


## Properties

- `Int32 Item`

- `Int32 waveCnt`

- `Boolean isFail`


## Methods

- `Int32 get_Item(Int32)`

- `Int32 get_waveCnt()`

- `Boolean get_isFail()`

- `Void _ReplaceTeamPlayerWithEnemyKey(ActionData)`

- `Void _SelectTeamPlayers()`

- `Boolean _CheckNeedReplaceTeamInFootball(LevelData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CooperatePreProcessor : SchedulerPreprocessor
{
	private const String RANDOM_BONUS_KEY; // 0x0
	private const String FAIL_RANDOM_BONUS_KEY; // 0x0
	private const String TEAM_PLAYER_FORWARD; // 0x0
	private const String TEAM_PLAYER_GOALKEEPER; // 0x0
	private const String TEAM_PLAYER_MUSCLEMAN; // 0x0
	private const String MULTI_STAGE_TAG; // 0x0
	private const String HIGH_LEVEL_END; // 0x0
	private Dictionary`2 m_randomActionGroups; // 0x10
	private PriorityQueue`1 m_actionsToDelete; // 0x18
	private readonly HashSet`1 m_actionPacksToDelete; // 0x20
	private readonly Dictionary`2 m_footballLevelWithWaves; // 0x28
	private Int32 m_waveCnt; // 0x30
	private Int32 m_lastWaveIndex; // 0x34
	private Dictionary`2 m_selectTeamPlayer; // 0x38
	public readonly List`1 enemyCntStats; // 0x40
	public readonly List`1 stageWave; // 0x48
	public readonly List`1 stageDistCar; // 0x50
	private static DelegateBridge __Hotfix0_get_Item; // 0x0
	private static DelegateBridge __Hotfix0_get_waveCnt; // 0x8
	private static DelegateBridge __Hotfix0_get_isFail; // 0x10
	private static DelegateBridge __Hotfix0_DoPreprocess; // 0x18
	private static DelegateBridge __Hotfix0__ReplaceTeamPlayerWithEnemyKey; // 0x20
	private static DelegateBridge __Hotfix0__SelectTeamPlayers; // 0x28
	private static DelegateBridge __Hotfix0__CheckNeedReplaceTeamInFootball; // 0x30
	private static DelegateBridge __Hotfix0_Dispose; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 Item { get; }
	public Int32 waveCnt { get; }
	public Boolean isFail { get; }

	// RVA: 0x40dee0c VA: 0x75966f6e0c
	public Int32 get_Item(Int32 difficultyIndex) { }
	// RVA: 0x40defd0 VA: 0x75966f6fd0
	public Int32 get_waveCnt() { }
	// RVA: 0x40df038 VA: 0x75966f7038
	public Boolean get_isFail() { }
	// RVA: 0x40df17c VA: 0x75966f717c
	public override Void DoPreprocess(LevelData levelData) { }
	// RVA: 0x40e0858 VA: 0x75966f8858
	private Void _ReplaceTeamPlayerWithEnemyKey(ActionData action) { }
	// RVA: 0x40e0b28 VA: 0x75966f8b28
	private Void _SelectTeamPlayers() { }
	// RVA: 0x40e062c VA: 0x75966f862c
	private Boolean _CheckNeedReplaceTeamInFootball(LevelData levelData) { }
	// RVA: 0x40e0d28 VA: 0x75966f8d28
	public override Void Dispose() { }
	// RVA: 0x40e0df8 VA: 0x75966f8df8
	public Void .ctor() { }
}
```
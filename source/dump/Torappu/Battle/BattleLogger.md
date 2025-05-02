# BattleLogger

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_randomSeed`

- `BattleController m_controller`

- `BattleStats m_stats`

- `BattleVerboseRecorder m_verboseRecorder`


## Methods

- `Void _CreateVerboseRecorder(GameModeType)`

- `Void LogSquadAndRandomSeed(BattlePlayerData, Int32, PlayerSide)`

- `Void LogManualSpawn(BattleCharacterData, Direction, GridPosition, Boolean)`

- `Void LogManualWithdraw(BattleCharacterData, GridPosition)`

- `Void LogCharacterAutoWithdraw(BattleCharacterData)`

- `Void LogManualSkill(BattleCharacterData, GridPosition, Boolean)`

- `Void LogModifier(ref)`

- `Void LogEpModifier(ref)`

- `Void LogEpBreakModifier(Character, ElementType)`

- `Boolean LogCharacterSnapshot(Character)`

- `Boolean LogEnemySnapshot(EnemyData)`

- `Boolean LogRuneSnapshot()`

- `Boolean LogExtraBattleInfo(String, Int32, Boolean)`

- `Boolean LogExtraBattleInfo(String, Int32)`

- `Boolean LogExtraBattleInfoCharacterNotMannuallySpawn(String)`

- `Boolean LogExtraBattleInfoCharacterKillCount(String)`

- `Boolean LogExtraBattleInfoEnemyDieBecauseOfFallDown(String)`

- `Boolean LogRoguelikeRelicSnapshot(IEnumerable`1)`

- `Boolean LogExtraBattleInfoAddCount(ExtraLogType, List`1)`

- `Boolean LogExtraBattleInfoMaxCount(ExtraLogType, List`1, Int32)`

- `Void OnCharacterFinish(BattleCharacterData, FinishReason)`

- `Void OnEnemyBorn(EnemyData)`

- `Void OnEnemyFinish(EnemyData, Options, FinishReason)`

- `Void OnSkillTrig(BattleCharacterData)`

- `Void OnCostUnnaturalRecovered(Int32)`

- `Void OnAutoReplayCancelled()`

- `Void ClearAll()`

- `BattleStats AchieveStats(BattleController)`

- `Journal AchieveJournal(BattleController)`

- `Void _AppendLog(LogItem)`

- `Boolean _CheckPlayerSide(PlayerSide)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleLogger : IHotfixable
{
	private const Int32 MAX_SNAPSHOTS_FOR_SINGLE_CHARACTER; // 0x0
	private const Int32 MAX_SNAPSHOTS_FOR_SAME_ENEMY; // 0x0
	private Int32 m_randomSeed; // 0x10
	private BattleController m_controller; // 0x18
	private List`1 m_logs; // 0x20
	private List`1 m_squad; // 0x28
	private BattleStats m_stats; // 0x30
	private BattleVerboseRecorder m_verboseRecorder; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__CreateVerboseRecorder; // 0x8
	private static DelegateBridge __Hotfix0_LogSquadAndRandomSeed; // 0x10
	private static DelegateBridge __Hotfix0_LogManualSpawn; // 0x18
	private static DelegateBridge __Hotfix0_LogManualWithdraw; // 0x20
	private static DelegateBridge __Hotfix0_LogCharacterAutoWithdraw; // 0x28
	private static DelegateBridge __Hotfix0_LogManualSkill; // 0x30
	private static DelegateBridge __Hotfix0_LogModifier; // 0x38
	private static DelegateBridge __Hotfix0_LogEpModifier; // 0x40
	private static DelegateBridge __Hotfix0_LogEpBreakModifier; // 0x48
	private static DelegateBridge __Hotfix0_LogCharacterSnapshot; // 0x50
	private static DelegateBridge __Hotfix0_LogEnemySnapshot; // 0x58
	private static DelegateBridge __Hotfix0_LogRuneSnapshot; // 0x60
	private static DelegateBridge __Hotfix0_LogExtraBattleInfo; // 0x68
	private static DelegateBridge __Hotfix1_LogExtraBattleInfo; // 0x70
	private static DelegateBridge __Hotfix0_LogExtraBattleInfoCharacterNotMannuallySpawn; // 0x78
	private static DelegateBridge __Hotfix0_LogExtraBattleInfoCharacterKillCount; // 0x80
	private static DelegateBridge __Hotfix0_LogExtraBattleInfoEnemyDieBecauseOfFallDown; // 0x88
	private static DelegateBridge __Hotfix0_LogRoguelikeRelicSnapshot; // 0x90
	private static DelegateBridge __Hotfix0_LogExtraBattleInfoAddCount; // 0x98
	private static DelegateBridge __Hotfix0_LogExtraBattleInfoMaxCount; // 0xa0
	private static DelegateBridge __Hotfix0_OnCharacterFinish; // 0xa8
	private static DelegateBridge __Hotfix0_OnEnemyBorn; // 0xb0
	private static DelegateBridge __Hotfix0_OnEnemyFinish; // 0xb8
	private static DelegateBridge __Hotfix0_OnSkillTrig; // 0xc0
	private static DelegateBridge __Hotfix0_OnCostUnnaturalRecovered; // 0xc8
	private static DelegateBridge __Hotfix0_OnAutoReplayCancelled; // 0xd0
	private static DelegateBridge __Hotfix0_ClearAll; // 0xd8
	private static DelegateBridge __Hotfix0_AchieveStats; // 0xe0
	private static DelegateBridge __Hotfix0_AchieveJournal; // 0xe8
	private static DelegateBridge __Hotfix0_AchievePackedRuneDataList; // 0xf0
	private static DelegateBridge __Hotfix0_AchieveSixStarRuneDataList; // 0xf8
	private static DelegateBridge __Hotfix0__AppendLog; // 0x100
	private static DelegateBridge __Hotfix0__CheckPlayerSide; // 0x108


	// RVA: 0x3fdae40 VA: 0x75965f2e40
	public Void .ctor(BattleController controller, GameModeType gameModeType) { }
	// RVA: 0x3fdb4c8 VA: 0x75965f34c8
	private Void _CreateVerboseRecorder(GameModeType gameModeType) { }
	// RVA: 0x3fdb668 VA: 0x75965f3668
	public Void LogSquadAndRandomSeed(BattlePlayerData playerData, Int32 randomSeed, PlayerSide playerSide) { }
	// RVA: 0x3fdba70 VA: 0x75965f3a70
	public Void LogManualSpawn(BattleCharacterData data, Direction direction, GridPosition pos, Boolean ignoreCharStats) { }
	// RVA: 0x3fdbd6c VA: 0x75965f3d6c
	public Void LogManualWithdraw(BattleCharacterData data, GridPosition pos) { }
	// RVA: 0x3fdbe9c VA: 0x75965f3e9c
	public Void LogCharacterAutoWithdraw(BattleCharacterData data) { }
	// RVA: 0x3fdbf70 VA: 0x75965f3f70
	public Void LogManualSkill(BattleCharacterData data, GridPosition pos, Boolean isHidden) { }
	// RVA: 0x3fdc068 VA: 0x75965f4068
	public Void LogModifier(ref Modifier modifier) { }
	// RVA: 0x3fdc830 VA: 0x75965f4830
	public Void LogEpModifier(ref Modifier modifier) { }
	// RVA: 0x3fd32e0 VA: 0x75965eb2e0
	public Void LogEpBreakModifier(Character character, ElementType elementType) { }
	// RVA: 0x3fdcc38 VA: 0x75965f4c38
	public Boolean LogCharacterSnapshot(Character character) { }
	// RVA: 0x3fdcf50 VA: 0x75965f4f50
	public Boolean LogEnemySnapshot(EnemyData data) { }
	// RVA: 0x3fdd2e0 VA: 0x75965f52e0
	public Boolean LogRuneSnapshot() { }
	// RVA: 0x3fdd880 VA: 0x75965f5880
	public Boolean LogExtraBattleInfo(String key, Int32 value, Boolean overwrite) { }
	// RVA: 0x3fda7a4 VA: 0x75965f27a4
	public Boolean LogExtraBattleInfo(String key, Int32 value) { }
	// RVA: 0x3fddab4 VA: 0x75965f5ab4
	public Boolean LogExtraBattleInfoCharacterNotMannuallySpawn(String key) { }
	// RVA: 0x3fddb80 VA: 0x75965f5b80
	public Boolean LogExtraBattleInfoCharacterKillCount(String key) { }
	// RVA: 0x3fddc4c VA: 0x75965f5c4c
	public Boolean LogExtraBattleInfoEnemyDieBecauseOfFallDown(String key) { }
	// RVA: 0x3fddd18 VA: 0x75965f5d18
	public Boolean LogRoguelikeRelicSnapshot(IEnumerable`1 relics) { }
	// RVA: 0x3fde1b0 VA: 0x75965f61b0
	public Boolean LogExtraBattleInfoAddCount(ExtraLogType logType, List`1 indexs) { }
	// RVA: 0x3fde488 VA: 0x75965f6488
	public Boolean LogExtraBattleInfoMaxCount(ExtraLogType logType, List`1 indexs, Int32 new_count) { }
	// RVA: 0x3fde7ac VA: 0x75965f67ac
	public Void OnCharacterFinish(BattleCharacterData data, FinishReason reason) { }
	// RVA: 0x3fde8bc VA: 0x75965f68bc
	public Void OnEnemyBorn(EnemyData data) { }
	// RVA: 0x3fde990 VA: 0x75965f6990
	public Void OnEnemyFinish(EnemyData data, Options options, FinishReason reason) { }
	// RVA: 0x3fdeb30 VA: 0x75965f6b30
	public Void OnSkillTrig(BattleCharacterData data) { }
	// RVA: 0x3fded14 VA: 0x75965f6d14
	public Void OnCostUnnaturalRecovered(Int32 cost) { }
	// RVA: 0x3fdeda4 VA: 0x75965f6da4
	public Void OnAutoReplayCancelled() { }
	// RVA: 0x3fdee1c VA: 0x75965f6e1c
	public Void ClearAll() { }
	// RVA: 0x3fdf270 VA: 0x75965f7270
	public BattleStats AchieveStats(BattleController controller) { }
	// RVA: 0x3fdf850 VA: 0x75965f7850
	public Journal AchieveJournal(BattleController controller) { }
	// RVA: 0x3fdfb4c VA: 0x75965f7b4c
	public List`1 AchievePackedRuneDataList() { }
	// RVA: 0x3fdfd14 VA: 0x75965f7d14
	public List`1 AchieveSixStarRuneDataList() { }
	// RVA: 0x3fdbbb4 VA: 0x75965f3bb4
	private Void _AppendLog(LogItem log) { }
	// RVA: 0x3fdc674 VA: 0x75965f4674
	private Boolean _CheckPlayerSide(PlayerSide sourceSide) { }
}
```
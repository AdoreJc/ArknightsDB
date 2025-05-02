# RoguelikeGameMode

**Namespace:** ` `


## Fields

- `RoguelikeInput m_input`

- `RoguelikeBattleManager m_roguelikeManager`

- `RoguelikeBattleExpManager m_expManager`

- `RoguelikeBattleTopicHolder m_topicHolder`

- `Int32 m_diceIndex`

- `Int32 <diceRoll>k__BackingField`


## Properties

- `Int32 diceRoll`

- `Int32 san`

- `Boolean isFragmentWeightLimit`

- `Boolean hasInspiration`

- `Int32 inputHp`

- `Int32 inputShield`

- `PlayerNodeForesightType foresightType`

- `RoguelikeEventType eventType`

- `Boolean isSpecialExpUIStyle`

- `RoguelikeBattleTopicHolder topicHolder`

- `RoguelikeBattleExpManager expManager`


## Methods

- `Int32 get_diceRoll()`

- `Void set_diceRoll(Int32)`

- `Int32 get_san()`

- `Boolean get_isFragmentWeightLimit()`

- `Boolean get_hasInspiration()`

- `Int32 get_inputHp()`

- `Int32 get_inputShield()`

- `PlayerNodeForesightType get_foresightType()`

- `RoguelikeEventType get_eventType()`

- `Boolean get_isSpecialExpUIStyle()`

- `RoguelikeBattleTopicHolder get_topicHolder()`

- `RoguelikeBattleExpManager get_expManager()`

- `Void _ProcessExtraProfession(BattleCharacterData, Blackboard)`

- `Boolean TryRollDice(out)`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Void <>xLuaBaseProxy_OnPostInit()`

- `Void <>xLuaBaseProxy_PreprocessPlayerData(List`1)`

- `Options <>xLuaBaseProxy_PostprocessLevelOptions(Options)`

- `Void <>xLuaBaseProxy_PreprocessLevelData(LevelData)`

- `Void <>xLuaBaseProxy_PostprocessRuneExtraData(RuneLevelExtraOutput)`

- `Void <>xLuaBaseProxy_PreprocessCharacterCard(BattleCharacterData, Character)`

- `Void <>xLuaBaseProxy_PreProcessDeckCards(IList`1)`

- `Void <>xLuaBaseProxy_PreprocessEnemy(EnemyData)`

- `Boolean <>xLuaBaseProxy_NeedPreprocessPredefinedCharacter()`

- `Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoguelikeGameMode : DefaultGameMode
{
	protected RoguelikeInput m_input; // 0x20
	private RoguelikeBattleManager m_roguelikeManager; // 0x28
	private RoguelikeBattleExpManager m_expManager; // 0x30
	private RoguelikeBattleTopicHolder m_topicHolder; // 0x38
	private List`1 m_diceRoll; // 0x40
	private Int32 m_diceIndex; // 0x48
	private Int32 <diceRoll>k__BackingField; // 0x4c
	private const AlgorithmType RANDOM_ALGORITHM; // 0x0
	private static Random s_randomRogueScheduler; // 0x0
	private static Random s_randomRogueRelic; // 0x8
	private static DelegateBridge __Hotfix0_get_diceRoll; // 0x10
	private static DelegateBridge __Hotfix0_set_diceRoll; // 0x18
	private static DelegateBridge __Hotfix0_get_san; // 0x20
	private static DelegateBridge __Hotfix0_get_isFragmentWeightLimit; // 0x28
	private static DelegateBridge __Hotfix0_get_hasInspiration; // 0x30
	private static DelegateBridge __Hotfix0_get_inputHp; // 0x38
	private static DelegateBridge __Hotfix0_get_inputShield; // 0x40
	private static DelegateBridge __Hotfix0_get_foresightType; // 0x48
	private static DelegateBridge __Hotfix0_get_eventType; // 0x50
	private static DelegateBridge __Hotfix0_get_isSpecialExpUIStyle; // 0x58
	private static DelegateBridge __Hotfix0_get_fragmentCarryCharUniqueList; // 0x60
	private static DelegateBridge __Hotfix0_get_enemyHpInfo; // 0x68
	private static DelegateBridge __Hotfix0_get_randomRogueScheduler; // 0x70
	private static DelegateBridge __Hotfix0_get_randomRogueRelic; // 0x78
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x80
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x88
	private static DelegateBridge __Hotfix0_get_topicHolder; // 0x90
	private static DelegateBridge __Hotfix0_get_expManager; // 0x98
	private static DelegateBridge __Hotfix0_Init; // 0xa0
	private static DelegateBridge __Hotfix0_OnPostInit; // 0xa8
	private static DelegateBridge __Hotfix0_PreprocessPlayerData; // 0xb0
	private static DelegateBridge __Hotfix0__ProcessExtraProfession; // 0xb8
	private static DelegateBridge __Hotfix0_PostprocessLevelOptions; // 0xc0
	private static DelegateBridge __Hotfix0_PreprocessLevelData; // 0xc8
	private static DelegateBridge __Hotfix0_PostprocessRuneExtraData; // 0xd0
	private static DelegateBridge __Hotfix0_PreprocessCharacterCard; // 0xd8
	private static DelegateBridge __Hotfix0_PreProcessDeckCards; // 0xe0
	private static DelegateBridge __Hotfix0_PreprocessEnemy; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0
	private static DelegateBridge __Hotfix0_GatherGlobalBuffs; // 0xf8
	private static DelegateBridge __Hotfix0_GatherEnvSystems; // 0x100
	private static DelegateBridge __Hotfix0_NeedPreprocessPredefinedCharacter; // 0x108
	private static DelegateBridge __Hotfix0_GatherPreloadAssets; // 0x110
	private static DelegateBridge __Hotfix0__TryGatherGlobalbuffIds; // 0x118
	private static DelegateBridge __Hotfix0__TryGatherEnvSystemIds; // 0x120
	private static DelegateBridge __Hotfix0__TryGatherDynamicAbility; // 0x128
	private static DelegateBridge __Hotfix0__TryGatherTempTokens; // 0x130
	private static DelegateBridge __Hotfix0__TryGatherTempCharacters; // 0x138
	private static DelegateBridge __Hotfix0_OnApplyingGlobalModifier; // 0x140
	private static DelegateBridge __Hotfix0_TryRollDice; // 0x148

	public Int32 diceRoll { get; set; }
	public Int32 san { get; }
	public Boolean isFragmentWeightLimit { get; }
	public Boolean hasInspiration { get; }
	public Int32 inputHp { get; }
	public Int32 inputShield { get; }
	public PlayerNodeForesightType foresightType { get; }
	public RoguelikeEventType eventType { get; }
	public Boolean isSpecialExpUIStyle { get; }
	public List`1 fragmentCarryCharUniqueList { get; }
	public Dictionary`2 enemyHpInfo { get; }
	public static Random randomRogueScheduler { get; }
	public static Random randomRogueRelic { get; }
	public override GameModeType gameModeType { get; }
	public RoguelikeBattleTopicHolder topicHolder { get; }
	public RoguelikeBattleExpManager expManager { get; }

	// RVA: 0x1cf4e24 VA: 0x759430ce24
	public Int32 get_diceRoll() { }
	// RVA: 0x1cf4e9c VA: 0x759430ce9c
	private Void set_diceRoll(Int32 value) { }
	// RVA: 0x1cf4f28 VA: 0x759430cf28
	public Int32 get_san() { }
	// RVA: 0x1cf4fac VA: 0x759430cfac
	public Boolean get_isFragmentWeightLimit() { }
	// RVA: 0x1cf5030 VA: 0x759430d030
	public Boolean get_hasInspiration() { }
	// RVA: 0x1cf50b4 VA: 0x759430d0b4
	public Int32 get_inputHp() { }
	// RVA: 0x1cf5138 VA: 0x759430d138
	public Int32 get_inputShield() { }
	// RVA: 0x1cf51bc VA: 0x759430d1bc
	public PlayerNodeForesightType get_foresightType() { }
	// RVA: 0x1cf5240 VA: 0x759430d240
	public RoguelikeEventType get_eventType() { }
	// RVA: 0x1cf52c4 VA: 0x759430d2c4
	public Boolean get_isSpecialExpUIStyle() { }
	// RVA: 0x1cf5348 VA: 0x759430d348
	public List`1 get_fragmentCarryCharUniqueList() { }
	// RVA: 0x1cf53cc VA: 0x759430d3cc
	public Dictionary`2 get_enemyHpInfo() { }
	// RVA: 0x1cf5450 VA: 0x759430d450
	public static Random get_randomRogueScheduler() { }
	// RVA: 0x1cf54d8 VA: 0x759430d4d8
	public static Random get_randomRogueRelic() { }
	// RVA: 0x1cf4bbc VA: 0x759430cbbc
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cf4c48 VA: 0x759430cc48
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cf5560 VA: 0x759430d560
	public RoguelikeBattleTopicHolder get_topicHolder() { }
	// RVA: 0x1cf55d8 VA: 0x759430d5d8
	public RoguelikeBattleExpManager get_expManager() { }
	// RVA: 0x1cf0c64 VA: 0x7594308c64
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1cf5650 VA: 0x759430d650
	public override Void OnPostInit() { }
	// RVA: 0x1cf5718 VA: 0x759430d718
	public override Void PreprocessPlayerData(List`1 dataList) { }
	// RVA: 0x1cf5a58 VA: 0x759430da58
	private Void _ProcessExtraProfession(BattleCharacterData data, Blackboard blackboard) { }
	// RVA: 0x1cf5ba0 VA: 0x759430dba0
	public override Options PostprocessLevelOptions(Options options) { }
	// RVA: 0x1cf5c4c VA: 0x759430dc4c
	public override Void PreprocessLevelData(LevelData levelData) { }
	// RVA: 0x1cf5cfc VA: 0x759430dcfc
	public override Void PostprocessRuneExtraData(RuneLevelExtraOutput extraData) { }
	// RVA: 0x1cf5e7c VA: 0x759430de7c
	public override Void PreprocessCharacterCard(BattleCharacterData data, Character character) { }
	// RVA: 0x1cf1a6c VA: 0x7594309a6c
	public override Void PreProcessDeckCards(IList`1 cards) { }
	// RVA: 0x1cf5f8c VA: 0x759430df8c
	public override Void PreprocessEnemy(EnemyData data) { }
	// RVA: 0x1cf2ad0 VA: 0x759430aad0
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1cf6098 VA: 0x759430e098
	public override List`1 GatherGlobalBuffs() { }
	// RVA: 0x1cf611c VA: 0x759430e11c
	public override List`1 GatherEnvSystems() { }
	// RVA: 0x1cf61a0 VA: 0x759430e1a0
	public override Boolean NeedPreprocessPredefinedCharacter() { }
	// RVA: 0x1cf6224 VA: 0x759430e224
	public static Dictionary`2 GatherPreloadAssets() { }
	// RVA: 0x1cf6d40 VA: 0x759430ed40
	private static Void _TryGatherGlobalbuffIds(RoguelikeBuff buff, HashSet`1 global_buff_ids) { }
	// RVA: 0x1cf6bb4 VA: 0x759430ebb4
	private static Void _TryGatherEnvSystemIds(RoguelikeBuff buff, HashSet`1 env_system_ids) { }
	// RVA: 0x1cf67ac VA: 0x759430e7ac
	private static Void _TryGatherDynamicAbility(RoguelikeBuff buff, List`1 list) { }
	// RVA: 0x1cf69c0 VA: 0x759430e9c0
	private static Void _TryGatherTempTokens(RoguelikeBuff buff, List`1 list) { }
	// RVA: 0x1cf6f68 VA: 0x759430ef68
	private static Void _TryGatherTempCharacters(RoguelikeInput input, List`1 charList, List`1 tokenList) { }
	// RVA: 0x1cf4d88 VA: 0x759430cd88
	public override Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1cf71fc VA: 0x759430f1fc
	public Boolean TryRollDice(out Int32 diceVal) { }
	// RVA: 0x1cf7320 VA: 0x759430f320
	private static Void .cctor() { }
	// RVA: 0x1cf73a4 VA: 0x759430f3a4
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cf73ac VA: 0x759430f3ac
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1cf73b4 VA: 0x759430f3b4
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1cf73bc VA: 0x759430f3bc
	private Void <>xLuaBaseProxy_OnPostInit() { }
	// RVA: 0x1cf73c4 VA: 0x759430f3c4
	private Void <>xLuaBaseProxy_PreprocessPlayerData(List`1 P0) { }
	// RVA: 0x1cf73cc VA: 0x759430f3cc
	private Options <>xLuaBaseProxy_PostprocessLevelOptions(Options P0) { }
	// RVA: 0x1cf73d4 VA: 0x759430f3d4
	private Void <>xLuaBaseProxy_PreprocessLevelData(LevelData P0) { }
	// RVA: 0x1cf73dc VA: 0x759430f3dc
	private Void <>xLuaBaseProxy_PostprocessRuneExtraData(RuneLevelExtraOutput P0) { }
	// RVA: 0x1cf73e4 VA: 0x759430f3e4
	private Void <>xLuaBaseProxy_PreprocessCharacterCard(BattleCharacterData P0, Character P1) { }
	// RVA: 0x1cf73ec VA: 0x759430f3ec
	private Void <>xLuaBaseProxy_PreProcessDeckCards(IList`1 P0) { }
	// RVA: 0x1cf73f4 VA: 0x759430f3f4
	private Void <>xLuaBaseProxy_PreprocessEnemy(EnemyData P0) { }
	// RVA: 0x1cf73fc VA: 0x759430f3fc
	private List`1 <>xLuaBaseProxy_GatherGlobalBuffs() { }
	// RVA: 0x1cf7404 VA: 0x759430f404
	private List`1 <>xLuaBaseProxy_GatherEnvSystems() { }
	// RVA: 0x1cf740c VA: 0x759430f40c
	private Boolean <>xLuaBaseProxy_NeedPreprocessPredefinedCharacter() { }
	// RVA: 0x1cf7414 VA: 0x759430f414
	private Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref Modifier P0) { }
}
```
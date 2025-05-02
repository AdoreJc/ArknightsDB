# SandboxLevelDataProcessor

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `SandboxGameMode m_gameMode`

- `SandboxBattleManager m_manager`

- `PhaseData m_rushEnemyPhase`

- `PhaseData m_rareAnimalPhase`

- `Int32 m_insectPhaseIndex`


## Properties

- `SandboxInput input`

- `SandboxLevelConfig levelConfig`

- `SandboxV2Data configData`


## Methods

- `SandboxInput get_input()`

- `SandboxLevelConfig get_levelConfig()`

- `SandboxV2Data get_configData()`

- `SchedulerPreprocessor GetSchedulerPreprocessor()`

- `Void Init(LevelData, BattlePlayerData)`

- `Void OnStartGame()`

- `IEnumerator OnFinalSchedule()`

- `Single CheckBlockRushEnemyActionTime()`

- `Void SummonNextInsectPhase()`

- `Void _ParseFoodRune()`

- `Void _ParseMiscLevelData(LevelData)`

- `Void _ParseRushEnemy(LevelData)`

- `Single _CalculateRushEnemyPreDelayOffset()`

- `Boolean _ParseRushEnemy(LevelData, RushEnemy, Single)`

- `Void _ParseLureRacer(LevelData, RushEnemy)`

- `Boolean _ParseRushEnemyAction(LevelData, RushEnemy, Single, out)`

- `ActionData _GetFallbackAction(LevelData)`

- `Void _ParseExtraLoadEnemy(String, List`1)`

- `Void _ParseRuneDatas(LevelData)`

- `Void _ParsePredefinedData(LevelData, BattlePlayerData)`

- `Void _ParseConstructItems()`

- `Void _ParsePlacedItems()`

- `Void PostPreprocessLevel(LevelData)`

- `Void _ParseNPCPredefinedData(LevelData)`

- `Void _ParseShinyAnimals(LevelData)`

- `Boolean ProcessSpecialEnemy(Enemy)`

- `Void <_ParseFoodRune>b__31_0(RuneData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxLevelDataProcessor : IHotfixable
{
	private SandboxGameMode m_gameMode; // 0x10
	private SandboxBattleManager m_manager; // 0x18
	private List`1 m_rushEnemyActions; // 0x20
	private PhaseData m_rushEnemyPhase; // 0x28
	private List`1 m_rareAnimalActions; // 0x30
	private PhaseData m_rareAnimalPhase; // 0x38
	private List`1 m_lureRacerActions; // 0x40
	private List`1 m_predefinedTokenCards; // 0x48
	private List`1 m_predefinedTokenInsts; // 0x50
	private List`1 m_originPredefinedInsts; // 0x58
	private List`1 m_extraLevelRunes; // 0x60
	private ListDict`2 m_shinyAnimalStatus; // 0x68
	private List`1 m_charactersWithFoodBuff; // 0x70
	private Int32 m_insectPhaseIndex; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_input; // 0x8
	private static DelegateBridge __Hotfix0_get_levelConfig; // 0x10
	private static DelegateBridge __Hotfix0_get_configData; // 0x18
	private static DelegateBridge __Hotfix0_get_originPredefinedInsts; // 0x20
	private static DelegateBridge __Hotfix0_get_charactersWithFoodBuff; // 0x28
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x38
	private static DelegateBridge __Hotfix0_OnStartGame; // 0x40
	private static DelegateBridge __Hotfix0_OnFinalSchedule; // 0x48
	private static DelegateBridge __Hotfix0_CheckBlockRushEnemyActionTime; // 0x50
	private static DelegateBridge __Hotfix0_SummonNextInsectPhase; // 0x58
	private static DelegateBridge __Hotfix0__ParseFoodRune; // 0x60
	private static DelegateBridge __Hotfix0__ParseMiscLevelData; // 0x68
	private static DelegateBridge __Hotfix0__ParseRushEnemy; // 0x70
	private static DelegateBridge __Hotfix0__CalculateRushEnemyPreDelayOffset; // 0x78
	private static DelegateBridge __Hotfix1__ParseRushEnemy; // 0x80
	private static DelegateBridge __Hotfix0__ParseLureRacer; // 0x88
	private static DelegateBridge __Hotfix0__ParseRushEnemyAction; // 0x90
	private static DelegateBridge __Hotfix0__GetFallbackAction; // 0x98
	private static DelegateBridge __Hotfix0__ParseExtraLoadEnemy; // 0xa0
	private static DelegateBridge __Hotfix0__ParseRuneDatas; // 0xa8
	private static DelegateBridge __Hotfix0__ParsePredefinedData; // 0xb0
	private static DelegateBridge __Hotfix0__ParseConstructItems; // 0xb8
	private static DelegateBridge __Hotfix0__ParsePlacedItems; // 0xc0
	private static DelegateBridge __Hotfix0_PostPreprocessLevel; // 0xc8
	private static DelegateBridge __Hotfix0__ParseNPCPredefinedData; // 0xd0
	private static DelegateBridge __Hotfix0__ParseShinyAnimals; // 0xd8
	private static DelegateBridge __Hotfix0_ProcessSpecialEnemy; // 0xe0

	public SandboxInput input { get; }
	public SandboxLevelConfig levelConfig { get; }
	public SandboxV2Data configData { get; }
	public List`1 originPredefinedInsts { get; }
	public List`1 charactersWithFoodBuff { get; }

	// RVA: 0x1dfadec VA: 0x7594412dec
	public Void .ctor(SandboxGameMode gameMode, SandboxBattleManager manager) { }
	// RVA: 0x1dfb16c VA: 0x759441316c
	public SandboxInput get_input() { }
	// RVA: 0x1dfb1e0 VA: 0x75944131e0
	public SandboxLevelConfig get_levelConfig() { }
	// RVA: 0x1dfb258 VA: 0x7594413258
	public SandboxV2Data get_configData() { }
	// RVA: 0x1dfb2cc VA: 0x75944132cc
	public List`1 get_originPredefinedInsts() { }
	// RVA: 0x1dfb334 VA: 0x7594413334
	public List`1 get_charactersWithFoodBuff() { }
	// RVA: 0x1dfb39c VA: 0x759441339c
	public SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1dfb464 VA: 0x7594413464
	public Void Init(LevelData levelData, BattlePlayerData playerData) { }
	// RVA: 0x1dfc804 VA: 0x7594414804
	public Void OnStartGame() { }
	// RVA: 0x1df3ec0 VA: 0x759440bec0
	public IEnumerator OnFinalSchedule() { }
	// RVA: 0x1dfcf78 VA: 0x7594414f78
	public Single CheckBlockRushEnemyActionTime() { }
	// RVA: 0x1dfd064 VA: 0x7594415064
	public Void SummonNextInsectPhase() { }
	// RVA: 0x1dfcdac VA: 0x7594414dac
	private Void _ParseFoodRune() { }
	// RVA: 0x1dfc6a0 VA: 0x75944146a0
	private Void _ParseMiscLevelData(LevelData levelData) { }
	// RVA: 0x1dfb51c VA: 0x759441351c
	private Void _ParseRushEnemy(LevelData levelData) { }
	// RVA: 0x1dfd690 VA: 0x7594415690
	private Single _CalculateRushEnemyPreDelayOffset() { }
	// RVA: 0x1dfd41c VA: 0x759441541c
	private Boolean _ParseRushEnemy(LevelData levelData, RushEnemy rushEnemy, Single preDelayOffset) { }
	// RVA: 0x1dfd574 VA: 0x7594415574
	private Void _ParseLureRacer(LevelData levelData, RushEnemy rushEnemy) { }
	// RVA: 0x1dfd968 VA: 0x7594415968
	private Boolean _ParseRushEnemyAction(LevelData levelData, RushEnemy rushEnemy, Single preDelayOffset, out ActionData actionData) { }
	// RVA: 0x1dfdfa0 VA: 0x7594415fa0
	private ActionData _GetFallbackAction(LevelData levelData) { }
	// RVA: 0x1dfd2c0 VA: 0x75944152c0
	private Void _ParseExtraLoadEnemy(String enemyId, List`1 extraLoadEnemies) { }
	// RVA: 0x1dfbe30 VA: 0x7594413e30
	private Void _ParseRuneDatas(LevelData levelData) { }
	// RVA: 0x1dfb994 VA: 0x7594413994
	private Void _ParsePredefinedData(LevelData levelData, BattlePlayerData playerData) { }
	// RVA: 0x1dfe13c VA: 0x759441613c
	private Void _ParseConstructItems() { }
	// RVA: 0x1dfe4e8 VA: 0x75944164e8
	private Void _ParsePlacedItems() { }
	// RVA: 0x1dfed7c VA: 0x7594416d7c
	public Void PostPreprocessLevel(LevelData levelData) { }
	// RVA: 0x1dfe848 VA: 0x7594416848
	private Void _ParseNPCPredefinedData(LevelData levelData) { }
	// RVA: 0x1dfc9f8 VA: 0x75944149f8
	private Void _ParseShinyAnimals(LevelData levelData) { }
	// RVA: 0x1dff2c8 VA: 0x75944172c8
	public Boolean ProcessSpecialEnemy(Enemy enemy) { }
	// RVA: 0x1dff490 VA: 0x7594417490
	private Void <_ParseFoodRune>b__31_0(RuneData rune) { }
}
```
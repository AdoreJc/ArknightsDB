# EnemyDuelPlayerManager

**Namespace:** ` `


## Fields

- `Int32 m_curRoundIndex`

- `EnemyDuelPlayerData m_selfPlayerData`

- `ActivityEnemyDuelModeData m_subModeData`

- `ActivityEnemyDuelData m_actData`

- `Random m_playerRandom`

- `Boolean m_hasNpcPlayer`


## Methods

- `Void InitPlayers(LevelData, ActivityEnemyDuelData, ActivityEnemyDuelModeData, EnemyDuelInput)`

- `Void ResetSeed(Int32)`

- `Void PreparePlayerDataBeforeWaveStart(Int32)`

- `Void CalculateNpcChoiceOnBet(EnemyDuelGameMode, ActivityEnemyDuelRoundData)`

- `Void CalculateNpcFinalScore(Int32, Int32, List`1)`

- `Void _ProcessPlayerData(ActivityEnemyDuelData, EnemyDuelInput)`

- `Void _ProcessNpcData(ActivityEnemyDuelData, Dictionary`2, List`1)`

- `Void _ProcessNpcData(ActivityEnemyDuelData, Int32, Dictionary`2)`

- `Int32 _GetNpcSurviveCnt(Dictionary`2)`

- `Void _CalculateRestNpcResult(List`1, Int32, Dictionary`2)`

- `Void _CalculateNpcChoice(EnemyDuelGameMode, ActivityEnemyDuelRoundData)`

- `Void _CalculateDefaultStrategy(EnemyDuelPlayerData, ActivityEnemyDuelNpcData)`

- `Single _CalculateTeamScoreBySide(Boolean, ActivityEnemyDuelNpcData)`

- `Void _CalculateChooseWinStrategy(EnemyDuelPlayerData)`

- `Void _CalculateChooseOddStrategy(EnemyDuelPlayerData)`

- `Void _CalculateFollowStrategy(EnemyDuelPlayerData, Boolean, Dictionary`2)`

- `Void _CalculateChooseByEnemyCountParityStrategy(EnemyDuelPlayerData, Boolean)`

- `Int32 _GetEnemyCountParityBySide(Boolean)`

- `Void _CalculateFixedChoiceStrategy(EnemyDuelPlayerData, Boolean)`

- `Void _RefreshNpcChoice(EnemyDuelPlayerData, Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyDuelPlayerManager : IHotfixable
{
	private Int32 m_curRoundIndex; // 0x10
	private readonly List`1 m_npcSortList; // 0x18
	private readonly Dictionary`2 m_npcSelectorData; // 0x20
	private EnemyDuelPlayerData m_selfPlayerData; // 0x28
	private ActivityEnemyDuelModeData m_subModeData; // 0x30
	private ActivityEnemyDuelData m_actData; // 0x38
	private Random m_playerRandom; // 0x40
	private Boolean m_hasNpcPlayer; // 0x48
	private static DelegateBridge __Hotfix0_InitPlayers; // 0x0
	private static DelegateBridge __Hotfix0_ResetSeed; // 0x8
	private static DelegateBridge __Hotfix0_PreparePlayerDataBeforeWaveStart; // 0x10
	private static DelegateBridge __Hotfix0_CalculateNpcChoiceOnBet; // 0x18
	private static DelegateBridge __Hotfix0_CalculateNpcFinalScore; // 0x20
	private static DelegateBridge __Hotfix0__ProcessPlayerData; // 0x28
	private static DelegateBridge __Hotfix0__ProcessNpcData; // 0x30
	private static DelegateBridge __Hotfix1__ProcessNpcData; // 0x38
	private static DelegateBridge __Hotfix0__GetNpcSurviveCnt; // 0x40
	private static DelegateBridge __Hotfix0__CalculateRestNpcResult; // 0x48
	private static DelegateBridge __Hotfix0__CalculateNpcChoice; // 0x50
	private static DelegateBridge __Hotfix0__CalculateDefaultStrategy; // 0x58
	private static DelegateBridge __Hotfix0__CalculateTeamScoreBySide; // 0x60
	private static DelegateBridge __Hotfix0__CalculateChooseWinStrategy; // 0x68
	private static DelegateBridge __Hotfix0__CalculateChooseOddStrategy; // 0x70
	private static DelegateBridge __Hotfix0__CalculateFollowStrategy; // 0x78
	private static DelegateBridge __Hotfix0__CalculateChooseByEnemyCountParityStrategy; // 0x80
	private static DelegateBridge __Hotfix0__GetEnemyCountParityBySide; // 0x88
	private static DelegateBridge __Hotfix0__CalculateFixedChoiceStrategy; // 0x90
	private static DelegateBridge __Hotfix0__RefreshNpcChoice; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x1cd1b9c VA: 0x75942e9b9c
	public Void InitPlayers(LevelData levelData, ActivityEnemyDuelData actData, ActivityEnemyDuelModeData subModeData, EnemyDuelInput inputData) { }
	// RVA: 0x1cd2220 VA: 0x75942ea220
	public Void ResetSeed(Int32 seed) { }
	// RVA: 0x1cd22b4 VA: 0x75942ea2b4
	public Void PreparePlayerDataBeforeWaveStart(Int32 curRoundIndex) { }
	// RVA: 0x1cd2330 VA: 0x75942ea330
	public Void CalculateNpcChoiceOnBet(EnemyDuelGameMode gameMode, ActivityEnemyDuelRoundData roundData) { }
	// RVA: 0x1cd27b4 VA: 0x75942ea7b4
	public Void CalculateNpcFinalScore(Int32 remainingRoundCnt, Int32 roundIndex, List`1 roundDataList) { }
	// RVA: 0x1cd1cb4 VA: 0x75942e9cb4
	private Void _ProcessPlayerData(ActivityEnemyDuelData battleData, EnemyDuelInput inputData) { }
	// RVA: 0x1cd2da4 VA: 0x75942eada4
	private Void _ProcessNpcData(ActivityEnemyDuelData battleData, Dictionary`2 playerDataDict, List`1 npcIds) { }
	// RVA: 0x1cd32b8 VA: 0x75942eb2b8
	private Void _ProcessNpcData(ActivityEnemyDuelData battleData, Int32 npcCnt, Dictionary`2 playerDataDict) { }
	// RVA: 0x1cd28f0 VA: 0x75942ea8f0
	private Int32 _GetNpcSurviveCnt(Dictionary`2 playerDataDict) { }
	// RVA: 0x1cd2ab0 VA: 0x75942eaab0
	private Void _CalculateRestNpcResult(List`1 roundDataList, Int32 fakeRound, Dictionary`2 playerDataDic) { }
	// RVA: 0x1cd23dc VA: 0x75942ea3dc
	private Void _CalculateNpcChoice(EnemyDuelGameMode gameMode, ActivityEnemyDuelRoundData roundData) { }
	// RVA: 0x1cd3f78 VA: 0x75942ebf78
	private Void _CalculateDefaultStrategy(EnemyDuelPlayerData npc, ActivityEnemyDuelNpcData data) { }
	// RVA: 0x1cd4034 VA: 0x75942ec034
	private Single _CalculateTeamScoreBySide(Boolean isLeft, ActivityEnemyDuelNpcData npcInfoData) { }
	// RVA: 0x1cd3a14 VA: 0x75942eba14
	private Void _CalculateChooseWinStrategy(EnemyDuelPlayerData npc) { }
	// RVA: 0x1cd3b18 VA: 0x75942ebb18
	private Void _CalculateChooseOddStrategy(EnemyDuelPlayerData npc) { }
	// RVA: 0x1cd3bbc VA: 0x75942ebbbc
	private Void _CalculateFollowStrategy(EnemyDuelPlayerData npc, Boolean isFollowMore, Dictionary`2 playerDataDict) { }
	// RVA: 0x1cd3e14 VA: 0x75942ebe14
	private Void _CalculateChooseByEnemyCountParityStrategy(EnemyDuelPlayerData npc, Boolean chooseOdd) { }
	// RVA: 0x1cd4394 VA: 0x75942ec394
	private Int32 _GetEnemyCountParityBySide(Boolean isLeft) { }
	// RVA: 0x1cd3ed4 VA: 0x75942ebed4
	private Void _CalculateFixedChoiceStrategy(EnemyDuelPlayerData npc, Boolean alwaysLeft) { }
	// RVA: 0x1cd42e4 VA: 0x75942ec2e4
	private Void _RefreshNpcChoice(EnemyDuelPlayerData npc, Single scoreLeft, Single scoreRight) { }
	// RVA: 0x1cd455c VA: 0x75942ec55c
	public Void .ctor() { }
}
```
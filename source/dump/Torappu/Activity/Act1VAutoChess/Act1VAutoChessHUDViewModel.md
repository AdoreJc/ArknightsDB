# Act1VAutoChessHUDViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `HUDState m_hudState`

- `HUDCampShowState m_campState`

- `Int32 round`

- `Int32 enemyCount`

- `Int32 enemyMax`

- `Int32 def`

- `Int32 damageEnemyCnt`

- `Boolean isHandCntExceed`

- `Int32 charDamage`

- `Int32 coin`

- `Act1VAutoChessHUDHealthViewModel selfHp`

- `Act1VAutoChessHUDRoundStartViewModel roundStart`

- `Act1VAutoChessHUDRoundResultViewModel roundResult`

- `Boolean isPause`

- `SpeedLevel speedLevel`

- `Act1VAutoChessHUDCampSelfViewModel selfCamp`

- `Act1VAutoChessHUDCampEnemyViewModel enemyCamp`

- `String defDamageTip`

- `String charDamageTip`

- `Boolean isSpecialRound`

- `Boolean isTraining`

- `String m_bandId`

- `Act1VAutoChessBandData m_bandData`


## Properties

- `HUDCampShowState campState`

- `HUDState hudState`


## Methods

- `HUDCampShowState get_campState()`

- `HUDState get_hudState()`

- `Void LoadData(AutoChessGame, ActivityAutoChessVerify1Data)`

- `Void LoadDataForRoundStartEnd(AutoChessGame, ActivityAutoChessVerify1Data, RoundBattleFinishResponseViewModel, Boolean)`

- `Boolean RefreshCharDeployCnt(AutoChessDataCenter, ActivityAutoChessVerify1Data)`

- `Boolean _TryRefreshFractionCount(AutoChessDataCenter, ActivityAutoChessVerify1Data)`

- `Void SetState(HUDState)`

- `Void SetCampState(HUDCampShowState)`

- `Void ClearHintCache()`

- `Void NotifySeqUpdate(HUDSeqType)`

- `Act1VAutoChessHUDCampEnemyItemViewModel GetTargetEnemy(String)`

- `Boolean IsNewOrDifferentEnemy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDViewModel : IHotfixable
{
	private HUDState m_hudState; // 0x10
	private HUDCampShowState m_campState; // 0x14
	public Int32 round; // 0x18
	public Int32 enemyCount; // 0x1c
	public Int32 enemyMax; // 0x20
	public Int32 def; // 0x24
	public Int32 damageEnemyCnt; // 0x28
	public Boolean isHandCntExceed; // 0x2c
	public Int32 charDamage; // 0x30
	public Int32 coin; // 0x34
	public Act1VAutoChessHUDHealthViewModel selfHp; // 0x38
	public Int32[] seqNums; // 0x40
	public List`1 battleInsts; // 0x48
	public List`1 prepareHint; // 0x50
	public List`1 battleHint; // 0x58
	public Act1VAutoChessHUDRoundStartViewModel roundStart; // 0x60
	public Act1VAutoChessHUDRoundResultViewModel roundResult; // 0x68
	public Boolean isPause; // 0x70
	public SpeedLevel speedLevel; // 0x74
	public Act1VAutoChessHUDCampSelfViewModel selfCamp; // 0x78
	public Act1VAutoChessHUDCampEnemyViewModel enemyCamp; // 0x80
	public String defDamageTip; // 0x88
	public String charDamageTip; // 0x90
	public Boolean isSpecialRound; // 0x98
	public ListDict`2 professionCnts; // 0xa0
	public ListDict`2 factionCnts; // 0xa8
	public Boolean isTraining; // 0xb0
	private String m_bandId; // 0xb8
	private Act1VAutoChessBandData m_bandData; // 0xc0
	private static DelegateBridge __Hotfix0_get_campState; // 0x0
	private static DelegateBridge __Hotfix0_get_hudState; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_LoadDataForRoundStartEnd; // 0x18
	private static DelegateBridge __Hotfix0_RefreshCharDeployCnt; // 0x20
	private static DelegateBridge __Hotfix0__TryRefreshFractionCount; // 0x28
	private static DelegateBridge __Hotfix0_SetState; // 0x30
	private static DelegateBridge __Hotfix0_SetCampState; // 0x38
	private static DelegateBridge __Hotfix0_ClearHintCache; // 0x40
	private static DelegateBridge __Hotfix0_NotifySeqUpdate; // 0x48
	private static DelegateBridge __Hotfix0_GetTargetEnemy; // 0x50
	private static DelegateBridge __Hotfix0_IsNewOrDifferentEnemy; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public HUDCampShowState campState { get; }
	public HUDState hudState { get; }

	// RVA: 0x33724b8 VA: 0x759598a4b8
	public HUDCampShowState get_campState() { }
	// RVA: 0x3371064 VA: 0x7595989064
	public HUDState get_hudState() { }
	// RVA: 0x3377f34 VA: 0x759598ff34
	public Void LoadData(AutoChessGame game, ActivityAutoChessVerify1Data data) { }
	// RVA: 0x3378084 VA: 0x7595990084
	public Void LoadDataForRoundStartEnd(AutoChessGame game, ActivityAutoChessVerify1Data data, RoundBattleFinishResponseViewModel resp, Boolean hasEnterBattleStateAlready) { }
	// RVA: 0x33770a0 VA: 0x759598f0a0
	public Boolean RefreshCharDeployCnt(AutoChessDataCenter dataCenter, ActivityAutoChessVerify1Data data) { }
	// RVA: 0x337f904 VA: 0x7595997904
	private Boolean _TryRefreshFractionCount(AutoChessDataCenter dataCenter, ActivityAutoChessVerify1Data data) { }
	// RVA: 0x3377490 VA: 0x759598f490
	public Void SetState(HUDState state) { }
	// RVA: 0x337452c VA: 0x759598c52c
	public Void SetCampState(HUDCampShowState campState) { }
	// RVA: 0x33775f0 VA: 0x759598f5f0
	public Void ClearHintCache() { }
	// RVA: 0x3372d8c VA: 0x759598ad8c
	public Void NotifySeqUpdate(HUDSeqType seqType) { }
	// RVA: 0x337ad3c VA: 0x7595992d3c
	public Act1VAutoChessHUDCampEnemyItemViewModel GetTargetEnemy(String forceId) { }
	// RVA: 0x3379db0 VA: 0x7595991db0
	public Boolean IsNewOrDifferentEnemy() { }
	// RVA: 0x337ff0c VA: 0x7595997f0c
	public Void .ctor() { }
}
```
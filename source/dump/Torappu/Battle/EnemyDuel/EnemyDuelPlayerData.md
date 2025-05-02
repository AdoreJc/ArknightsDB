# EnemyDuelPlayerData

**Namespace:** `Torappu.Battle.EnemyDuel`


## Fields

- `String playerId`

- `String nickName`

- `String playerAvatarId`

- `PlayerAvatarType playerAvatarType`

- `Int32 curScore`

- `Int32 betScore`

- `Int32 rewardScore`

- `Int32 scoreBeforeSettle`

- `Int32 winStreak`

- `Int32 maxRound`

- `EnemyDuelChoiceType curChoiceType`

- `Boolean isNpc`

- `Int64 updateTs`

- `EnemyDuelRoundResult m_curRoundResult`

- `EnemyDuelChoiceSide m_curChoiceSide`

- `Boolean m_lastChoiceCorrect`

- `Boolean m_lastChoiceIsRight`

- `Boolean m_choiceIsRight`

- `Boolean m_hasChosen`

- `Boolean m_isSurvive`

- `EnemyDuelShieldState m_shieldState`

- `Boolean <isSelf>k__BackingField`


## Properties

- `Boolean isSelf`

- `Boolean hasChosen`

- `Boolean hasShield`

- `Boolean justUsedShield`

- `EnemyDuelChoiceSide curChoiceSide`

- `EnemyDuelRoundResult curRoundResult`

- `Boolean lastChoiceCorrect`

- `Boolean lastChoiceIsRight`

- `Boolean isSurvive`

- `EnemyDuelShieldState shieldState`


## Methods

- `Boolean get_isSelf()`

- `Void set_isSelf(Boolean)`

- `Boolean get_hasChosen()`

- `Boolean get_hasShield()`

- `Boolean get_justUsedShield()`

- `EnemyDuelChoiceSide get_curChoiceSide()`

- `EnemyDuelRoundResult get_curRoundResult()`

- `Boolean get_lastChoiceCorrect()`

- `Boolean get_lastChoiceIsRight()`

- `Boolean get_isSurvive()`

- `EnemyDuelShieldState get_shieldState()`

- `Void RefreshNpcChoice(Single, Single, Random)`

- `Void RefreshNpcChoiceType(ActivityEnemyDuelRoundData, Single, Random)`

- `Void ResetChoice()`

- `Void UpdateChoiceFromBetData(BetItem, Int32, ActivityEnemyDuelConstData)`

- `Void UpdateSettleScore(Int32, RoundLeaderBoard)`

- `Void UpdateSettleScore(Int32, EnemyDuelRoundResult)`

- `Void FastForwardNpcScore(Int32, Boolean, ActivityEnemyDuelConstData, ActivityEnemyDuelRoundData)`

- `Int32 CompareTo(EnemyDuelPlayerData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.EnemyDuel
public class EnemyDuelPlayerData : IHotfixable, IComparable`1
{
	public String playerId; // 0x10
	public String nickName; // 0x18
	public String playerAvatarId; // 0x20
	public PlayerAvatarType playerAvatarType; // 0x28
	public Int32 curScore; // 0x2c
	public Int32 betScore; // 0x30
	public Int32 rewardScore; // 0x34
	public Int32 scoreBeforeSettle; // 0x38
	public Int32 winStreak; // 0x3c
	public Int32 maxRound; // 0x40
	public EnemyDuelChoiceType curChoiceType; // 0x44
	public Boolean isNpc; // 0x48
	public Int64 updateTs; // 0x50
	private EnemyDuelRoundResult m_curRoundResult; // 0x58
	private EnemyDuelChoiceSide m_curChoiceSide; // 0x5c
	private Boolean m_lastChoiceCorrect; // 0x60
	private Boolean m_lastChoiceIsRight; // 0x61
	private Boolean m_choiceIsRight; // 0x62
	private Boolean m_hasChosen; // 0x63
	private Boolean m_isSurvive; // 0x64
	private EnemyDuelShieldState m_shieldState; // 0x68
	private Boolean <isSelf>k__BackingField; // 0x6c
	private static DelegateBridge __Hotfix0_get_isSelf; // 0x0
	private static DelegateBridge __Hotfix0_set_isSelf; // 0x8
	private static DelegateBridge __Hotfix0_get_hasChosen; // 0x10
	private static DelegateBridge __Hotfix0_get_hasShield; // 0x18
	private static DelegateBridge __Hotfix0_get_justUsedShield; // 0x20
	private static DelegateBridge __Hotfix0_get_curChoiceSide; // 0x28
	private static DelegateBridge __Hotfix0_get_curRoundResult; // 0x30
	private static DelegateBridge __Hotfix0_get_lastChoiceCorrect; // 0x38
	private static DelegateBridge __Hotfix0_get_lastChoiceIsRight; // 0x40
	private static DelegateBridge __Hotfix0_get_isSurvive; // 0x48
	private static DelegateBridge __Hotfix0_get_shieldState; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58
	private static DelegateBridge __Hotfix0_RefreshNpcChoice; // 0x60
	private static DelegateBridge __Hotfix0_RefreshNpcChoiceType; // 0x68
	private static DelegateBridge __Hotfix0_ResetChoice; // 0x70
	private static DelegateBridge __Hotfix0_UpdateChoiceFromBetData; // 0x78
	private static DelegateBridge __Hotfix0_UpdateSettleScore; // 0x80
	private static DelegateBridge __Hotfix1_UpdateSettleScore; // 0x88
	private static DelegateBridge __Hotfix0_FastForwardNpcScore; // 0x90
	private static DelegateBridge __Hotfix0_CompareTo; // 0x98

	public Boolean isSelf { get; set; }
	public Boolean hasChosen { get; }
	public Boolean hasShield { get; }
	public Boolean justUsedShield { get; }
	public EnemyDuelChoiceSide curChoiceSide { get; }
	public EnemyDuelRoundResult curRoundResult { get; }
	public Boolean lastChoiceCorrect { get; }
	public Boolean lastChoiceIsRight { get; }
	public Boolean isSurvive { get; }
	public EnemyDuelShieldState shieldState { get; }

	// RVA: 0x1c63490 VA: 0x759427b490
	public Boolean get_isSelf() { }
	// RVA: 0x1c634f8 VA: 0x759427b4f8
	public Void set_isSelf(Boolean value) { }
	// RVA: 0x1c63578 VA: 0x759427b578
	public Boolean get_hasChosen() { }
	// RVA: 0x1c635e0 VA: 0x759427b5e0
	public Boolean get_hasShield() { }
	// RVA: 0x1c63650 VA: 0x759427b650
	public Boolean get_justUsedShield() { }
	// RVA: 0x1c636c0 VA: 0x759427b6c0
	public EnemyDuelChoiceSide get_curChoiceSide() { }
	// RVA: 0x1c63728 VA: 0x759427b728
	public EnemyDuelRoundResult get_curRoundResult() { }
	// RVA: 0x1c63790 VA: 0x759427b790
	public Boolean get_lastChoiceCorrect() { }
	// RVA: 0x1c637f8 VA: 0x759427b7f8
	public Boolean get_lastChoiceIsRight() { }
	// RVA: 0x1c63860 VA: 0x759427b860
	public Boolean get_isSurvive() { }
	// RVA: 0x1c638c8 VA: 0x759427b8c8
	public EnemyDuelShieldState get_shieldState() { }
	// RVA: 0x1c63930 VA: 0x759427b930
	public Void .ctor(EnemyDuelModeType subModeType, Int32 initScore) { }
	// RVA: 0x1c639e8 VA: 0x759427b9e8
	public Void RefreshNpcChoice(Single scoreLeft, Single scoreRight, Random playerRandom) { }
	// RVA: 0x1c63b18 VA: 0x759427bb18
	public Void RefreshNpcChoiceType(ActivityEnemyDuelRoundData roundData, Single allinProb, Random playerRandom) { }
	// RVA: 0x1c63c18 VA: 0x759427bc18
	public Void ResetChoice() { }
	// RVA: 0x1c63c94 VA: 0x759427bc94
	public Void UpdateChoiceFromBetData(BetItem betData, Int32 basicBetScore, ActivityEnemyDuelConstData constData) { }
	// RVA: 0x1c63dbc VA: 0x759427bdbc
	public Void UpdateSettleScore(Int32 roundIndex, RoundLeaderBoard leaderBoard) { }
	// RVA: 0x1c63ed8 VA: 0x759427bed8
	public Void UpdateSettleScore(Int32 roundIndex, EnemyDuelRoundResult result) { }
	// RVA: 0x1c64028 VA: 0x759427c028
	public Void FastForwardNpcScore(Int32 roundIndex, Boolean isCorrect, ActivityEnemyDuelConstData constData, ActivityEnemyDuelRoundData roundData) { }
	// RVA: 0x1c6418c VA: 0x759427c18c
	public Int32 CompareTo(EnemyDuelPlayerData other) { }
}
```
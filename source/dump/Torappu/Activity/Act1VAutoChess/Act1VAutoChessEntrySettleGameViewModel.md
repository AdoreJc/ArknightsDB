# Act1VAutoChessEntrySettleGameViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int32 m_settleSeqNum`

- `Act1VAutoChessSettleGameResponse <cache>k__BackingField`

- `Boolean <fromBattle>k__BackingField`

- `Boolean <win>k__BackingField`

- `String <modeName>k__BackingField`

- `Int64 <battleStartTs>k__BackingField`

- `Int64 <battleSettleTs>k__BackingField`

- `Int32 <battleRound>k__BackingField`

- `String <bandLogoId>k__BackingField`

- `Int32 <restHealth>k__BackingField`

- `String <playerNickName>k__BackingField`

- `String <playerNickNumber>k__BackingField`

- `String <rewardItemId>k__BackingField`

- `Int32 <normalRewardCount>k__BackingField`

- `Int32 <extraRewardCount>k__BackingField`

- `CharWordData <charWord>k__BackingField`


## Properties

- `Act1VAutoChessSettleGameResponse cache`

- `Boolean fromBattle`

- `Boolean win`

- `String modeName`

- `Int64 battleStartTs`

- `Int64 battleSettleTs`

- `Int32 battleRound`

- `String bandLogoId`

- `Int32 restHealth`

- `String playerNickName`

- `String playerNickNumber`

- `String rewardItemId`

- `Int32 normalRewardCount`

- `Int32 extraRewardCount`

- `DailyRewardViewModel dailyReward`

- `LevelViewModel level`

- `CharWordData charWord`

- `Int32 settleSeqNum`


## Methods

- `Act1VAutoChessSettleGameResponse get_cache()`

- `Void set_cache(Act1VAutoChessSettleGameResponse)`

- `Boolean get_fromBattle()`

- `Void set_fromBattle(Boolean)`

- `Boolean get_win()`

- `Void set_win(Boolean)`

- `String get_modeName()`

- `Void set_modeName(String)`

- `Int64 get_battleStartTs()`

- `Void set_battleStartTs(Int64)`

- `Int64 get_battleSettleTs()`

- `Void set_battleSettleTs(Int64)`

- `Int32 get_battleRound()`

- `Void set_battleRound(Int32)`

- `String get_bandLogoId()`

- `Void set_bandLogoId(String)`

- `Int32 get_restHealth()`

- `Void set_restHealth(Int32)`

- `String get_playerNickName()`

- `Void set_playerNickName(String)`

- `String get_playerNickNumber()`

- `Void set_playerNickNumber(String)`

- `String get_rewardItemId()`

- `Void set_rewardItemId(String)`

- `Int32 get_normalRewardCount()`

- `Void set_normalRewardCount(Int32)`

- `Int32 get_extraRewardCount()`

- `Void set_extraRewardCount(Int32)`

- `DailyRewardViewModel get_dailyReward()`

- `LevelViewModel get_level()`

- `CharWordData get_charWord()`

- `Void set_charWord(CharWordData)`

- `Int32 get_settleSeqNum()`

- `Void _LoadModeName(ActivityAutoChessVerify1Data, String)`

- `Void _LoadBandInfo(ActivityAutoChessVerify1Data, OurSide)`

- `Void _LoadForceInfo(ActivityAutoChessVerify1Data, Dictionary`2)`

- `Void _LoadChars(ActivityAutoChessVerify1Data, PlayerAutoChessV1Activity, List`1)`

- `Void _LoadNormalOrGoldenDataIfNeed(Dictionary`2, Act1VAutoChessCharShopChessData, Act1VAutoChessCharChessData, out, out)`

- `String _LoadCharChessSkillId(String, Int32)`

- `Void _LoadEquips(ActivityAutoChessVerify1Data, List`1)`

- `Void _LoadRewardRelated(ActivityAutoChessVerify1Data, PlayerAutoChessV1Activity, RewardRelated)`

- `Void _LoadLevel(ActivityAutoChessVerify1Data, PlayerAutoChessV1Activity, RewardRelated, Int32)`

- `Void _LoadVoice()`

- `CharWordShowType _GetProperCharWordShowType()`

- `Void <>xLuaBaseProxy_LoadData(String, ActivityAutoChessVerify1Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntrySettleGameViewModel : Act1VAutoChessEntryBaseSubViewModel
{
	private Int32 m_settleSeqNum; // 0x24
	private readonly List`1 m_forces; // 0x28
	private readonly DailyRewardViewModel m_dailyReward; // 0x30
	private readonly LevelViewModel m_level; // 0x38
	private readonly List`1 m_chars; // 0x40
	private readonly List`1 m_equips; // 0x48
	private Act1VAutoChessSettleGameResponse <cache>k__BackingField; // 0x50
	private Boolean <fromBattle>k__BackingField; // 0x58
	private Boolean <win>k__BackingField; // 0x59
	private String <modeName>k__BackingField; // 0x60
	private Int64 <battleStartTs>k__BackingField; // 0x68
	private Int64 <battleSettleTs>k__BackingField; // 0x70
	private Int32 <battleRound>k__BackingField; // 0x78
	private String <bandLogoId>k__BackingField; // 0x80
	private Int32 <restHealth>k__BackingField; // 0x88
	private String <playerNickName>k__BackingField; // 0x90
	private String <playerNickNumber>k__BackingField; // 0x98
	private String <rewardItemId>k__BackingField; // 0xa0
	private Int32 <normalRewardCount>k__BackingField; // 0xa8
	private Int32 <extraRewardCount>k__BackingField; // 0xac
	private CharWordData <charWord>k__BackingField; // 0xb0
	private static DelegateBridge __Hotfix0_get_cache; // 0x0
	private static DelegateBridge __Hotfix0_set_cache; // 0x8
	private static DelegateBridge __Hotfix0_get_fromBattle; // 0x10
	private static DelegateBridge __Hotfix0_set_fromBattle; // 0x18
	private static DelegateBridge __Hotfix0_get_win; // 0x20
	private static DelegateBridge __Hotfix0_set_win; // 0x28
	private static DelegateBridge __Hotfix0_get_modeName; // 0x30
	private static DelegateBridge __Hotfix0_set_modeName; // 0x38
	private static DelegateBridge __Hotfix0_get_battleStartTs; // 0x40
	private static DelegateBridge __Hotfix0_set_battleStartTs; // 0x48
	private static DelegateBridge __Hotfix0_get_battleSettleTs; // 0x50
	private static DelegateBridge __Hotfix0_set_battleSettleTs; // 0x58
	private static DelegateBridge __Hotfix0_get_battleRound; // 0x60
	private static DelegateBridge __Hotfix0_set_battleRound; // 0x68
	private static DelegateBridge __Hotfix0_get_bandLogoId; // 0x70
	private static DelegateBridge __Hotfix0_set_bandLogoId; // 0x78
	private static DelegateBridge __Hotfix0_get_restHealth; // 0x80
	private static DelegateBridge __Hotfix0_set_restHealth; // 0x88
	private static DelegateBridge __Hotfix0_get_playerNickName; // 0x90
	private static DelegateBridge __Hotfix0_set_playerNickName; // 0x98
	private static DelegateBridge __Hotfix0_get_playerNickNumber; // 0xa0
	private static DelegateBridge __Hotfix0_set_playerNickNumber; // 0xa8
	private static DelegateBridge __Hotfix0_get_forces; // 0xb0
	private static DelegateBridge __Hotfix0_get_chars; // 0xb8
	private static DelegateBridge __Hotfix0_get_equips; // 0xc0
	private static DelegateBridge __Hotfix0_get_rewardItemId; // 0xc8
	private static DelegateBridge __Hotfix0_set_rewardItemId; // 0xd0
	private static DelegateBridge __Hotfix0_get_normalRewardCount; // 0xd8
	private static DelegateBridge __Hotfix0_set_normalRewardCount; // 0xe0
	private static DelegateBridge __Hotfix0_get_extraRewardCount; // 0xe8
	private static DelegateBridge __Hotfix0_set_extraRewardCount; // 0xf0
	private static DelegateBridge __Hotfix0_get_dailyReward; // 0xf8
	private static DelegateBridge __Hotfix0_get_level; // 0x100
	private static DelegateBridge __Hotfix0_get_charWord; // 0x108
	private static DelegateBridge __Hotfix0_set_charWord; // 0x110
	private static DelegateBridge __Hotfix0_get_settleSeqNum; // 0x118
	private static DelegateBridge __Hotfix0_LoadData; // 0x120
	private static DelegateBridge __Hotfix0__LoadModeName; // 0x128
	private static DelegateBridge __Hotfix0__LoadBandInfo; // 0x130
	private static DelegateBridge __Hotfix0__LoadForceInfo; // 0x138
	private static DelegateBridge __Hotfix0__LoadChars; // 0x140
	private static DelegateBridge __Hotfix0__LoadNormalOrGoldenDataIfNeed; // 0x148
	private static DelegateBridge __Hotfix0__LoadCharChessSkillId; // 0x150
	private static DelegateBridge __Hotfix0__LoadEquips; // 0x158
	private static DelegateBridge __Hotfix0__LoadRewardRelated; // 0x160
	private static DelegateBridge __Hotfix0__LoadLevel; // 0x168
	private static DelegateBridge __Hotfix0__LoadVoice; // 0x170
	private static DelegateBridge __Hotfix0__GetProperCharWordShowType; // 0x178
	private static DelegateBridge _c__Hotfix0_ctor; // 0x180

	private Act1VAutoChessSettleGameResponse cache { get; set; }
	public Boolean fromBattle { get; set; }
	public Boolean win { get; set; }
	public String modeName { get; set; }
	public Int64 battleStartTs { get; set; }
	public Int64 battleSettleTs { get; set; }
	public Int32 battleRound { get; set; }
	public String bandLogoId { get; set; }
	public Int32 restHealth { get; set; }
	public String playerNickName { get; set; }
	public String playerNickNumber { get; set; }
	public List`1 forces { get; }
	public List`1 chars { get; }
	public List`1 equips { get; }
	public String rewardItemId { get; set; }
	public Int32 normalRewardCount { get; set; }
	public Int32 extraRewardCount { get; set; }
	public DailyRewardViewModel dailyReward { get; }
	public LevelViewModel level { get; }
	public CharWordData charWord { get; set; }
	public Int32 settleSeqNum { get; }

	// RVA: 0x3353970 VA: 0x759596b970
	private Act1VAutoChessSettleGameResponse get_cache() { }
	// RVA: 0x33539d8 VA: 0x759596b9d8
	public Void set_cache(Act1VAutoChessSettleGameResponse value) { }
	// RVA: 0x3349374 VA: 0x7595961374
	public Boolean get_fromBattle() { }
	// RVA: 0x3353a5c VA: 0x759596ba5c
	public Void set_fromBattle(Boolean value) { }
	// RVA: 0x334930c VA: 0x759596130c
	public Boolean get_win() { }
	// RVA: 0x3353adc VA: 0x759596badc
	private Void set_win(Boolean value) { }
	// RVA: 0x3348f64 VA: 0x7595960f64
	public String get_modeName() { }
	// RVA: 0x3353b5c VA: 0x759596bb5c
	private Void set_modeName(String value) { }
	// RVA: 0x3348fcc VA: 0x7595960fcc
	public Int64 get_battleStartTs() { }
	// RVA: 0x3353be0 VA: 0x759596bbe0
	private Void set_battleStartTs(Int64 value) { }
	// RVA: 0x3349034 VA: 0x7595961034
	public Int64 get_battleSettleTs() { }
	// RVA: 0x3353c5c VA: 0x759596bc5c
	private Void set_battleSettleTs(Int64 value) { }
	// RVA: 0x334909c VA: 0x759596109c
	public Int32 get_battleRound() { }
	// RVA: 0x3353cd8 VA: 0x759596bcd8
	private Void set_battleRound(Int32 value) { }
	// RVA: 0x3349104 VA: 0x7595961104
	public String get_bandLogoId() { }
	// RVA: 0x3353d54 VA: 0x759596bd54
	private Void set_bandLogoId(String value) { }
	// RVA: 0x334916c VA: 0x759596116c
	public Int32 get_restHealth() { }
	// RVA: 0x3353dd8 VA: 0x759596bdd8
	private Void set_restHealth(Int32 value) { }
	// RVA: 0x33491d4 VA: 0x75959611d4
	public String get_playerNickName() { }
	// RVA: 0x3353e54 VA: 0x759596be54
	private Void set_playerNickName(String value) { }
	// RVA: 0x334923c VA: 0x759596123c
	public String get_playerNickNumber() { }
	// RVA: 0x3353ed8 VA: 0x759596bed8
	private Void set_playerNickNumber(String value) { }
	// RVA: 0x33492a4 VA: 0x75959612a4
	public List`1 get_forces() { }
	// RVA: 0x3349880 VA: 0x7595961880
	public List`1 get_chars() { }
	// RVA: 0x3349aa8 VA: 0x7595961aa8
	public List`1 get_equips() { }
	// RVA: 0x334a258 VA: 0x7595962258
	public String get_rewardItemId() { }
	// RVA: 0x3353f5c VA: 0x759596bf5c
	private Void set_rewardItemId(String value) { }
	// RVA: 0x334a2c0 VA: 0x75959622c0
	public Int32 get_normalRewardCount() { }
	// RVA: 0x3353fe0 VA: 0x759596bfe0
	private Void set_normalRewardCount(Int32 value) { }
	// RVA: 0x334a328 VA: 0x7595962328
	public Int32 get_extraRewardCount() { }
	// RVA: 0x335405c VA: 0x759596c05c
	private Void set_extraRewardCount(Int32 value) { }
	// RVA: 0x3349e58 VA: 0x7595961e58
	public DailyRewardViewModel get_dailyReward() { }
	// RVA: 0x3349ec0 VA: 0x7595961ec0
	public LevelViewModel get_level() { }
	// RVA: 0x334a940 VA: 0x7595962940
	public CharWordData get_charWord() { }
	// RVA: 0x33540d8 VA: 0x759596c0d8
	private Void set_charWord(CharWordData value) { }
	// RVA: 0x33496c4 VA: 0x75959616c4
	public Int32 get_settleSeqNum() { }
	// RVA: 0x335415c VA: 0x759596c15c
	public override Void LoadData(String actId, ActivityAutoChessVerify1Data actData) { }
	// RVA: 0x33543f8 VA: 0x759596c3f8
	private Void _LoadModeName(ActivityAutoChessVerify1Data actData, String modeId) { }
	// RVA: 0x3354564 VA: 0x759596c564
	private Void _LoadBandInfo(ActivityAutoChessVerify1Data actData, OurSide ourSide) { }
	// RVA: 0x335465c VA: 0x759596c65c
	private Void _LoadForceInfo(ActivityAutoChessVerify1Data actData, Dictionary`2 enemySide) { }
	// RVA: 0x33548e0 VA: 0x759596c8e0
	private Void _LoadChars(ActivityAutoChessVerify1Data actData, PlayerAutoChessV1Activity playerData, List`1 onStageChars) { }
	// RVA: 0x335537c VA: 0x759596d37c
	private Void _LoadNormalOrGoldenDataIfNeed(Dictionary`2 charDatabase, Act1VAutoChessCharShopChessData shopData, Act1VAutoChessCharChessData formerLookup, out Act1VAutoChessCharChessData normal, out Act1VAutoChessCharChessData golden) { }
	// RVA: 0x3355540 VA: 0x759596d540
	private String _LoadCharChessSkillId(String charId, Int32 skillIndex) { }
	// RVA: 0x3354ce4 VA: 0x759596cce4
	private Void _LoadEquips(ActivityAutoChessVerify1Data actData, List`1 onStageEquips) { }
	// RVA: 0x3354fd8 VA: 0x759596cfd8
	private Void _LoadRewardRelated(ActivityAutoChessVerify1Data actData, PlayerAutoChessV1Activity playerData, RewardRelated rewardRelated) { }
	// RVA: 0x3355718 VA: 0x759596d718
	private Void _LoadLevel(ActivityAutoChessVerify1Data actData, PlayerAutoChessV1Activity playerData, RewardRelated rewardRelated, Int32 rewardCount) { }
	// RVA: 0x33551d4 VA: 0x759596d1d4
	private Void _LoadVoice() { }
	// RVA: 0x3355d04 VA: 0x759596dd04
	private CharWordShowType _GetProperCharWordShowType() { }
	// RVA: 0x3355e10 VA: 0x759596de10
	public Void .ctor() { }
	// RVA: 0x33560b8 VA: 0x759596e0b8
	private Void <>xLuaBaseProxy_LoadData(String P0, ActivityAutoChessVerify1Data P1) { }
}
```
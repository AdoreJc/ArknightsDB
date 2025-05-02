# AutoChessHttpService

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Methods

- `Void _ChooseTalent(ValueBundle)`

- `Void _BuyRequest(ValueBundle)`

- `Void _SaleRequest(ValueBundle)`

- `Void _FreezeStoreRequest(ValueBundle)`

- `Void _RefreshStoreRequest(ValueBundle)`

- `Void _UpdateStoreRequest(ValueBundle)`

- `Void _WearEquipmentRequest(ValueBundle)`

- `Void _UseSpellRequest(ValueBundle)`

- `Void _RoundBattleStartRequest(ValueBundle)`

- `Void _RoundBattleFinishRequest(ValueBundle)`

- `Boolean _OnCommonRequestFailed(AutoChessServiceMsg, ResponseError)`

- `Void _HandlePlayerDataChanged()`

- `Void <_ChooseTalent>b__30_0(AutoChessInGameCommonResponse)`

- `Boolean <_ChooseTalent>b__30_1(ResponseError)`

- `Void <_BuyRequest>b__31_0(AutoChessInGameCommonResponse)`

- `Boolean <_BuyRequest>b__31_1(ResponseError)`

- `Void <_SaleRequest>b__32_0(AutoChessInGameCommonResponse)`

- `Boolean <_SaleRequest>b__32_1(ResponseError)`

- `Void <_FreezeStoreRequest>b__33_0(AutoChessInGameCommonResponse)`

- `Boolean <_FreezeStoreRequest>b__33_1(ResponseError)`

- `Void <_RefreshStoreRequest>b__34_0(AutoChessInGameCommonResponse)`

- `Boolean <_RefreshStoreRequest>b__34_1(ResponseError)`

- `Void <_UpdateStoreRequest>b__35_0(AutoChessInGameCommonResponse)`

- `Boolean <_UpdateStoreRequest>b__35_1(ResponseError)`

- `Void <_WearEquipmentRequest>b__36_0(AutoChessInGameCommonResponse)`

- `Boolean <_WearEquipmentRequest>b__36_1(ResponseError)`

- `Void <_UseSpellRequest>b__37_0(AutoChessInGameCommonResponse)`

- `Boolean <_UseSpellRequest>b__37_1(ResponseError)`

- `Void <_RoundBattleStartRequest>b__38_0(AutoChessInGameCommonResponse)`

- `Boolean <_RoundBattleStartRequest>b__38_1(ResponseError)`

- `Void <_RoundBattleFinishRequest>b__39_0(AutoChessRoundBattleFinishResponse)`

- `Boolean <_RoundBattleFinishRequest>b__39_1(ResponseError)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class AutoChessHttpService : AutoChessService, IHotfixable
{
	private const String CHOOSE_TALENT; // 0x0
	private const String BUY; // 0x0
	private const String SALE; // 0x0
	private const String FORZE_STORE; // 0x0
	private const String REFRESH_STORE; // 0x0
	private const String UPDATE_STORE; // 0x0
	private const String WEAR_EQUIPMENT; // 0x0
	private const String USE_SPELL; // 0x0
	private const String ROUND_BATTLE_START; // 0x0
	private const String ROUND_BATTLE_FINISH; // 0x0
	private const String PLAYER_DATA_UPDATE_LOACTION_FORMAT; // 0x0
	private static DelegateBridge __Hotfix0_get_networkType; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0_get_senderList; // 0x18
	private static DelegateBridge __Hotfix0__ChooseTalent; // 0x20
	private static DelegateBridge __Hotfix0__BuyRequest; // 0x28
	private static DelegateBridge __Hotfix0__SaleRequest; // 0x30
	private static DelegateBridge __Hotfix0__FreezeStoreRequest; // 0x38
	private static DelegateBridge __Hotfix0__RefreshStoreRequest; // 0x40
	private static DelegateBridge __Hotfix0__UpdateStoreRequest; // 0x48
	private static DelegateBridge __Hotfix0__WearEquipmentRequest; // 0x50
	private static DelegateBridge __Hotfix0__UseSpellRequest; // 0x58
	private static DelegateBridge __Hotfix0__RoundBattleStartRequest; // 0x60
	private static DelegateBridge __Hotfix0__RoundBattleFinishRequest; // 0x68
	private static DelegateBridge __Hotfix0__OnCommonRequestFailed; // 0x70
	private static DelegateBridge __Hotfix0__HandlePlayerDataChanged; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	protected override UnifiedServiceNetType networkType { get; }
	protected override KeyValuePair`2[] senderList { get; }

	// RVA: 0x33814e0 VA: 0x75959994e0
	protected override UnifiedServiceNetType get_networkType() { }
	// RVA: 0x3381548 VA: 0x7595999548
	protected override Void OnInit() { }
	// RVA: 0x3381704 VA: 0x7595999704
	protected override Void OnStart() { }
	// RVA: 0x33817a0 VA: 0x75959997a0
	protected override KeyValuePair`2[] get_senderList() { }
	// RVA: 0x3381ccc VA: 0x7595999ccc
	private Void _ChooseTalent(ValueBundle data) { }
	// RVA: 0x3381f58 VA: 0x7595999f58
	private Void _BuyRequest(ValueBundle data) { }
	// RVA: 0x3382248 VA: 0x759599a248
	private Void _SaleRequest(ValueBundle data) { }
	// RVA: 0x338251c VA: 0x759599a51c
	private Void _FreezeStoreRequest(ValueBundle data) { }
	// RVA: 0x33827ac VA: 0x759599a7ac
	private Void _RefreshStoreRequest(ValueBundle data) { }
	// RVA: 0x3382a28 VA: 0x759599aa28
	private Void _UpdateStoreRequest(ValueBundle data) { }
	// RVA: 0x3382ca4 VA: 0x759599aca4
	private Void _WearEquipmentRequest(ValueBundle data) { }
	// RVA: 0x3382f78 VA: 0x759599af78
	private Void _UseSpellRequest(ValueBundle data) { }
	// RVA: 0x3383278 VA: 0x759599b278
	private Void _RoundBattleStartRequest(ValueBundle data) { }
	// RVA: 0x3383574 VA: 0x759599b574
	private Void _RoundBattleFinishRequest(ValueBundle data) { }
	// RVA: 0x3383800 VA: 0x759599b800
	private Boolean _OnCommonRequestFailed(AutoChessServiceMsg serviceMsg, ResponseError respError) { }
	// RVA: 0x3383918 VA: 0x759599b918
	private Void _HandlePlayerDataChanged() { }
	// RVA: 0x3383a48 VA: 0x759599ba48
	public Void .ctor() { }
	// RVA: 0x3383afc VA: 0x759599bafc
	private Void <_ChooseTalent>b__30_0(AutoChessInGameCommonResponse response) { }
	// RVA: 0x3383c34 VA: 0x759599bc34
	private Boolean <_ChooseTalent>b__30_1(ResponseError error) { }
	// RVA: 0x3383c68 VA: 0x759599bc68
	private Void <_BuyRequest>b__31_0(AutoChessInGameCommonResponse response) { }
	// RVA: 0x3383d30 VA: 0x759599bd30
	private Boolean <_BuyRequest>b__31_1(ResponseError error) { }
	// RVA: 0x3383d64 VA: 0x759599bd64
	private Void <_SaleRequest>b__32_0(AutoChessInGameCommonResponse response) { }
	// RVA: 0x3383e2c VA: 0x759599be2c
	private Boolean <_SaleRequest>b__32_1(ResponseError error) { }
	// RVA: 0x3383e60 VA: 0x759599be60
	private Void <_FreezeStoreRequest>b__33_0(AutoChessInGameCommonResponse response) { }
	// RVA: 0x3383f28 VA: 0x759599bf28
	private Boolean <_FreezeStoreRequest>b__33_1(ResponseError error) { }
	// RVA: 0x3383f5c VA: 0x759599bf5c
	private Void <_RefreshStoreRequest>b__34_0(AutoChessInGameCommonResponse response) { }
	// RVA: 0x3384024 VA: 0x759599c024
	private Boolean <_RefreshStoreRequest>b__34_1(ResponseError error) { }
	// RVA: 0x3384058 VA: 0x759599c058
	private Void <_UpdateStoreRequest>b__35_0(AutoChessInGameCommonResponse response) { }
	// RVA: 0x3384120 VA: 0x759599c120
	private Boolean <_UpdateStoreRequest>b__35_1(ResponseError error) { }
	// RVA: 0x3384154 VA: 0x759599c154
	private Void <_WearEquipmentRequest>b__36_0(AutoChessInGameCommonResponse response) { }
	// RVA: 0x338421c VA: 0x759599c21c
	private Boolean <_WearEquipmentRequest>b__36_1(ResponseError error) { }
	// RVA: 0x3384250 VA: 0x759599c250
	private Void <_UseSpellRequest>b__37_0(AutoChessInGameCommonResponse response) { }
	// RVA: 0x3384318 VA: 0x759599c318
	private Boolean <_UseSpellRequest>b__37_1(ResponseError error) { }
	// RVA: 0x338434c VA: 0x759599c34c
	private Void <_RoundBattleStartRequest>b__38_0(AutoChessInGameCommonResponse response) { }
	// RVA: 0x3384414 VA: 0x759599c414
	private Boolean <_RoundBattleStartRequest>b__38_1(ResponseError error) { }
	// RVA: 0x3384448 VA: 0x759599c448
	private Void <_RoundBattleFinishRequest>b__39_0(AutoChessRoundBattleFinishResponse response) { }
	// RVA: 0x33845a8 VA: 0x759599c5a8
	private Boolean <_RoundBattleFinishRequest>b__39_1(ResponseError error) { }
}
```
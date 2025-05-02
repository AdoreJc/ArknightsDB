# RoguelikeShopStateBean

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeGoodsViewModel selectedGoods`

- `Bank topicBankPlayerData`

- `RoguelikeGameShopStatusProperty shopStatusProp`

- `RoguelikeGameShopDialogProp shopDialogProp`

- `RoguelikeGameShopGoodsProperty shopGoodsProp`

- `RoguelikeGameBankProperty bankProp`

- `String m_topicId`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `Void Init(String, RoguelikeCommonShopPlugin)`

- `Void LoadShopData()`

- `Void LoadBankData()`

- `Boolean CheckCanWithdraw()`

- `Boolean CheckWithdrawReachLimit(Int32)`

- `Void WithdrawIncrementCurrent()`

- `Void WithdrawDecrementCurrent()`

- `Void WithdrawMaxCurrent()`

- `Void WithdrawMinCurrent()`

- `Int32 GetWithdrawCount()`

- `Void _InjectShopPluginAndLoadData(RoguelikeGameShopViewModelPlugin)`

- `Void _InjectBankPluginAndLoadData(BankWithdrawModelPlugin)`

- `Void _LoadShopDialogData()`

- `ShopContent _GetGameShopPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopStateBean : IStateBean, IHotfixable
{
	public RoguelikeGoodsViewModel selectedGoods; // 0x10
	public Bank topicBankPlayerData; // 0x18
	public RoguelikeGameShopStatusProperty shopStatusProp; // 0x20
	public RoguelikeGameShopDialogProp shopDialogProp; // 0x28
	public RoguelikeGameShopGoodsProperty shopGoodsProp; // 0x30
	public RoguelikeGameBankProperty bankProp; // 0x38
	private String m_topicId; // 0x40
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_LoadShopData; // 0x10
	private static DelegateBridge __Hotfix0_LoadBankData; // 0x18
	private static DelegateBridge __Hotfix0_CheckCanWithdraw; // 0x20
	private static DelegateBridge __Hotfix0_CheckWithdrawReachLimit; // 0x28
	private static DelegateBridge __Hotfix0_WithdrawIncrementCurrent; // 0x30
	private static DelegateBridge __Hotfix0_WithdrawDecrementCurrent; // 0x38
	private static DelegateBridge __Hotfix0_WithdrawMaxCurrent; // 0x40
	private static DelegateBridge __Hotfix0_WithdrawMinCurrent; // 0x48
	private static DelegateBridge __Hotfix0_GetWithdrawCount; // 0x50
	private static DelegateBridge __Hotfix0__InjectShopPluginAndLoadData; // 0x58
	private static DelegateBridge __Hotfix0__InjectBankPluginAndLoadData; // 0x60
	private static DelegateBridge __Hotfix0__LoadShopDialogData; // 0x68
	private static DelegateBridge __Hotfix0__GetGameShopPlayerData; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public String topicId { get; }

	// RVA: 0x2aec844 VA: 0x7595104844
	public String get_topicId() { }
	// RVA: 0x2aec8ac VA: 0x75951048ac
	public Void Init(String topicId, RoguelikeCommonShopPlugin shopPlugin) { }
	// RVA: 0x2aecc70 VA: 0x7595104c70
	public Void LoadShopData() { }
	// RVA: 0x2aecef0 VA: 0x7595104ef0
	public Void LoadBankData() { }
	// RVA: 0x2aecfb8 VA: 0x7595104fb8
	public Boolean CheckCanWithdraw() { }
	// RVA: 0x2aed04c VA: 0x759510504c
	public Boolean CheckWithdrawReachLimit(Int32 hasWithdrawnCount) { }
	// RVA: 0x2aed100 VA: 0x7595105100
	public Void WithdrawIncrementCurrent() { }
	// RVA: 0x2aed194 VA: 0x7595105194
	public Void WithdrawDecrementCurrent() { }
	// RVA: 0x2aed228 VA: 0x7595105228
	public Void WithdrawMaxCurrent() { }
	// RVA: 0x2aed2bc VA: 0x75951052bc
	public Void WithdrawMinCurrent() { }
	// RVA: 0x2aed350 VA: 0x7595105350
	public Int32 GetWithdrawCount() { }
	// RVA: 0x2aeca0c VA: 0x7595104a0c
	private Void _InjectShopPluginAndLoadData(RoguelikeGameShopViewModelPlugin shopViewModelPlugin) { }
	// RVA: 0x2aecac0 VA: 0x7595104ac0
	private Void _InjectBankPluginAndLoadData(BankWithdrawModelPlugin bankWithdrawModelPlugin) { }
	// RVA: 0x2aecb74 VA: 0x7595104b74
	private Void _LoadShopDialogData() { }
	// RVA: 0x2aecd74 VA: 0x7595104d74
	private ShopContent _GetGameShopPlayerData() { }
	// RVA: 0x2aed3e8 VA: 0x75951053e8
	public Void .ctor() { }
}
```
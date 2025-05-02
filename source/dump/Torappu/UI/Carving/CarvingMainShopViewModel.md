# CarvingMainShopViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Int32 <round>k__BackingField`

- `Int32 <freeCardCnt>k__BackingField`

- `Int32 <freeNotifySeqNum>k__BackingField`

- `Int32 <refreshCoin>k__BackingField`

- `Int32 <refreshSeqNum>k__BackingField`

- `Int32 <coin>k__BackingField`

- `Boolean <canRefresh>k__BackingField`

- `Boolean <isNoGoods>k__BackingField`

- `CarvingMainShopGoodSlotItemModel <slotItemModel>k__BackingField`

- `CarvingInputMaterialModel <inputMaterialModel>k__BackingField`

- `Act35SideConstData <constData>k__BackingField`

- `String m_actId`

- `Act35SideData m_actData`


## Properties

- `Int32 round`

- `Int32 freeCardCnt`

- `Int32 freeNotifySeqNum`

- `Int32 refreshCoin`

- `Int32 refreshSeqNum`

- `Int32 coin`

- `Boolean canRefresh`

- `Boolean isNoGoods`

- `CarvingMainShopGoodSlotItemModel slotItemModel`

- `CarvingInputMaterialModel inputMaterialModel`

- `Act35SideConstData constData`


## Methods

- `Int32 get_round()`

- `Void set_round(Int32)`

- `Int32 get_freeCardCnt()`

- `Void set_freeCardCnt(Int32)`

- `Int32 get_freeNotifySeqNum()`

- `Void set_freeNotifySeqNum(Int32)`

- `Int32 get_refreshCoin()`

- `Void set_refreshCoin(Int32)`

- `Int32 get_refreshSeqNum()`

- `Void set_refreshSeqNum(Int32)`

- `Int32 get_coin()`

- `Void set_coin(Int32)`

- `Boolean get_canRefresh()`

- `Void set_canRefresh(Boolean)`

- `Boolean get_isNoGoods()`

- `Void set_isNoGoods(Boolean)`

- `Void set_cardGoodList(List`1)`

- `CarvingMainShopGoodSlotItemModel get_slotItemModel()`

- `Void set_slotItemModel(CarvingMainShopGoodSlotItemModel)`

- `CarvingInputMaterialModel get_inputMaterialModel()`

- `Void set_inputMaterialModel(CarvingInputMaterialModel)`

- `Act35SideConstData get_constData()`

- `Void set_constData(Act35SideConstData)`

- `Void LoadData(String, Act35SideData)`

- `Void UpdateData()`

- `Boolean CheckIsCanNextStep()`

- `Boolean GetIsSelectGood()`

- `Boolean CheckIsSelectSlotItem()`

- `Int32 GetSelectCardPos()`

- `CarvingMainCardViewModel GetSelectCardViewModel()`

- `Int32 GetSelectPrice()`

- `Boolean CheckIsCanBuySelect()`

- `Void SelectCard(Int32)`

- `Void SelectSlot()`

- `Void UnselectAll()`

- `Void NotifyFree()`

- `Void NotifyRefresh()`

- `Boolean _CheckHasSameCardInHand(ShopGood, Dictionary`2, out)`

- `Void _UnselectAllCard()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainShopViewModel : IHotfixable
{
	private const Int32 CAN_NOT_REFRESH_COIN; // 0x0
	private const Int32 CAN_NEXT_STEP_FREE_CARD_CNT; // 0x0
	private Int32 <round>k__BackingField; // 0x10
	private Int32 <freeCardCnt>k__BackingField; // 0x14
	private Int32 <freeNotifySeqNum>k__BackingField; // 0x18
	private Int32 <refreshCoin>k__BackingField; // 0x1c
	private Int32 <refreshSeqNum>k__BackingField; // 0x20
	private Int32 <coin>k__BackingField; // 0x24
	private Boolean <canRefresh>k__BackingField; // 0x28
	private Boolean <isNoGoods>k__BackingField; // 0x29
	private List`1 <cardGoodList>k__BackingField; // 0x30
	private CarvingMainShopGoodSlotItemModel <slotItemModel>k__BackingField; // 0x38
	private CarvingInputMaterialModel <inputMaterialModel>k__BackingField; // 0x40
	private Act35SideConstData <constData>k__BackingField; // 0x48
	private String m_actId; // 0x50
	private Act35SideData m_actData; // 0x58
	private static DelegateBridge __Hotfix0_get_round; // 0x0
	private static DelegateBridge __Hotfix0_set_round; // 0x8
	private static DelegateBridge __Hotfix0_get_freeCardCnt; // 0x10
	private static DelegateBridge __Hotfix0_set_freeCardCnt; // 0x18
	private static DelegateBridge __Hotfix0_get_freeNotifySeqNum; // 0x20
	private static DelegateBridge __Hotfix0_set_freeNotifySeqNum; // 0x28
	private static DelegateBridge __Hotfix0_get_refreshCoin; // 0x30
	private static DelegateBridge __Hotfix0_set_refreshCoin; // 0x38
	private static DelegateBridge __Hotfix0_get_refreshSeqNum; // 0x40
	private static DelegateBridge __Hotfix0_set_refreshSeqNum; // 0x48
	private static DelegateBridge __Hotfix0_get_coin; // 0x50
	private static DelegateBridge __Hotfix0_set_coin; // 0x58
	private static DelegateBridge __Hotfix0_get_canRefresh; // 0x60
	private static DelegateBridge __Hotfix0_set_canRefresh; // 0x68
	private static DelegateBridge __Hotfix0_get_isNoGoods; // 0x70
	private static DelegateBridge __Hotfix0_set_isNoGoods; // 0x78
	private static DelegateBridge __Hotfix0_get_cardGoodList; // 0x80
	private static DelegateBridge __Hotfix0_set_cardGoodList; // 0x88
	private static DelegateBridge __Hotfix0_get_slotItemModel; // 0x90
	private static DelegateBridge __Hotfix0_set_slotItemModel; // 0x98
	private static DelegateBridge __Hotfix0_get_inputMaterialModel; // 0xa0
	private static DelegateBridge __Hotfix0_set_inputMaterialModel; // 0xa8
	private static DelegateBridge __Hotfix0_get_constData; // 0xb0
	private static DelegateBridge __Hotfix0_set_constData; // 0xb8
	private static DelegateBridge __Hotfix0_LoadData; // 0xc0
	private static DelegateBridge __Hotfix0_UpdateData; // 0xc8
	private static DelegateBridge __Hotfix0_CheckIsCanNextStep; // 0xd0
	private static DelegateBridge __Hotfix0_GetIsSelectGood; // 0xd8
	private static DelegateBridge __Hotfix0_CheckIsSelectSlotItem; // 0xe0
	private static DelegateBridge __Hotfix0_GetSelectCardPos; // 0xe8
	private static DelegateBridge __Hotfix0_GetSelectCardViewModel; // 0xf0
	private static DelegateBridge __Hotfix0_GetSelectPrice; // 0xf8
	private static DelegateBridge __Hotfix0_CheckIsCanBuySelect; // 0x100
	private static DelegateBridge __Hotfix0_SelectCard; // 0x108
	private static DelegateBridge __Hotfix0_SelectSlot; // 0x110
	private static DelegateBridge __Hotfix0_UnselectAll; // 0x118
	private static DelegateBridge __Hotfix0_NotifyFree; // 0x120
	private static DelegateBridge __Hotfix0_NotifyRefresh; // 0x128
	private static DelegateBridge __Hotfix0__CheckHasSameCardInHand; // 0x130
	private static DelegateBridge __Hotfix0__UnselectAllCard; // 0x138
	private static DelegateBridge _c__Hotfix0_ctor; // 0x140

	public Int32 round { get; set; }
	public Int32 freeCardCnt { get; set; }
	public Int32 freeNotifySeqNum { get; set; }
	public Int32 refreshCoin { get; set; }
	public Int32 refreshSeqNum { get; set; }
	public Int32 coin { get; set; }
	public Boolean canRefresh { get; set; }
	public Boolean isNoGoods { get; set; }
	public List`1 cardGoodList { get; set; }
	public CarvingMainShopGoodSlotItemModel slotItemModel { get; set; }
	public CarvingInputMaterialModel inputMaterialModel { get; set; }
	public Act35SideConstData constData { get; set; }

	// RVA: 0x2dba9c4 VA: 0x75953d29c4
	public Int32 get_round() { }
	// RVA: 0x2dbbbf4 VA: 0x75953d3bf4
	private Void set_round(Int32 value) { }
	// RVA: 0x2dba7fc VA: 0x75953d27fc
	public Int32 get_freeCardCnt() { }
	// RVA: 0x2dbbc70 VA: 0x75953d3c70
	private Void set_freeCardCnt(Int32 value) { }
	// RVA: 0x2dba864 VA: 0x75953d2864
	public Int32 get_freeNotifySeqNum() { }
	// RVA: 0x2dbbcec VA: 0x75953d3cec
	private Void set_freeNotifySeqNum(Int32 value) { }
	// RVA: 0x2dbaa94 VA: 0x75953d2a94
	public Int32 get_refreshCoin() { }
	// RVA: 0x2dbbd68 VA: 0x75953d3d68
	private Void set_refreshCoin(Int32 value) { }
	// RVA: 0x2db9ebc VA: 0x75953d1ebc
	public Int32 get_refreshSeqNum() { }
	// RVA: 0x2dbbde4 VA: 0x75953d3de4
	private Void set_refreshSeqNum(Int32 value) { }
	// RVA: 0x2dbaafc VA: 0x75953d2afc
	public Int32 get_coin() { }
	// RVA: 0x2dbbe60 VA: 0x75953d3e60
	private Void set_coin(Int32 value) { }
	// RVA: 0x2dbaa2c VA: 0x75953d2a2c
	public Boolean get_canRefresh() { }
	// RVA: 0x2dbbedc VA: 0x75953d3edc
	private Void set_canRefresh(Boolean value) { }
	// RVA: 0x2dbab64 VA: 0x75953d2b64
	public Boolean get_isNoGoods() { }
	// RVA: 0x2dbbf5c VA: 0x75953d3f5c
	private Void set_isNoGoods(Boolean value) { }
	// RVA: 0x2dbabcc VA: 0x75953d2bcc
	public List`1 get_cardGoodList() { }
	// RVA: 0x2dbbfdc VA: 0x75953d3fdc
	private Void set_cardGoodList(List`1 value) { }
	// RVA: 0x2dbac9c VA: 0x75953d2c9c
	public CarvingMainShopGoodSlotItemModel get_slotItemModel() { }
	// RVA: 0x2dbc060 VA: 0x75953d4060
	private Void set_slotItemModel(CarvingMainShopGoodSlotItemModel value) { }
	// RVA: 0x2dbb024 VA: 0x75953d3024
	public CarvingInputMaterialModel get_inputMaterialModel() { }
	// RVA: 0x2dbc0e4 VA: 0x75953d40e4
	private Void set_inputMaterialModel(CarvingInputMaterialModel value) { }
	// RVA: 0x2dbc168 VA: 0x75953d4168
	public Act35SideConstData get_constData() { }
	// RVA: 0x2dbc1d0 VA: 0x75953d41d0
	private Void set_constData(Act35SideConstData value) { }
	// RVA: 0x2dbc254 VA: 0x75953d4254
	public Void LoadData(String actId, Act35SideData actData) { }
	// RVA: 0x2dbc318 VA: 0x75953d4318
	public Void UpdateData() { }
	// RVA: 0x2dbafb0 VA: 0x75953d2fb0
	public Boolean CheckIsCanNextStep() { }
	// RVA: 0x2dbaea4 VA: 0x75953d2ea4
	public Boolean GetIsSelectGood() { }
	// RVA: 0x2dbd428 VA: 0x75953d5428
	public Boolean CheckIsSelectSlotItem() { }
	// RVA: 0x2dbd49c VA: 0x75953d549c
	public Int32 GetSelectCardPos() { }
	// RVA: 0x2dbd590 VA: 0x75953d5590
	public CarvingMainCardViewModel GetSelectCardViewModel() { }
	// RVA: 0x2dbad6c VA: 0x75953d2d6c
	public Int32 GetSelectPrice() { }
	// RVA: 0x2dbd6a8 VA: 0x75953d56a8
	public Boolean CheckIsCanBuySelect() { }
	// RVA: 0x2dbd728 VA: 0x75953d5728
	public Void SelectCard(Int32 pos) { }
	// RVA: 0x2dbd9b0 VA: 0x75953d59b0
	public Void SelectSlot() { }
	// RVA: 0x2dbdb70 VA: 0x75953d5b70
	public Void UnselectAll() { }
	// RVA: 0x2dbdc08 VA: 0x75953d5c08
	public Void NotifyFree() { }
	// RVA: 0x2dbdc7c VA: 0x75953d5c7c
	public Void NotifyRefresh() { }
	// RVA: 0x2dbcef0 VA: 0x75953d4ef0
	private Boolean _CheckHasSameCardInHand(ShopGood good, Dictionary`2 handCard, out Int32 handCardLevel) { }
	// RVA: 0x2dbda84 VA: 0x75953d5a84
	private Void _UnselectAllCard() { }
	// RVA: 0x2dbdcf0 VA: 0x75953d5cf0
	public Void .ctor() { }
}
```
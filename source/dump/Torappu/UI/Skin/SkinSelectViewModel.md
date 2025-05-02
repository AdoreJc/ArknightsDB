# SkinSelectViewModel

**Namespace:** `Torappu.UI.Skin`


## Fields

- `Int32 index`

- `SkinState state`

- `CharSkinData skinData`

- `Int32 price`

- `SkinShopViewModel <skinShopData>k__BackingField`

- `Boolean <cacheSeFlag>k__BackingField`

- `Boolean <useVoucher>k__BackingField`

- `Boolean <usePriceToBuy>k__BackingField`

- `Boolean <hasCurSkin>k__BackingField`

- `Boolean <isRedeem>k__BackingField`

- `Boolean <hasCurSkinAndChar>k__BackingField`

- `Boolean <showPricePart>k__BackingField`

- `String <giftAvatarId>k__BackingField`

- `String <giftDesc>k__BackingField`

- `Boolean <showGiftPart>k__BackingField`

- `Boolean <showDynIllust>k__BackingField`


## Properties

- `String portraitId`

- `SkinShopViewModel skinShopData`

- `Boolean cacheSeFlag`

- `Boolean useVoucher`

- `Boolean usePriceToBuy`

- `Boolean hasCurSkin`

- `Boolean isRedeem`

- `Boolean hasCurSkinAndChar`

- `Boolean showPricePart`

- `String giftAvatarId`

- `String giftDesc`

- `Boolean showGiftPart`

- `Boolean showDynIllust`

- `ShopSkinItemViewModel skinShopModel`

- `Int32 groupSortId`

- `Int32 sortId`


## Methods

- `String get_portraitId()`

- `SkinShopViewModel get_skinShopData()`

- `Void set_skinShopData(SkinShopViewModel)`

- `Boolean get_cacheSeFlag()`

- `Void set_cacheSeFlag(Boolean)`

- `Boolean get_useVoucher()`

- `Void set_useVoucher(Boolean)`

- `Boolean get_usePriceToBuy()`

- `Void set_usePriceToBuy(Boolean)`

- `Boolean get_hasCurSkin()`

- `Void set_hasCurSkin(Boolean)`

- `Boolean get_isRedeem()`

- `Void set_isRedeem(Boolean)`

- `Boolean get_hasCurSkinAndChar()`

- `Void set_hasCurSkinAndChar(Boolean)`

- `Boolean get_showPricePart()`

- `Void set_showPricePart(Boolean)`

- `String get_giftAvatarId()`

- `Void set_giftAvatarId(String)`

- `String get_giftDesc()`

- `Void set_giftDesc(String)`

- `Boolean get_showGiftPart()`

- `Void set_showGiftPart(Boolean)`

- `Boolean get_showDynIllust()`

- `Void set_showDynIllust(Boolean)`

- `ShopSkinItemViewModel get_skinShopModel()`

- `Int32 get_groupSortId()`

- `Int32 get_sortId()`

- `Boolean CheckIfHasSkin(String)`

- `Boolean _CheckSelectFlag(CharSkinData, Boolean)`

- `Sprite LoadAvatarImage()`

- `Void RefreshData()`

- `Void InitData(Int32, CharSkinData, Boolean, Boolean)`

- `Void InitData(Int32, SkinShopViewModel, Boolean, Boolean)`

- `Void _UpdateData()`

- `SkinState _AnalyseCurSkinState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinSelectViewModel : IHotfixable
{
	public Int32 index; // 0x10
	public SkinState state; // 0x14
	public CharSkinData skinData; // 0x18
	public Int32 price; // 0x20
	private SkinShopViewModel <skinShopData>k__BackingField; // 0x28
	private Boolean <cacheSeFlag>k__BackingField; // 0x30
	private Boolean <useVoucher>k__BackingField; // 0x31
	private Boolean <usePriceToBuy>k__BackingField; // 0x32
	private Boolean <hasCurSkin>k__BackingField; // 0x33
	private Boolean <isRedeem>k__BackingField; // 0x34
	private Boolean <hasCurSkinAndChar>k__BackingField; // 0x35
	private Boolean <showPricePart>k__BackingField; // 0x36
	private String <giftAvatarId>k__BackingField; // 0x38
	private String <giftDesc>k__BackingField; // 0x40
	private Boolean <showGiftPart>k__BackingField; // 0x48
	private Boolean <showDynIllust>k__BackingField; // 0x49
	private static DelegateBridge __Hotfix0_get_portraitId; // 0x0
	private static DelegateBridge __Hotfix0_get_skinShopData; // 0x8
	private static DelegateBridge __Hotfix0_set_skinShopData; // 0x10
	private static DelegateBridge __Hotfix0_get_cacheSeFlag; // 0x18
	private static DelegateBridge __Hotfix0_set_cacheSeFlag; // 0x20
	private static DelegateBridge __Hotfix0_get_useVoucher; // 0x28
	private static DelegateBridge __Hotfix0_set_useVoucher; // 0x30
	private static DelegateBridge __Hotfix0_get_usePriceToBuy; // 0x38
	private static DelegateBridge __Hotfix0_set_usePriceToBuy; // 0x40
	private static DelegateBridge __Hotfix0_get_hasCurSkin; // 0x48
	private static DelegateBridge __Hotfix0_set_hasCurSkin; // 0x50
	private static DelegateBridge __Hotfix0_get_isRedeem; // 0x58
	private static DelegateBridge __Hotfix0_set_isRedeem; // 0x60
	private static DelegateBridge __Hotfix0_get_hasCurSkinAndChar; // 0x68
	private static DelegateBridge __Hotfix0_set_hasCurSkinAndChar; // 0x70
	private static DelegateBridge __Hotfix0_get_showPricePart; // 0x78
	private static DelegateBridge __Hotfix0_set_showPricePart; // 0x80
	private static DelegateBridge __Hotfix0_get_giftAvatarId; // 0x88
	private static DelegateBridge __Hotfix0_set_giftAvatarId; // 0x90
	private static DelegateBridge __Hotfix0_get_giftDesc; // 0x98
	private static DelegateBridge __Hotfix0_set_giftDesc; // 0xa0
	private static DelegateBridge __Hotfix0_get_showGiftPart; // 0xa8
	private static DelegateBridge __Hotfix0_set_showGiftPart; // 0xb0
	private static DelegateBridge __Hotfix0_get_showDynIllust; // 0xb8
	private static DelegateBridge __Hotfix0_set_showDynIllust; // 0xc0
	private static DelegateBridge __Hotfix0_get_skinShopModel; // 0xc8
	private static DelegateBridge __Hotfix0_get_groupSortId; // 0xd0
	private static DelegateBridge __Hotfix0_get_sortId; // 0xd8
	private static DelegateBridge __Hotfix0_CheckSkinAvailableState; // 0xe0
	private static DelegateBridge __Hotfix0_CheckSkinTmplMatch; // 0xe8
	private static DelegateBridge __Hotfix0_CheckSkinTmplAvail; // 0xf0
	private static DelegateBridge __Hotfix0_GetSkinTmplSortId; // 0xf8
	private static DelegateBridge __Hotfix0_CheckIfHasSkin; // 0x100
	private static DelegateBridge __Hotfix0__CheckSelectFlag; // 0x108
	private static DelegateBridge __Hotfix0_LoadAvatarImage; // 0x110
	private static DelegateBridge __Hotfix0_RefreshData; // 0x118
	private static DelegateBridge __Hotfix0_InitData; // 0x120
	private static DelegateBridge __Hotfix1_InitData; // 0x128
	private static DelegateBridge __Hotfix0__UpdateData; // 0x130
	private static DelegateBridge __Hotfix0__AnalyseCurSkinState; // 0x138
	private static DelegateBridge _c__Hotfix0_ctor; // 0x140

	public String portraitId { get; }
	public SkinShopViewModel skinShopData { get; set; }
	public Boolean cacheSeFlag { get; set; }
	public Boolean useVoucher { get; set; }
	public Boolean usePriceToBuy { get; set; }
	public Boolean hasCurSkin { get; set; }
	public Boolean isRedeem { get; set; }
	public Boolean hasCurSkinAndChar { get; set; }
	public Boolean showPricePart { get; set; }
	public String giftAvatarId { get; set; }
	public String giftDesc { get; set; }
	public Boolean showGiftPart { get; set; }
	public Boolean showDynIllust { get; set; }
	public ShopSkinItemViewModel skinShopModel { get; }
	public Int32 groupSortId { get; }
	public Int32 sortId { get; }

	// RVA: 0x23d6598 VA: 0x75949ee598
	public String get_portraitId() { }
	// RVA: 0x23d9f54 VA: 0x75949f1f54
	public SkinShopViewModel get_skinShopData() { }
	// RVA: 0x23d9fbc VA: 0x75949f1fbc
	private Void set_skinShopData(SkinShopViewModel value) { }
	// RVA: 0x23da040 VA: 0x75949f2040
	public Boolean get_cacheSeFlag() { }
	// RVA: 0x23da0a8 VA: 0x75949f20a8
	private Void set_cacheSeFlag(Boolean value) { }
	// RVA: 0x23da128 VA: 0x75949f2128
	public Boolean get_useVoucher() { }
	// RVA: 0x23da190 VA: 0x75949f2190
	private Void set_useVoucher(Boolean value) { }
	// RVA: 0x23da210 VA: 0x75949f2210
	public Boolean get_usePriceToBuy() { }
	// RVA: 0x23da278 VA: 0x75949f2278
	private Void set_usePriceToBuy(Boolean value) { }
	// RVA: 0x23da2f8 VA: 0x75949f22f8
	public Boolean get_hasCurSkin() { }
	// RVA: 0x23da360 VA: 0x75949f2360
	private Void set_hasCurSkin(Boolean value) { }
	// RVA: 0x23da3e0 VA: 0x75949f23e0
	public Boolean get_isRedeem() { }
	// RVA: 0x23da448 VA: 0x75949f2448
	private Void set_isRedeem(Boolean value) { }
	// RVA: 0x23da4c8 VA: 0x75949f24c8
	public Boolean get_hasCurSkinAndChar() { }
	// RVA: 0x23da530 VA: 0x75949f2530
	private Void set_hasCurSkinAndChar(Boolean value) { }
	// RVA: 0x23d6610 VA: 0x75949ee610
	public Boolean get_showPricePart() { }
	// RVA: 0x23da5b0 VA: 0x75949f25b0
	private Void set_showPricePart(Boolean value) { }
	// RVA: 0x23d5088 VA: 0x75949ed088
	public String get_giftAvatarId() { }
	// RVA: 0x23da630 VA: 0x75949f2630
	private Void set_giftAvatarId(String value) { }
	// RVA: 0x23da6b4 VA: 0x75949f26b4
	public String get_giftDesc() { }
	// RVA: 0x23da71c VA: 0x75949f271c
	private Void set_giftDesc(String value) { }
	// RVA: 0x23d5020 VA: 0x75949ed020
	public Boolean get_showGiftPart() { }
	// RVA: 0x23da7a0 VA: 0x75949f27a0
	private Void set_showGiftPart(Boolean value) { }
	// RVA: 0x23d4654 VA: 0x75949ec654
	public Boolean get_showDynIllust() { }
	// RVA: 0x23da820 VA: 0x75949f2820
	private Void set_showDynIllust(Boolean value) { }
	// RVA: 0x23d6678 VA: 0x75949ee678
	public ShopSkinItemViewModel get_skinShopModel() { }
	// RVA: 0x23da8a0 VA: 0x75949f28a0
	public Int32 get_groupSortId() { }
	// RVA: 0x23da91c VA: 0x75949f291c
	public Int32 get_sortId() { }
	// RVA: 0x23da998 VA: 0x75949f2998
	public static Boolean CheckSkinAvailableState(CharSkinData skinData) { }
	// RVA: 0x23daa78 VA: 0x75949f2a78
	public static Boolean CheckSkinTmplMatch(CharSkinData skinData) { }
	// RVA: 0x23dabcc VA: 0x75949f2bcc
	public static Boolean CheckSkinTmplAvail(CharSkinData skinData) { }
	// RVA: 0x23dacac VA: 0x75949f2cac
	public static Int32 GetSkinTmplSortId(CharSkinData skinData) { }
	// RVA: 0x23dad94 VA: 0x75949f2d94
	public Boolean CheckIfHasSkin(String skinId) { }
	// RVA: 0x23dae88 VA: 0x75949f2e88
	private Boolean _CheckSelectFlag(CharSkinData skinData, Boolean secretaryFlag) { }
	// RVA: 0x23daff8 VA: 0x75949f2ff8
	public Sprite LoadAvatarImage() { }
	// RVA: 0x23d9e20 VA: 0x75949f1e20
	public Void RefreshData() { }
	// RVA: 0x23db1e4 VA: 0x75949f31e4
	public Void InitData(Int32 index, CharSkinData importData, Boolean secretaryFlag, Boolean useVoucher) { }
	// RVA: 0x23db2d0 VA: 0x75949f32d0
	public Void InitData(Int32 index, SkinShopViewModel shopData, Boolean secretaryFlag, Boolean useVoucher) { }
	// RVA: 0x23db0a4 VA: 0x75949f30a4
	private Void _UpdateData() { }
	// RVA: 0x23db3f8 VA: 0x75949f33f8
	private SkinState _AnalyseCurSkinState() { }
	// RVA: 0x23db590 VA: 0x75949f3590
	public Void .ctor() { }
}
```
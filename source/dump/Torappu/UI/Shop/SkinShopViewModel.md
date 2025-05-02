# SkinShopViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Boolean isAchieved`

- `String skinId`

- `ShopSkinItemViewModel shopViewModel`

- `CharSkinData skinData`

- `CharUISkinStruct skinStruct`

- `String skinGroup`

- `Boolean useVoucher`

- `Boolean isRedeem`

- `String giftAvatarId`

- `String giftAvatarName`

- `String giftDesc`

- `Boolean <showVoucherPart>k__BackingField`

- `Boolean <showSoldOutPart>k__BackingField`

- `Boolean <showDiamondPart>k__BackingField`

- `Boolean <showDiamondDiscount>k__BackingField`

- `Boolean <showCashPart>k__BackingField`

- `Boolean <showCashDiscount>k__BackingField`

- `Boolean <showTimeLimitPart>k__BackingField`

- `Boolean <showDiscountPart>k__BackingField`

- `GiftShowType <giftShowType>k__BackingField`


## Properties

- `Boolean showVoucherPart`

- `Boolean showSoldOutPart`

- `Boolean showDiamondPart`

- `Boolean showDiamondDiscount`

- `Boolean showCashPart`

- `Boolean showCashDiscount`

- `Boolean showTimeLimitPart`

- `Boolean showDiscountPart`

- `GiftShowType giftShowType`


## Methods

- `Boolean CheckIfShowDynPortrait(Config)`

- `Boolean get_showVoucherPart()`

- `Void set_showVoucherPart(Boolean)`

- `Boolean get_showSoldOutPart()`

- `Void set_showSoldOutPart(Boolean)`

- `Boolean get_showDiamondPart()`

- `Void set_showDiamondPart(Boolean)`

- `Boolean get_showDiamondDiscount()`

- `Void set_showDiamondDiscount(Boolean)`

- `Boolean get_showCashPart()`

- `Void set_showCashPart(Boolean)`

- `Boolean get_showCashDiscount()`

- `Void set_showCashDiscount(Boolean)`

- `Boolean get_showTimeLimitPart()`

- `Void set_showTimeLimitPart(Boolean)`

- `Boolean get_showDiscountPart()`

- `Void set_showDiscountPart(Boolean)`

- `GiftShowType get_giftShowType()`

- `Void set_giftShowType(GiftShowType)`

- `Boolean InitData(ShopSkinItemViewModel, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SkinShopViewModel : IHotfixable
{
	public Boolean isAchieved; // 0x10
	public String skinId; // 0x18
	public ShopSkinItemViewModel shopViewModel; // 0x20
	public CharSkinData skinData; // 0x28
	public CharUISkinStruct skinStruct; // 0x30
	public String skinGroup; // 0x40
	public Boolean useVoucher; // 0x48
	public Boolean isRedeem; // 0x49
	public String giftAvatarId; // 0x50
	public String giftAvatarName; // 0x58
	public String giftDesc; // 0x60
	private Boolean <showVoucherPart>k__BackingField; // 0x68
	private Boolean <showSoldOutPart>k__BackingField; // 0x69
	private Boolean <showDiamondPart>k__BackingField; // 0x6a
	private Boolean <showDiamondDiscount>k__BackingField; // 0x6b
	private Boolean <showCashPart>k__BackingField; // 0x6c
	private Boolean <showCashDiscount>k__BackingField; // 0x6d
	private Boolean <showTimeLimitPart>k__BackingField; // 0x6e
	private Boolean <showDiscountPart>k__BackingField; // 0x6f
	private GiftShowType <giftShowType>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_CheckIfShowDynPortrait; // 0x0
	private static DelegateBridge __Hotfix0_get_showVoucherPart; // 0x8
	private static DelegateBridge __Hotfix0_set_showVoucherPart; // 0x10
	private static DelegateBridge __Hotfix0_get_showSoldOutPart; // 0x18
	private static DelegateBridge __Hotfix0_set_showSoldOutPart; // 0x20
	private static DelegateBridge __Hotfix0_get_showDiamondPart; // 0x28
	private static DelegateBridge __Hotfix0_set_showDiamondPart; // 0x30
	private static DelegateBridge __Hotfix0_get_showDiamondDiscount; // 0x38
	private static DelegateBridge __Hotfix0_set_showDiamondDiscount; // 0x40
	private static DelegateBridge __Hotfix0_get_showCashPart; // 0x48
	private static DelegateBridge __Hotfix0_set_showCashPart; // 0x50
	private static DelegateBridge __Hotfix0_get_showCashDiscount; // 0x58
	private static DelegateBridge __Hotfix0_set_showCashDiscount; // 0x60
	private static DelegateBridge __Hotfix0_get_showTimeLimitPart; // 0x68
	private static DelegateBridge __Hotfix0_set_showTimeLimitPart; // 0x70
	private static DelegateBridge __Hotfix0_get_showDiscountPart; // 0x78
	private static DelegateBridge __Hotfix0_set_showDiscountPart; // 0x80
	private static DelegateBridge __Hotfix0_get_giftShowType; // 0x88
	private static DelegateBridge __Hotfix0_set_giftShowType; // 0x90
	private static DelegateBridge __Hotfix0_InitData; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public Boolean showVoucherPart { get; set; }
	public Boolean showSoldOutPart { get; set; }
	public Boolean showDiamondPart { get; set; }
	public Boolean showDiamondDiscount { get; set; }
	public Boolean showCashPart { get; set; }
	public Boolean showCashDiscount { get; set; }
	public Boolean showTimeLimitPart { get; set; }
	public Boolean showDiscountPart { get; set; }
	public GiftShowType giftShowType { get; set; }

	// RVA: 0x246bf40 VA: 0x7594a83f40
	public Boolean CheckIfShowDynPortrait(Config illustConfig) { }
	// RVA: 0x246bb98 VA: 0x7594a83b98
	public Boolean get_showVoucherPart() { }
	// RVA: 0x246cbd0 VA: 0x7594a84bd0
	private Void set_showVoucherPart(Boolean value) { }
	// RVA: 0x246bc00 VA: 0x7594a83c00
	public Boolean get_showSoldOutPart() { }
	// RVA: 0x246cc50 VA: 0x7594a84c50
	private Void set_showSoldOutPart(Boolean value) { }
	// RVA: 0x246bc68 VA: 0x7594a83c68
	public Boolean get_showDiamondPart() { }
	// RVA: 0x246ccd0 VA: 0x7594a84cd0
	private Void set_showDiamondPart(Boolean value) { }
	// RVA: 0x246bda0 VA: 0x7594a83da0
	public Boolean get_showDiamondDiscount() { }
	// RVA: 0x246cd50 VA: 0x7594a84d50
	private Void set_showDiamondDiscount(Boolean value) { }
	// RVA: 0x246bcd0 VA: 0x7594a83cd0
	public Boolean get_showCashPart() { }
	// RVA: 0x246cdd0 VA: 0x7594a84dd0
	private Void set_showCashPart(Boolean value) { }
	// RVA: 0x246be08 VA: 0x7594a83e08
	public Boolean get_showCashDiscount() { }
	// RVA: 0x246ce50 VA: 0x7594a84e50
	private Void set_showCashDiscount(Boolean value) { }
	// RVA: 0x246be70 VA: 0x7594a83e70
	public Boolean get_showTimeLimitPart() { }
	// RVA: 0x246ced0 VA: 0x7594a84ed0
	private Void set_showTimeLimitPart(Boolean value) { }
	// RVA: 0x246bd38 VA: 0x7594a83d38
	public Boolean get_showDiscountPart() { }
	// RVA: 0x246cf50 VA: 0x7594a84f50
	private Void set_showDiscountPart(Boolean value) { }
	// RVA: 0x246bed8 VA: 0x7594a83ed8
	public GiftShowType get_giftShowType() { }
	// RVA: 0x246cfd0 VA: 0x7594a84fd0
	private Void set_giftShowType(GiftShowType value) { }
	// RVA: 0x246c490 VA: 0x7594a84490
	public Boolean InitData(ShopSkinItemViewModel viewModel, Boolean useVoucher, Boolean useSideGiftPart) { }
	// RVA: 0x246c420 VA: 0x7594a84420
	public Void .ctor() { }
}
```
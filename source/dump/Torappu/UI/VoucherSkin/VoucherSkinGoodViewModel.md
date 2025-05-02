# VoucherSkinGoodViewModel

**Namespace:** `Torappu.UI.VoucherSkin`


## Fields

- `String goodId`

- `Int32 slotId`

- `String skinId`

- `String skinName`

- `Boolean hasGot`

- `String skinGroup`

- `CharUISkinStruct skinStruct`

- `Boolean isRedeem`


## Methods

- `Boolean LoadData(ShopSkinItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoucherSkin
public class VoucherSkinGoodViewModel : IHotfixable
{
	public String goodId; // 0x10
	public Int32 slotId; // 0x18
	public String skinId; // 0x20
	public String skinName; // 0x28
	public Boolean hasGot; // 0x30
	public String skinGroup; // 0x38
	public CharUISkinStruct skinStruct; // 0x40
	public Boolean isRedeem; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x22931b8 VA: 0x75948ab1b8
	public Boolean LoadData(ShopSkinItemViewModel good) { }
	// RVA: 0x22933a4 VA: 0x75948ab3a4
	public Void .ctor() { }
}
```
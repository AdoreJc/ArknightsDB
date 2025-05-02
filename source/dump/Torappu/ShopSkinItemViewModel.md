# ShopSkinItemViewModel

**Namespace:** `Torappu`


## Fields

- `String goodId`

- `Int32 slotId`

- `String skinId`

- `Int32 originPrice`

- `Int32 price`

- `Single discount`

- `String skinName`

- `ShopCurrencyUnit currencyUnit`

- `Int64 startDateTime`

- `Int64 endDateTime`

- `Boolean isRedeem`

- `String giftAvatarId`

- `String giftDesc`


## Methods

- `ShopCashInfo GetCashInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ShopSkinItemViewModel : IHotfixable
{
	public String goodId; // 0x10
	public Int32 slotId; // 0x18
	public String skinId; // 0x20
	public Int32 originPrice; // 0x28
	public Int32 price; // 0x2c
	public Single discount; // 0x30
	public String skinName; // 0x38
	public ShopCurrencyUnit currencyUnit; // 0x40
	public Int64 startDateTime; // 0x48
	public Int64 endDateTime; // 0x50
	public Boolean isRedeem; // 0x58
	public String giftAvatarId; // 0x60
	public String giftDesc; // 0x68
	private static DelegateBridge __Hotfix0_GetCashInfo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x32ccd74 VA: 0x75958e4d74
	public ShopCashInfo GetCashInfo() { }
	// RVA: 0x32cce4c VA: 0x75958e4e4c
	public Void .ctor() { }
}
```
# TemplateNormalShopGoodViewModel

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `String displayName`

- `ItemBundle item`

- `String progressGoodId`

- `Int32 price`

- `Int32 availCount`

- `Int32 buyCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateNormalShopGoodViewModel : TemplateCommonShopGoodViewModel
{
	public String displayName; // 0x20
	public ItemBundle item; // 0x28
	public String progressGoodId; // 0x30
	public Int32 price; // 0x38
	public Int32 availCount; // 0x3c
	public Int32 buyCount; // 0x40


	// RVA: 0x2360b4c VA: 0x7594978b4c
	public override Int32 GetAvailCount() { }
	// RVA: 0x2360b54 VA: 0x7594978b54
	public override String GetDisplayName() { }
	// RVA: 0x2360b5c VA: 0x7594978b5c
	public override ItemBundle GetItem() { }
	// RVA: 0x2360b64 VA: 0x7594978b64
	public override Int32 GetPrice() { }
	// RVA: 0x2360b6c VA: 0x7594978b6c
	public override Int32 GetRemainCount() { }
	// RVA: 0x2360b84 VA: 0x7594978b84
	public override Boolean GetBuyableFlag() { }
	// RVA: 0x2360bc8 VA: 0x7594978bc8
	public Void .ctor() { }
}
```
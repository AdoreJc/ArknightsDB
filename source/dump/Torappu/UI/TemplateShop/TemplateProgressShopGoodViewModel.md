# TemplateProgressShopGoodViewModel

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `String progressGoodId`

- `PlayerGoodProgressData playerProgressInfo`


## Methods

- `ProgessGoodItem GetGoodItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateProgressShopGoodViewModel : TemplateCommonShopGoodViewModel
{
	public String progressGoodId; // 0x20
	public List`1 progressItemList; // 0x28
	public PlayerGoodProgressData playerProgressInfo; // 0x30


	// RVA: 0x2360970 VA: 0x7594978970
	public ProgessGoodItem GetGoodItem() { }
	// RVA: 0x2360a3c VA: 0x7594978a3c
	public override Int32 GetAvailCount() { }
	// RVA: 0x2360a44 VA: 0x7594978a44
	public override String GetDisplayName() { }
	// RVA: 0x2360aa4 VA: 0x7594978aa4
	public override ItemBundle GetItem() { }
	// RVA: 0x2360abc VA: 0x7594978abc
	public override Int32 GetPrice() { }
	// RVA: 0x2360adc VA: 0x7594978adc
	public override Int32 GetRemainCount() { }
	// RVA: 0x2360b00 VA: 0x7594978b00
	public override Boolean GetBuyableFlag() { }
	// RVA: 0x2360b44 VA: 0x7594978b44
	public Void .ctor() { }
}
```
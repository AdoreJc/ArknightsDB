# QCShopREPGood

**Namespace:** `Torappu.UI.Shop`


## Fields

- `REPGood goodData`

- `PlayerGoodItemData playerShop`


## Properties

- `Boolean isSoldOut`

- `Int32 RemainCount`


## Methods

- `Boolean get_isSoldOut()`

- `Int32 get_RemainCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopREPGood
{
	public REPGood goodData; // 0x10
	public PlayerGoodItemData playerShop; // 0x18

	public Boolean isSoldOut { get; }
	public Int32 RemainCount { get; }

	// RVA: 0x2459814 VA: 0x7594a71814
	public Boolean get_isSoldOut() { }
	// RVA: 0x2459850 VA: 0x7594a71850
	public Int32 get_RemainCount() { }
	// RVA: 0x2459888 VA: 0x7594a71888
	public Void .ctor() { }
}
```
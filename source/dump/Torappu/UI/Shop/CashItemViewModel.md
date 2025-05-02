# CashItemViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `CashShopObject cacheData`

- `ShopCashInfo cashInfo`

- `Boolean isDouble`


## Methods

- `Void ApplyData(CashShopObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class CashItemViewModel : IHotfixable
{
	public CashShopObject cacheData; // 0x10
	public ShopCashInfo cashInfo; // 0x18
	public Boolean isDouble; // 0x28
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x24273b8 VA: 0x7594a3f3b8
	public Void ApplyData(CashShopObject data) { }
	// RVA: 0x2427574 VA: 0x7594a3f574
	public Void .ctor() { }
}
```
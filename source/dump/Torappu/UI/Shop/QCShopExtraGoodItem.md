# QCShopExtraGoodItem

**Namespace:** `Torappu.UI.Shop`


## Fields

- `GameObject _newObj`

- `GameObject _replenishTimePart`

- `Text _replenishTimeText`

- `QCShopExtraObj m_cacheObj`

- `ShopDetailPriceType m_cachePriceType`


## Methods

- `Void ApplyNormalData(QCShopExtraObj, ShopDetailPriceType, SpriteHub)`

- `Void OpenItemDetail()`

- `Void <>xLuaBaseProxy_SetSoldOutObj(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopExtraGoodItem : QCBaseGoodItem, IHotfixable
{
	private GameObject _newObj; // 0xa8
	private GameObject _replenishTimePart; // 0xb0
	private Text _replenishTimeText; // 0xb8
	private QCShopExtraObj m_cacheObj; // 0xc0
	private ShopDetailPriceType m_cachePriceType; // 0xc8
	private static DelegateBridge __Hotfix0_ApplyNormalData; // 0x0
	private static DelegateBridge __Hotfix0_SetSoldOutObj; // 0x8
	private static DelegateBridge __Hotfix0_OpenItemDetail; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x245300c VA: 0x7594a6b00c
	public Void ApplyNormalData(QCShopExtraObj obj, ShopDetailPriceType priceType, SpriteHub hub) { }
	// RVA: 0x245318c VA: 0x7594a6b18c
	protected override Void SetSoldOutObj(Boolean isSoldOut) { }
	// RVA: 0x2453458 VA: 0x7594a6b458
	public Void OpenItemDetail() { }
	// RVA: 0x24534c8 VA: 0x7594a6b4c8
	public Void .ctor() { }
	// RVA: 0x2453538 VA: 0x7594a6b538
	private Void <>xLuaBaseProxy_SetSoldOutObj(Boolean P0) { }
}
```
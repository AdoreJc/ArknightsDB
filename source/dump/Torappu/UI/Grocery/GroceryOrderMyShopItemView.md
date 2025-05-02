# GroceryOrderMyShopItemView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `SimpleLayoutContent _selfShopStrategyContent`

- `GameObject _objStock`

- `Text _txtStockCount`

- `GameObject _objUnknownCount`

- `GameObject _objExactCount`

- `Text _txtExactCount`

- `GameObject _objRangeCount`

- `Text _txtRangeDownCount`

- `Text _txtRangeUpCount`

- `Boolean m_hasInited`

- `GroceryOrderMyShopStrategyItemViewAdapter m_adapterMyShopStrategy`

- `GroceryOrderSelfShopViewModel m_cachedViewModel`

- `GroceryOrderCountTextTweener m_exactCountTweener`

- `GroceryOrderCountTextTweener m_rangeDownCountTweener`

- `GroceryOrderCountTextTweener m_rangeUpCountTweener`


## Methods

- `Void Render(GroceryOrderSelfShopViewModel, String)`

- `Void _InitIfNot()`

- `Void _RefreshExpectedOrderCount(GroceryOrderSelfShopViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderMyShopItemView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _selfShopStrategyContent; // 0x18
	private GameObject _objStock; // 0x20
	private Text _txtStockCount; // 0x28
	private GameObject _objUnknownCount; // 0x30
	private GameObject _objExactCount; // 0x38
	private Text _txtExactCount; // 0x40
	private GameObject _objRangeCount; // 0x48
	private Text _txtRangeDownCount; // 0x50
	private Text _txtRangeUpCount; // 0x58
	private Boolean m_hasInited; // 0x60
	private GroceryOrderMyShopStrategyItemViewAdapter m_adapterMyShopStrategy; // 0x68
	private GroceryOrderSelfShopViewModel m_cachedViewModel; // 0x70
	private GroceryOrderCountTextTweener m_exactCountTweener; // 0x78
	private GroceryOrderCountTextTweener m_rangeDownCountTweener; // 0x80
	private GroceryOrderCountTextTweener m_rangeUpCountTweener; // 0x88
	private const Single CNT_CHANGE_DUR; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RefreshExpectedOrderCount; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2887934 VA: 0x7594e9f934
	public Void Render(GroceryOrderSelfShopViewModel selfShopViewModel, String curChangingGoodId) { }
	// RVA: 0x28882a4 VA: 0x7594ea02a4
	private Void _InitIfNot() { }
	// RVA: 0x28884d8 VA: 0x7594ea04d8
	private Void _RefreshExpectedOrderCount(GroceryOrderSelfShopViewModel itemViewModel, Boolean fastMode) { }
	// RVA: 0x2888994 VA: 0x7594ea0994
	public Void .ctor() { }
}
```
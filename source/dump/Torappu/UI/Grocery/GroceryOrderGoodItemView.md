# GroceryOrderGoodItemView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Text _txtGoodName`

- `Text _txtGoodOfferCount`

- `Image _imgGoodIcon`

- `SimpleLayoutContent _otherShopContent`

- `GroceryOrderMyShopItemView _myShopItemView`

- `GameObject _panelGoods`

- `GameObject _panelPrice`

- `GameObject _panelInquire`

- `Boolean m_hasInited`

- `String m_cachedGoodId`

- `UIStateFinder m_stateFinder`

- `GrocerOrderOtherShopItemViewAdapter m_adapterOtherShop`

- `String m_curChangingGoodId`

- `GroceryOrderGoodItemViewModel m_cachedViewModel`


## Methods

- `Void Render(GroceryOrderGoodItemViewModel, String)`

- `Void RegisterTutorialGO()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderGoodItemView : MonoBehaviour, IHotfixable
{
	private Text _txtGoodName; // 0x18
	private Text _txtGoodOfferCount; // 0x20
	private Image _imgGoodIcon; // 0x28
	private SimpleLayoutContent _otherShopContent; // 0x30
	private GroceryOrderMyShopItemView _myShopItemView; // 0x38
	private GameObject _panelGoods; // 0x40
	private GameObject _panelPrice; // 0x48
	private GameObject _panelInquire; // 0x50
	private Boolean m_hasInited; // 0x58
	private String m_cachedGoodId; // 0x60
	private UIStateFinder m_stateFinder; // 0x68
	private GrocerOrderOtherShopItemViewAdapter m_adapterOtherShop; // 0x78
	private String m_curChangingGoodId; // 0x80
	private GroceryOrderGoodItemViewModel m_cachedViewModel; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RegisterTutorialGO; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x288743c VA: 0x7594e9f43c
	public Void Render(GroceryOrderGoodItemViewModel goodItemViewModel, String curChangingGoodId) { }
	// RVA: 0x2887a88 VA: 0x7594e9fa88
	public Void RegisterTutorialGO() { }
	// RVA: 0x2887620 VA: 0x7594e9f620
	private Void _InitIfNot() { }
	// RVA: 0x2887c48 VA: 0x7594e9fc48
	public Void .ctor() { }
}
```
# GroceryOrderResultGoodItemView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Text _txtGoodName`

- `Image _imgGoodIcon`

- `SimpleLayoutContent _shopContent`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `GroceryOrderResultGoodItemViewModel m_cachedViewModel`

- `GrocerOrderResultShopItemViewAdapter m_adapterShop`


## Methods

- `Void Render(GroceryOrderResultGoodItemViewModel)`

- `IEnumerator PlayShopItemSliderTween()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderResultGoodItemView : MonoBehaviour, IHotfixable
{
	private Text _txtGoodName; // 0x18
	private Image _imgGoodIcon; // 0x20
	private SimpleLayoutContent _shopContent; // 0x28
	private Boolean m_hasInited; // 0x30
	private UIStateFinder m_stateFinder; // 0x38
	private GroceryOrderResultGoodItemViewModel m_cachedViewModel; // 0x48
	private GrocerOrderResultShopItemViewAdapter m_adapterShop; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_PlayShopItemSliderTween; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2893b68 VA: 0x7594eabb68
	public Void Render(GroceryOrderResultGoodItemViewModel goodItemViewModel) { }
	// RVA: 0x2893e68 VA: 0x7594eabe68
	public IEnumerator PlayShopItemSliderTween() { }
	// RVA: 0x2893c8c VA: 0x7594eabc8c
	private Void _InitIfNot() { }
	// RVA: 0x2893fd0 VA: 0x7594eabfd0
	public Void .ctor() { }
}
```
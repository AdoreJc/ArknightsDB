# GroceryOrderResultView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GameObject _objMinus`

- `Text _txtTotalCost`

- `SimpleLayoutContent _goodContent`

- `RectTransform _rectBackBtn`

- `Boolean m_hasInited`

- `GroceryOrderResultViewModel m_cachedViewModel`

- `UIStateFinder m_stateFinder`

- `GrocerOrderResultGoodItemViewAdapter m_adapterGood`

- `UIPage m_page`

- `GroceryOrderCountTextTweener m_totalCostTextTweener`


## Methods

- `IEnumerator PlayGoodsShopsEnterAnim()`

- `Void Init(UIPage)`

- `Void _InitIfNot()`

- `Void OnBackClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderResultView : DataBinder`1
{
	private GameObject _objMinus; // 0x20
	private Text _txtTotalCost; // 0x28
	private SimpleLayoutContent _goodContent; // 0x30
	private RectTransform _rectBackBtn; // 0x38
	private Boolean m_hasInited; // 0x40
	private GroceryOrderResultViewModel m_cachedViewModel; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private GrocerOrderResultGoodItemViewAdapter m_adapterGood; // 0x60
	private UIPage m_page; // 0x68
	private GroceryOrderCountTextTweener m_totalCostTextTweener; // 0x70
	private const Single TOTAL_COST_SHOW_DELAY; // 0x0
	private const Single TOTAL_COST_CHANGE_DUR; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_PlayGoodsShopsEnterAnim; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x28957a8 VA: 0x7594ead7a8
	public override Void OnValueChanged(GroceryOrderResultProperty property) { }
	// RVA: 0x288c7a0 VA: 0x7594ea47a0
	public IEnumerator PlayGoodsShopsEnterAnim() { }
	// RVA: 0x288a4bc VA: 0x7594ea24bc
	public Void Init(UIPage page) { }
	// RVA: 0x2895870 VA: 0x7594ead870
	private Void _InitIfNot() { }
	// RVA: 0x2895b18 VA: 0x7594eadb18
	public Void OnBackClick() { }
	// RVA: 0x2895bbc VA: 0x7594eadbbc
	public Void .ctor() { }
}
```
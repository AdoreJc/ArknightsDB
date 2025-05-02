# TemplateShopCommonRightComplexView

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `Text _shopBuyCount`

- `Text _shopItemName`

- `Text _shopPerCount`

- `Text _shopAvailCount`

- `Text _totalPrice`

- `Text _alreadyHaveCount`

- `Text _singlePrice`

- `Text _constText`

- `Image _colorIcon`

- `Image _blackIcon`

- `Image _buyColor`

- `Text _replicateDetail`

- `UnityEvent _onBuyChangedEvent`

- `Int32 m_shopBuyCount`

- `TemplateCommonShopGoodViewModel m_cacheViewModel`


## Methods

- `Void RefreshReplicateInfo(TemplateCommonShopGoodViewModel)`

- `Void Render(TemplateCommonShopGoodViewModel, Boolean, Int32, ItemBundle)`

- `Int32 RefreshNum(Int32)`

- `Void _RefreshClick()`

- `Void AddOne()`

- `Void MinusOne()`

- `Void AddToMax()`

- `Void MinusToOne()`

- `Int32 GetBuyCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopCommonRightComplexView : MonoBehaviour, IHotfixable
{
	private Text _shopBuyCount; // 0x18
	private Text _shopItemName; // 0x20
	private Text _shopPerCount; // 0x28
	private Text _shopAvailCount; // 0x30
	private Text _totalPrice; // 0x38
	private Text _alreadyHaveCount; // 0x40
	private Text _singlePrice; // 0x48
	private Text _constText; // 0x50
	private Image _colorIcon; // 0x58
	private Image _blackIcon; // 0x60
	private Image _buyColor; // 0x68
	private Text _replicateDetail; // 0x70
	private UnityEvent _onBuyChangedEvent; // 0x78
	private Int32 m_shopBuyCount; // 0x80
	private TemplateCommonShopGoodViewModel m_cacheViewModel; // 0x88
	private static DelegateBridge __Hotfix0_RefreshReplicateInfo; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_RefreshNum; // 0x10
	private static DelegateBridge __Hotfix0__RefreshClick; // 0x18
	private static DelegateBridge __Hotfix0_AddOne; // 0x20
	private static DelegateBridge __Hotfix0_MinusOne; // 0x28
	private static DelegateBridge __Hotfix0_AddToMax; // 0x30
	private static DelegateBridge __Hotfix0_MinusToOne; // 0x38
	private static DelegateBridge __Hotfix0_GetMaxPrice; // 0x40
	private static DelegateBridge __Hotfix0_GetBuyCount; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x235be40 VA: 0x7594973e40
	public Void RefreshReplicateInfo(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x235bed4 VA: 0x7594973ed4
	public Void Render(TemplateCommonShopGoodViewModel shopInfo, Boolean isReplicate, Int32 availCount, ItemBundle item) { }
	// RVA: 0x235c4b4 VA: 0x75949744b4
	public Int32 RefreshNum(Int32 currCount) { }
	// RVA: 0x235c57c VA: 0x759497457c
	private Void _RefreshClick() { }
	// RVA: 0x235c7fc VA: 0x75949747fc
	public Void AddOne() { }
	// RVA: 0x235c888 VA: 0x7594974888
	public Void MinusOne() { }
	// RVA: 0x235c914 VA: 0x7594974914
	public Void AddToMax() { }
	// RVA: 0x235c9cc VA: 0x75949749cc
	public Void MinusToOne() { }
	// RVA: 0x235c668 VA: 0x7594974668
	public static Int32 GetMaxPrice(Int32 price, Int32 maxCount) { }
	// RVA: 0x235ca54 VA: 0x7594974a54
	public Int32 GetBuyCount() { }
	// RVA: 0x235cac8 VA: 0x7594974ac8
	public Void .ctor() { }
}
```
# ShopDetailComplexView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _shopBuyCount`

- `Text _shopItemName`

- `Text _shopPerCount`

- `Text _shopAvailCount`

- `Text _totalPrice`

- `Image _finalPriceIcon`

- `ShopDetailItemPileView _pileView`

- `Button _maxButton`

- `Text _maxButtonText`

- `Int32 m_shopBuyCount`

- `Int32 m_perPrice`


## Methods

- `Int32 RefreshNum(Int32)`

- `Void _RefreshClick()`

- `Void AddOne()`

- `Void MinusOne()`

- `Void AddToMax()`

- `Void MinusToOne()`

- `Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel, SpriteHub)`

- `Void <>xLuaBaseProxy_OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailComplexView : ShopDetailCommonView, IHotfixable
{
	private Text _shopBuyCount; // 0xa8
	private Text _shopItemName; // 0xb0
	private Text _shopPerCount; // 0xb8
	private Text _shopAvailCount; // 0xc0
	private Text _totalPrice; // 0xc8
	private Image _finalPriceIcon; // 0xd0
	private ShopDetailItemPileView _pileView; // 0xd8
	private Button _maxButton; // 0xe0
	private Text _maxButtonText; // 0xe8
	private Int32 m_shopBuyCount; // 0xf0
	private Int32 m_perPrice; // 0xf4
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshNum; // 0x8
	private static DelegateBridge __Hotfix0__RefreshClick; // 0x10
	private static DelegateBridge __Hotfix0_AddOne; // 0x18
	private static DelegateBridge __Hotfix0_MinusOne; // 0x20
	private static DelegateBridge __Hotfix0_AddToMax; // 0x28
	private static DelegateBridge __Hotfix0_MinusToOne; // 0x30
	private static DelegateBridge __Hotfix0_OnClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2431cac VA: 0x7594a49cac
	public override Void ApplyData(DetailCommonViewModel viewModel, SpriteHub priceTypeHub) { }
	// RVA: 0x24320b8 VA: 0x7594a4a0b8
	public Int32 RefreshNum(Int32 currCount) { }
	// RVA: 0x2432164 VA: 0x7594a4a164
	private Void _RefreshClick() { }
	// RVA: 0x2432238 VA: 0x7594a4a238
	public Void AddOne() { }
	// RVA: 0x24322b4 VA: 0x7594a4a2b4
	public Void MinusOne() { }
	// RVA: 0x2432330 VA: 0x7594a4a330
	public Void AddToMax() { }
	// RVA: 0x24323c0 VA: 0x7594a4a3c0
	public Void MinusToOne() { }
	// RVA: 0x2432438 VA: 0x7594a4a438
	public override Void OnClick() { }
	// RVA: 0x243251c VA: 0x7594a4a51c
	public Void .ctor() { }
	// RVA: 0x2432588 VA: 0x7594a4a588
	private Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel P0, SpriteHub P1) { }
	// RVA: 0x243258c VA: 0x7594a4a58c
	private Void <>xLuaBaseProxy_OnClick() { }
}
```
# ShopDetailFurnView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ThreeStateToggle _coinPart`

- `ThreeStateToggle _diamPart`

- `Text _shopBuyCount`

- `Text _shopCurrentCount`

- `Text _shopAvailCount`

- `Transform _itemContainer`

- `UIItemCard _itemCard`

- `Image _totalIcon`

- `Text _totalPrice`

- `Text _addText`

- `Text _itemDetailName`

- `Int32 m_shopBuyCount`

- `Boolean m_isDiamAvail`

- `Boolean m_isCoinAvail`

- `Int32 m_remainCount`

- `SpriteHub m_priceTypeHub`

- `SelectClass m_selectPriceFlag`

- `UIItemCard m_itemCard`


## Methods

- `Void ApplyPriceState()`

- `Int32 RefreshNum(Int32)`

- `Void TurnCoinFurn()`

- `Void TurnCoinDiam()`

- `Void AddOne()`

- `Void MinusOne()`

- `Void AddToMax()`

- `Void MinusToOne()`

- `Void <>xLuaBaseProxy_OnClick()`

- `Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel, SpriteHub)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailFurnView : ShopDetailCommonView, IHotfixable
{
	private ThreeStateToggle _coinPart; // 0xa8
	private ThreeStateToggle _diamPart; // 0xb0
	private Text _shopBuyCount; // 0xb8
	private Text _shopCurrentCount; // 0xc0
	private Text _shopAvailCount; // 0xc8
	private Transform _itemContainer; // 0xd0
	private UIItemCard _itemCard; // 0xd8
	private Image _totalIcon; // 0xe0
	private Text _totalPrice; // 0xe8
	private Text _addText; // 0xf0
	private Text _itemDetailName; // 0xf8
	private Image[] _whiteFurniIcons; // 0x100
	private Image[] _whiteDiamondIcons; // 0x108
	private Int32 m_shopBuyCount; // 0x110
	private Boolean m_isDiamAvail; // 0x114
	private Boolean m_isCoinAvail; // 0x115
	private Int32 m_remainCount; // 0x118
	private SpriteHub m_priceTypeHub; // 0x120
	private SelectClass m_selectPriceFlag; // 0x128
	private UIItemCard m_itemCard; // 0x130
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge __Hotfix0_ApplyPriceState; // 0x10
	private static DelegateBridge __Hotfix0_RefreshNum; // 0x18
	private static DelegateBridge __Hotfix0_TurnCoinFurn; // 0x20
	private static DelegateBridge __Hotfix0_TurnCoinDiam; // 0x28
	private static DelegateBridge __Hotfix0_AddOne; // 0x30
	private static DelegateBridge __Hotfix0_MinusOne; // 0x38
	private static DelegateBridge __Hotfix0_AddToMax; // 0x40
	private static DelegateBridge __Hotfix0_MinusToOne; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2435cb8 VA: 0x7594a4dcb8
	public override Void OnClick() { }
	// RVA: 0x2435db8 VA: 0x7594a4ddb8
	public override Void ApplyData(DetailCommonViewModel viewModel, SpriteHub priceTypeHub) { }
	// RVA: 0x2436650 VA: 0x7594a4e650
	public Void ApplyPriceState() { }
	// RVA: 0x24364c4 VA: 0x7594a4e4c4
	public Int32 RefreshNum(Int32 currCount) { }
	// RVA: 0x2436d30 VA: 0x7594a4ed30
	public Void TurnCoinFurn() { }
	// RVA: 0x2436e6c VA: 0x7594a4ee6c
	public Void TurnCoinDiam() { }
	// RVA: 0x2436fac VA: 0x7594a4efac
	public Void AddOne() { }
	// RVA: 0x243709c VA: 0x7594a4f09c
	public Void MinusOne() { }
	// RVA: 0x2437118 VA: 0x7594a4f118
	public Void AddToMax() { }
	// RVA: 0x2437204 VA: 0x7594a4f204
	public Void MinusToOne() { }
	// RVA: 0x24372f0 VA: 0x7594a4f2f0
	public Void .ctor() { }
	// RVA: 0x243735c VA: 0x7594a4f35c
	private Void <>xLuaBaseProxy_OnClick() { }
	// RVA: 0x2437360 VA: 0x7594a4f360
	private Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel P0, SpriteHub P1) { }
}
```
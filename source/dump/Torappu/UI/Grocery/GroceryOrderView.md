# GroceryOrderView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Text _txtDrinkCustomerCount`

- `Text _txtFoodCustomerCount`

- `Text _txtCoinCustomerCount`

- `Text _txtInquireCurCnt`

- `Text _txtInquireTotalCnt`

- `ScrollRect _scrollRectGoods`

- `SimpleLayoutContent _goodsContent`

- `SimpleLayoutContent _strategyBriefContent`

- `GameObject _panelCustomer`

- `GameObject _panelInquireDetail`

- `GroceryOrderCountTextTweener m_drinkCustomerCntTweener`

- `GroceryOrderCountTextTweener m_foodCustomerCntTweener`

- `GroceryOrderCountTextTweener m_coinCustomerCntTweener`

- `GroceryOrderViewModel m_cachedViewModel`

- `GroceryOrderGoodItemViewAdapter m_adapterGoods`

- `GroceryOrderStrategyBriefItemViewAdapter m_adapterStrategyBriefs`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInited`

- `Boolean m_playedCustomerTween`


## Methods

- `Void StateOnlyRegisterTutorialGO()`

- `Void PlayEnterCustomerCountTween()`

- `Void ScrollGoodsToTopIfNecessary()`

- `Void ResetCustomerCount()`

- `Void _InitIfNot()`

- `Void _PlayCustomerCountTween(Int32, Int32, Int32)`

- `Void OnConfirmClick()`

- `Void OnInquireDetailClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderView : DataBinder`1
{
	private const Int32 TUTORIAL_GOOD_POSITION; // 0x0
	private Text _txtDrinkCustomerCount; // 0x20
	private Text _txtFoodCustomerCount; // 0x28
	private Text _txtCoinCustomerCount; // 0x30
	private Text _txtInquireCurCnt; // 0x38
	private Text _txtInquireTotalCnt; // 0x40
	private ScrollRect _scrollRectGoods; // 0x48
	private SimpleLayoutContent _goodsContent; // 0x50
	private SimpleLayoutContent _strategyBriefContent; // 0x58
	private GameObject _panelCustomer; // 0x60
	private GameObject _panelInquireDetail; // 0x68
	private GroceryOrderCountTextTweener m_drinkCustomerCntTweener; // 0x70
	private GroceryOrderCountTextTweener m_foodCustomerCntTweener; // 0x78
	private GroceryOrderCountTextTweener m_coinCustomerCntTweener; // 0x80
	private GroceryOrderViewModel m_cachedViewModel; // 0x88
	private GroceryOrderGoodItemViewAdapter m_adapterGoods; // 0x90
	private GroceryOrderStrategyBriefItemViewAdapter m_adapterStrategyBriefs; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private Boolean m_hasInited; // 0xb0
	private Boolean m_playedCustomerTween; // 0xb1
	private const Single CUSTOMER_CNT_CHANGE_DUR; // 0x0
	private const Single GOODS_SCROLL_TOP_DUR; // 0x0
	private const String INIT_CUSTOMER_COUNT; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_StateOnlyRegisterTutorialGO; // 0x8
	private static DelegateBridge __Hotfix0_PlayEnterCustomerCountTween; // 0x10
	private static DelegateBridge __Hotfix0_ScrollGoodsToTopIfNecessary; // 0x18
	private static DelegateBridge __Hotfix0_ResetCustomerCount; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__PlayCustomerCountTween; // 0x30
	private static DelegateBridge __Hotfix0_OnConfirmClick; // 0x38
	private static DelegateBridge __Hotfix0_OnInquireDetailClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x288d94c VA: 0x7594ea594c
	public override Void OnValueChanged(GroceryOrderProperty property) { }
	// RVA: 0x288b5cc VA: 0x7594ea35cc
	public Void StateOnlyRegisterTutorialGO() { }
	// RVA: 0x288cbdc VA: 0x7594ea4bdc
	public Void PlayEnterCustomerCountTween() { }
	// RVA: 0x288cc94 VA: 0x7594ea4c94
	public Void ScrollGoodsToTopIfNecessary() { }
	// RVA: 0x288cb10 VA: 0x7594ea4b10
	public Void ResetCustomerCount() { }
	// RVA: 0x288da98 VA: 0x7594ea5a98
	private Void _InitIfNot() { }
	// RVA: 0x288dee8 VA: 0x7594ea5ee8
	private Void _PlayCustomerCountTween(Int32 drinkEndCnt, Int32 foodEndCnt, Int32 coinEndCnt) { }
	// RVA: 0x288e124 VA: 0x7594ea6124
	public Void OnConfirmClick() { }
	// RVA: 0x288e1c8 VA: 0x7594ea61c8
	public Void OnInquireDetailClick() { }
	// RVA: 0x288e26c VA: 0x7594ea626c
	public Void .ctor() { }
}
```
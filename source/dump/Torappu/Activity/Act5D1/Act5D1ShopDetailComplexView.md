# Act5D1ShopDetailComplexView

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Int32 m_shopBuyCount`

- `Act5D1ShopDetailItemPileView _pileView`

- `Text _shopBuyCount`

- `Text _remainCount`

- `Text _shopItemName`

- `Text _shopPerCount`

- `Text _shopAvailCount`

- `Text _totalPrice`

- `Act5D1ShopCommonViewModel m_data`


## Methods

- `Void AddOne()`

- `Void MinusOne()`

- `Void AddToMax()`

- `Void MinusToOne()`

- `Int32 GetMaxPrice()`

- `Int32 RefreshNum(Int32)`

- `Void _RefreshClick()`

- `Void <>xLuaBaseProxy_ApplyData(Act5D1ShopCommonViewModel)`

- `Void <>xLuaBaseProxy_OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1ShopDetailComplexView : Act5D1ShopDetailView, IHotfixable
{
	private Int32 m_shopBuyCount; // 0x40
	private Act5D1ShopDetailItemPileView _pileView; // 0x48
	private Text _shopBuyCount; // 0x50
	private Text _remainCount; // 0x58
	private Text _shopItemName; // 0x60
	private Text _shopPerCount; // 0x68
	private Text _shopAvailCount; // 0x70
	private Text _totalPrice; // 0x78
	private Act5D1ShopCommonViewModel m_data; // 0x80
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_AddOne; // 0x10
	private static DelegateBridge __Hotfix0_MinusOne; // 0x18
	private static DelegateBridge __Hotfix0_AddToMax; // 0x20
	private static DelegateBridge __Hotfix0_MinusToOne; // 0x28
	private static DelegateBridge __Hotfix0_GetMaxPrice; // 0x30
	private static DelegateBridge __Hotfix0_RefreshNum; // 0x38
	private static DelegateBridge __Hotfix0__RefreshClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x31d6bc8 VA: 0x75957eebc8
	public override Void ApplyData(Act5D1ShopCommonViewModel data) { }
	// RVA: 0x31d71a8 VA: 0x75957ef1a8
	public override Void OnClick() { }
	// RVA: 0x31d723c VA: 0x75957ef23c
	public Void AddOne() { }
	// RVA: 0x31d72b8 VA: 0x75957ef2b8
	public Void MinusOne() { }
	// RVA: 0x31d7334 VA: 0x75957ef334
	public Void AddToMax() { }
	// RVA: 0x31d74bc VA: 0x75957ef4bc
	public Void MinusToOne() { }
	// RVA: 0x31d73a8 VA: 0x75957ef3a8
	public Int32 GetMaxPrice() { }
	// RVA: 0x31d7034 VA: 0x75957ef034
	public Int32 RefreshNum(Int32 currCount) { }
	// RVA: 0x31d70c4 VA: 0x75957ef0c4
	private Void _RefreshClick() { }
	// RVA: 0x31d7534 VA: 0x75957ef534
	public Void .ctor() { }
	// RVA: 0x31d7618 VA: 0x75957ef618
	private Void <>xLuaBaseProxy_ApplyData(Act5D1ShopCommonViewModel P0) { }
	// RVA: 0x31d781c VA: 0x75957ef81c
	private Void <>xLuaBaseProxy_OnClick() { }
}
```
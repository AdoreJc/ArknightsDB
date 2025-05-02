# CrisisShopComplexRightView

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `Text _shopBuyCount`

- `Text _shopItemName`

- `Text _shopPerCount`

- `Text _shopAvailCount`

- `Text _totalPrice`

- `Text _alreadyHaveCount`

- `Text _singlePrice`

- `UIIntEvent _buyEvent`

- `Int32 m_shopBuyCount`

- `CrisisShopWrapped m_cacheViewModel`


## Methods

- `Void Render(CrisisShopWrapped)`

- `Int32 RefreshNum(Int32)`

- `Void _RefreshClick()`

- `Void AddOne()`

- `Void MinusOne()`

- `Void AddToMax()`

- `Void MinusToOne()`

- `Int32 GetMaxPrice(Int32, Int32)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopComplexRightView : MonoBehaviour
{
	private Text _shopBuyCount; // 0x18
	private Text _shopItemName; // 0x20
	private Text _shopPerCount; // 0x28
	private Text _shopAvailCount; // 0x30
	private Text _totalPrice; // 0x38
	private Text _alreadyHaveCount; // 0x40
	private Text _singlePrice; // 0x48
	private UIIntEvent _buyEvent; // 0x50
	private Int32 m_shopBuyCount; // 0x58
	private CrisisShopWrapped m_cacheViewModel; // 0x60


	// RVA: 0x2c3af50 VA: 0x7595252f50
	public Void Render(CrisisShopWrapped shopInfo) { }
	// RVA: 0x2c3c520 VA: 0x7595254520
	public Int32 RefreshNum(Int32 currCount) { }
	// RVA: 0x2c3c5a0 VA: 0x75952545a0
	private Void _RefreshClick() { }
	// RVA: 0x2c3c75c VA: 0x759525475c
	public Void AddOne() { }
	// RVA: 0x2c3c780 VA: 0x7595254780
	public Void MinusOne() { }
	// RVA: 0x2c3c7a4 VA: 0x75952547a4
	public Void AddToMax() { }
	// RVA: 0x2c3c810 VA: 0x7595254810
	public Void MinusToOne() { }
	// RVA: 0x2c3c638 VA: 0x7595254638
	public Int32 GetMaxPrice(Int32 price, Int32 maxCount) { }
	// RVA: 0x2c3c830 VA: 0x7595254830
	public Void OnClick() { }
	// RVA: 0x2c3c894 VA: 0x7595254894
	public Void .ctor() { }
}
```
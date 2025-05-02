# DIYShopBuyItemLine

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _countLabel`

- `Text _totalCostLabel`

- `Argument m_currentArgument`

- `Int32 m_buyCount`


## Properties

- `Int32 buyCount`


## Methods

- `Void add_countChanged(Action`1)`

- `Void remove_countChanged(Action`1)`

- `Int32 get_buyCount()`

- `Void set_buyCount(Int32)`

- `Void _UpdateView()`

- `Void Setup(Argument)`

- `Void OnAddButtonPressed()`

- `Void OnMinusButtonPressed()`

- `Void OnMinButtonPressed()`

- `Void OnMaxButtonPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYShopBuyItemLine : MonoBehaviour
{
	private const String BUY_COUNT_FORMAT; // 0x0
	private Text _countLabel; // 0x18
	private Text _totalCostLabel; // 0x20
	private Argument m_currentArgument; // 0x28
	private Action`1 countChanged; // 0x30
	public Int32 m_buyCount; // 0x38

	public Int32 buyCount { get; set; }

	// RVA: 0x37ffbb8 VA: 0x7595e17bb8
	public Void add_countChanged(Action`1 value) { }
	// RVA: 0x37ffc68 VA: 0x7595e17c68
	public Void remove_countChanged(Action`1 value) { }
	// RVA: 0x37ffd18 VA: 0x7595e17d18
	public Int32 get_buyCount() { }
	// RVA: 0x37ffd30 VA: 0x7595e17d30
	public Void set_buyCount(Int32 value) { }
	// RVA: 0x37ffda0 VA: 0x7595e17da0
	private Void _UpdateView() { }
	// RVA: 0x37fff20 VA: 0x7595e17f20
	public Void Setup(Argument arg) { }
	// RVA: 0x37fff88 VA: 0x7595e17f88
	public Void OnAddButtonPressed() { }
	// RVA: 0x37fffa4 VA: 0x7595e17fa4
	public Void OnMinusButtonPressed() { }
	// RVA: 0x37fffc0 VA: 0x7595e17fc0
	public Void OnMinButtonPressed() { }
	// RVA: 0x37fffc8 VA: 0x7595e17fc8
	public Void OnMaxButtonPressed() { }
	// RVA: 0x37fffe4 VA: 0x7595e17fe4
	public Void .ctor() { }
}
```
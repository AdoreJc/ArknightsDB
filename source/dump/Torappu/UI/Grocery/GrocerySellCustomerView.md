# GrocerySellCustomerView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `SellGoodState _sellGood`

- `GameObject _panelCurrent`

- `GameObject _panelNotCurrent`

- `Text _textNonCurrentDesc`

- `Text _textCustomerCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellCustomerView : DataBinder`1, IHotfixable
{
	private SellGoodState _sellGood; // 0x20
	private GameObject _panelCurrent; // 0x28
	private GameObject _panelNotCurrent; // 0x30
	private Text _textNonCurrentDesc; // 0x38
	private Text _textCustomerCount; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2898840 VA: 0x7594eb0840
	public override Void OnValueChanged(GrocerySellProperty property) { }
	// RVA: 0x2898990 VA: 0x7594eb0990
	public Void .ctor() { }
}
```
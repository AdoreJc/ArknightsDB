# GroceryMileStoneView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `TwoStateToggle _buttonToggle`

- `UIColorGraphic _claimAllButtonGraphic`

- `Text _totalPointNumText`

- `GroceryMileStoneItemGridAdapter _adapter`

- `LoopHorizontalScrollRect _content`

- `GridLayoutGroup _layout`

- `Single _focusDuration`

- `TweenWrapper m_focusTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void OnGetAllClick()`

- `Void FocusOnIdx(Int32)`

- `Single <FocusOnIdx>b__14_0()`

- `Void <FocusOnIdx>b__14_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryMileStoneView : DataBinder`1, IHotfixable
{
	private const Int32 SLIDE_MAX_LENGTH; // 0x0
	private TwoStateToggle _buttonToggle; // 0x20
	private UIColorGraphic _claimAllButtonGraphic; // 0x28
	private Text _totalPointNumText; // 0x30
	private List`1 _furniNameList; // 0x38
	private List`1 _furniNeedPointList; // 0x40
	private GroceryMileStoneItemGridAdapter _adapter; // 0x48
	private LoopHorizontalScrollRect _content; // 0x50
	private GridLayoutGroup _layout; // 0x58
	private Single _focusDuration; // 0x60
	private TweenWrapper m_focusTween; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnGetAllClick; // 0x8
	private static DelegateBridge __Hotfix0_FocusOnIdx; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28ab0d8 VA: 0x7594ec30d8
	public override Void OnValueChanged(GroceryMileStoneProperty property) { }
	// RVA: 0x28ab35c VA: 0x7594ec335c
	public Void OnGetAllClick() { }
	// RVA: 0x28aa9c8 VA: 0x7594ec29c8
	public Void FocusOnIdx(Int32 targetIndex) { }
	// RVA: 0x28ab400 VA: 0x7594ec3400
	public Void .ctor() { }
	// RVA: 0x28ab498 VA: 0x7594ec3498
	private Single <FocusOnIdx>b__14_0() { }
	// RVA: 0x28ab4b4 VA: 0x7594ec34b4
	private Void <FocusOnIdx>b__14_1(Single value) { }
}
```
# GrocerySellSliderController

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `MagneticDotSliderView _view`

- `UISliderPager _sliderPager`

- `MagneticDotSliderViewModelProperty m_dotProp`

- `UIStateFinder m_stateFinder`

- `InvokeWhenUnlock m_updateSliderLatch`

- `Int32 m_resetDataVersion`

- `GrocerySellViewModel m_viewModel`

- `Boolean m_hasInited`

- `Int32 m_valueCount`

- `Int32 m_selectIndex`


## Methods

- `Void OnMinBtnClick()`

- `Void OnAddBtnClick()`

- `Void _OnSliderPageChanged(Int32)`

- `Void _OnSliderValueUpdating(Single)`

- `Void _OnSliderStateChanged(State)`

- `Void _InitIfNot(Int32)`

- `Void _UpdateSliderWhenStable()`

- `Void _NotifySelectionChanged(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellSliderController : DataBinder`1, IHotfixable
{
	private MagneticDotSliderView _view; // 0x20
	private UISliderPager _sliderPager; // 0x28
	private MagneticDotSliderViewModelProperty m_dotProp; // 0x30
	private UIStateFinder m_stateFinder; // 0x38
	private InvokeWhenUnlock m_updateSliderLatch; // 0x48
	private Int32 m_resetDataVersion; // 0x50
	private GrocerySellViewModel m_viewModel; // 0x58
	private Boolean m_hasInited; // 0x60
	private Int32 m_valueCount; // 0x64
	private Int32 m_selectIndex; // 0x68
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnMinBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnAddBtnClick; // 0x10
	private static DelegateBridge __Hotfix0__OnSliderPageChanged; // 0x18
	private static DelegateBridge __Hotfix0__OnSliderValueUpdating; // 0x20
	private static DelegateBridge __Hotfix0__OnSliderStateChanged; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__UpdateSliderWhenStable; // 0x38
	private static DelegateBridge __Hotfix0__NotifySelectionChanged; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2899d08 VA: 0x7594eb1d08
	public override Void OnValueChanged(GrocerySellProperty property) { }
	// RVA: 0x289a0dc VA: 0x7594eb20dc
	public Void OnMinBtnClick() { }
	// RVA: 0x289a180 VA: 0x7594eb2180
	public Void OnAddBtnClick() { }
	// RVA: 0x289a224 VA: 0x7594eb2224
	private Void _OnSliderPageChanged(Int32 selectedPage) { }
	// RVA: 0x289a374 VA: 0x7594eb2374
	private Void _OnSliderValueUpdating(Single pageIndex) { }
	// RVA: 0x289a4ec VA: 0x7594eb24ec
	private Void _OnSliderStateChanged(State state) { }
	// RVA: 0x2899e84 VA: 0x7594eb1e84
	private Void _InitIfNot(Int32 valueCount) { }
	// RVA: 0x289a5a0 VA: 0x7594eb25a0
	private Void _UpdateSliderWhenStable() { }
	// RVA: 0x289a2a4 VA: 0x7594eb22a4
	private Void _NotifySelectionChanged(Int32 targetIndex) { }
	// RVA: 0x289a780 VA: 0x7594eb2780
	public Void .ctor() { }
}
```
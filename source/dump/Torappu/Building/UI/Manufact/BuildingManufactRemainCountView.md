# BuildingManufactRemainCountView

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `CanvasGroup _panelChange`

- `Text _textCount`

- `FillProgressBar _progress`

- `UILongPressButton _btnPlus`

- `UILongPressButton _btnMinus`

- `FadeSwitchTween m_panelChangeSwitch`

- `CountDownTask m_countDown`

- `Single m_secPerItem`

- `Int32 m_remainSec`

- `Boolean m_inited`

- `Listener listeners`


## Methods

- `Void _InitIfNot()`

- `Void _RenderNormal(MRoomViewModel)`

- `Void _RenderEdit(MRoomViewModel)`

- `Void _UpdateCountDown(MRoomViewModel, ManufactSnapshot)`

- `Void _UpdateSecond(TickValue)`

- `Void _OnPlusClicked()`

- `Boolean _OnPlusLongPressed()`

- `Void _OnMinusClicked()`

- `Boolean _OnMinusLongPressed()`

- `Void EventOnConfirmClicked()`

- `Void EventOnCancelClicked()`

- `Void EventOnMaxClicked()`

- `Void EventOnMinClicked()`

- `Void _InvokeCountChanged(Int32)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactRemainCountView : DataBinder`1
{
	private const Int32 LONG_PRESS_DELTA; // 0x0
	private CanvasGroup _panelChange; // 0x20
	private Text _textCount; // 0x28
	private FillProgressBar _progress; // 0x30
	private UILongPressButton _btnPlus; // 0x38
	private UILongPressButton _btnMinus; // 0x40
	private FadeSwitchTween m_panelChangeSwitch; // 0x48
	private CountDownTask m_countDown; // 0x50
	private Single m_secPerItem; // 0x58
	private Int32 m_remainSec; // 0x5c
	private Boolean m_inited; // 0x60
	public Listener listeners; // 0x68
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderNormal; // 0x10
	private static DelegateBridge __Hotfix0__RenderEdit; // 0x18
	private static DelegateBridge __Hotfix0__UpdateCountDown; // 0x20
	private static DelegateBridge __Hotfix0__UpdateSecond; // 0x28
	private static DelegateBridge __Hotfix0__OnPlusClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnPlusLongPressed; // 0x38
	private static DelegateBridge __Hotfix0__OnMinusClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnMinusLongPressed; // 0x48
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x50
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x58
	private static DelegateBridge __Hotfix0_EventOnMaxClicked; // 0x60
	private static DelegateBridge __Hotfix0_EventOnMinClicked; // 0x68
	private static DelegateBridge __Hotfix0__InvokeCountChanged; // 0x70
	private static DelegateBridge __Hotfix0_Update; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x3e0ccec VA: 0x7596424cec
	public override Void OnValueChanged(MRoomViewPropety property) { }
	// RVA: 0x3e0cdec VA: 0x7596424dec
	private Void _InitIfNot() { }
	// RVA: 0x3e0d138 VA: 0x7596425138
	private Void _RenderNormal(MRoomViewModel viewModel) { }
	// RVA: 0x3e0d024 VA: 0x7596425024
	private Void _RenderEdit(MRoomViewModel viewModel) { }
	// RVA: 0x3e0d2f0 VA: 0x75964252f0
	private Void _UpdateCountDown(MRoomViewModel viewModel, ManufactSnapshot snapshot) { }
	// RVA: 0x3e0d4b4 VA: 0x75964254b4
	private Void _UpdateSecond(TickValue value) { }
	// RVA: 0x3e0d550 VA: 0x7596425550
	private Void _OnPlusClicked() { }
	// RVA: 0x3e0d65c VA: 0x759642565c
	private Boolean _OnPlusLongPressed() { }
	// RVA: 0x3e0d6d0 VA: 0x75964256d0
	private Void _OnMinusClicked() { }
	// RVA: 0x3e0d73c VA: 0x759642573c
	private Boolean _OnMinusLongPressed() { }
	// RVA: 0x3e0d7b0 VA: 0x75964257b0
	public Void EventOnConfirmClicked() { }
	// RVA: 0x3e0d834 VA: 0x7596425834
	public Void EventOnCancelClicked() { }
	// RVA: 0x3e0d8b8 VA: 0x75964258b8
	public Void EventOnMaxClicked() { }
	// RVA: 0x3e0d924 VA: 0x7596425924
	public Void EventOnMinClicked() { }
	// RVA: 0x3e0d5bc VA: 0x75964255bc
	private Void _InvokeCountChanged(Int32 delta) { }
	// RVA: 0x3e0d990 VA: 0x7596425990
	private Void Update() { }
	// RVA: 0x3e0da0c VA: 0x7596425a0c
	public Void .ctor() { }
}
```
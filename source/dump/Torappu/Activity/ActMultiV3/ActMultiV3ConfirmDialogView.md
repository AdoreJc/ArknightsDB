# ActMultiV3ConfirmDialogView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Text _dialogContentText`

- `Text _confirmBtnText`

- `Text _confirmOnlyBtnText`

- `Text _cancelBtnText`

- `TwoStateToggle _confirmOnlyToggle`

- `Action <onConfirm>k__BackingField`

- `Action <onCancel>k__BackingField`


## Properties

- `Action onConfirm`

- `Action onCancel`


## Methods

- `Void set_onConfirm(Action)`

- `Action get_onConfirm()`

- `Void set_onCancel(Action)`

- `Action get_onCancel()`

- `Void Render(ActMultiV3ConfirmDialogConfig)`

- `Void EventOnConfirm()`

- `Void EventOnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ConfirmDialogView : MonoBehaviour, IHotfixable
{
	private Text _dialogContentText; // 0x18
	private Text _confirmBtnText; // 0x20
	private Text _confirmOnlyBtnText; // 0x28
	private Text _cancelBtnText; // 0x30
	private TwoStateToggle _confirmOnlyToggle; // 0x38
	private Action <onConfirm>k__BackingField; // 0x40
	private Action <onCancel>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_set_onConfirm; // 0x0
	private static DelegateBridge __Hotfix0_get_onConfirm; // 0x8
	private static DelegateBridge __Hotfix0_set_onCancel; // 0x10
	private static DelegateBridge __Hotfix0_get_onCancel; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x28
	private static DelegateBridge __Hotfix0_EventOnCancel; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action onConfirm { get; set; }
	private Action onCancel { get; set; }

	// RVA: 0x30e5064 VA: 0x75956fd064
	public Void set_onConfirm(Action value) { }
	// RVA: 0x30e57bc VA: 0x75956fd7bc
	private Action get_onConfirm() { }
	// RVA: 0x30e50e8 VA: 0x75956fd0e8
	public Void set_onCancel(Action value) { }
	// RVA: 0x30e5824 VA: 0x75956fd824
	private Action get_onCancel() { }
	// RVA: 0x30e4f0c VA: 0x75956fcf0c
	public Void Render(ActMultiV3ConfirmDialogConfig config) { }
	// RVA: 0x30e588c VA: 0x75956fd88c
	public Void EventOnConfirm() { }
	// RVA: 0x30e5928 VA: 0x75956fd928
	public Void EventOnCancel() { }
	// RVA: 0x30e59c4 VA: 0x75956fd9c4
	public Void .ctor() { }
}
```
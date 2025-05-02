# UIPayCostCheckContent

**Namespace:** `Torappu.UI`


## Fields

- `UIBlurFloatPanel _floatPanel`

- `Text _textDesc`

- `Action <onConfirm>k__BackingField`

- `Action <onCancel>k__BackingField`


## Properties

- `Action onConfirm`

- `Action onCancel`


## Methods

- `Action get_onConfirm()`

- `Void set_onConfirm(Action)`

- `Action get_onCancel()`

- `Void set_onCancel(Action)`

- `Void Init()`

- `Void Show()`

- `Void Hide()`

- `Void EventOnConfirmClicked()`

- `Void EventOnCancelClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPayCostCheckContent : MonoBehaviour
{
	private UIBlurFloatPanel _floatPanel; // 0x18
	private Text _textDesc; // 0x20
	private Action <onConfirm>k__BackingField; // 0x28
	private Action <onCancel>k__BackingField; // 0x30

	public Action onConfirm { get; set; }
	public Action onCancel { get; set; }

	// RVA: 0x2196828 VA: 0x75947ae828
	public Action get_onConfirm() { }
	// RVA: 0x2196830 VA: 0x75947ae830
	public Void set_onConfirm(Action value) { }
	// RVA: 0x2196838 VA: 0x75947ae838
	public Action get_onCancel() { }
	// RVA: 0x2196840 VA: 0x75947ae840
	public Void set_onCancel(Action value) { }
	// RVA: 0x2196848 VA: 0x75947ae848
	public Void Init() { }
	// RVA: 0x21969c4 VA: 0x75947ae9c4
	public Void Show() { }
	// RVA: 0x2196a00 VA: 0x75947aea00
	public Void Hide() { }
	// RVA: 0x2196a3c VA: 0x75947aea3c
	public Void EventOnConfirmClicked() { }
	// RVA: 0x2196a58 VA: 0x75947aea58
	public Void EventOnCancelClicked() { }
	// RVA: 0x2196a74 VA: 0x75947aea74
	public Void .ctor() { }
}
```
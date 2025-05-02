# UINotifyViewHolder

**Namespace:** `Torappu.UI.Notification`


## Fields

- `UITextNotifyView _textNotify`

- `UITextNotifyView _lockNotify`

- `UITextNotifyView _unlockNotify`

- `UIMedalNotifyView _multiMedalNotify`

- `UIMedalNotifyView _singleMedalNotify`


## Properties

- `UITextNotifyView textNotifyView`

- `UITextNotifyView lockNotifyView`

- `UITextNotifyView unlockNotifyView`

- `UIMedalNotifyView multiMedalNotifyView`

- `UIMedalNotifyView singleMedalNotifyView`


## Methods

- `UITextNotifyView get_textNotifyView()`

- `UITextNotifyView get_lockNotifyView()`

- `UITextNotifyView get_unlockNotifyView()`

- `UIMedalNotifyView get_multiMedalNotifyView()`

- `UIMedalNotifyView get_singleMedalNotifyView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Notification
public class UINotifyViewHolder : ScriptableObject
{
	private UITextNotifyView _textNotify; // 0x18
	private UITextNotifyView _lockNotify; // 0x20
	private UITextNotifyView _unlockNotify; // 0x28
	private UIMedalNotifyView _multiMedalNotify; // 0x30
	private UIMedalNotifyView _singleMedalNotify; // 0x38

	public UITextNotifyView textNotifyView { get; }
	public UITextNotifyView lockNotifyView { get; }
	public UITextNotifyView unlockNotifyView { get; }
	public UIMedalNotifyView multiMedalNotifyView { get; }
	public UIMedalNotifyView singleMedalNotifyView { get; }

	// RVA: 0x27275c4 VA: 0x7594d3f5c4
	public UITextNotifyView get_textNotifyView() { }
	// RVA: 0x27275cc VA: 0x7594d3f5cc
	public UITextNotifyView get_lockNotifyView() { }
	// RVA: 0x27275d4 VA: 0x7594d3f5d4
	public UITextNotifyView get_unlockNotifyView() { }
	// RVA: 0x27275dc VA: 0x7594d3f5dc
	public UIMedalNotifyView get_multiMedalNotifyView() { }
	// RVA: 0x27275e4 VA: 0x7594d3f5e4
	public UIMedalNotifyView get_singleMedalNotifyView() { }
	// RVA: 0x27275ec VA: 0x7594d3f5ec
	public Void .ctor() { }
}
```
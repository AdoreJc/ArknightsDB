# TextInput

**Namespace:** ` `


## Fields

- `Boolean m_Multiline`


## Properties

- `TextField parentTextField`

- `Boolean multiline`


## Methods

- `TextField get_parentTextField()`

- `Boolean get_multiline()`

- `Void set_multiline(Boolean)`

- `Void SetTextAlign()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
private class TextInput : TextInputBase
{
	private Boolean m_Multiline; // 0x410

	private TextField parentTextField { get; }
	public Boolean multiline { get; set; }
	public override Boolean isPasswordField { set; }

	// RVA: 0x69c6858 VA: 0x7598fde858
	private TextField get_parentTextField() { }
	// RVA: 0x69c68d8 VA: 0x7598fde8d8
	public Boolean get_multiline() { }
	// RVA: 0x69c5fdc VA: 0x7598fddfdc
	public Void set_multiline(Boolean value) { }
	// RVA: 0x69c68e0 VA: 0x7598fde8e0
	private Void SetTextAlign() { }
	// RVA: 0x69c6980 VA: 0x7598fde980
	public override Void set_isPasswordField(Boolean value) { }
	// RVA: 0x69c69dc VA: 0x7598fde9dc
	protected override String StringToValue(String str) { }
	// RVA: 0x69c69e4 VA: 0x7598fde9e4
	internal override Void SyncTextEngine() { }
	// RVA: 0x69c6a74 VA: 0x7598fdea74
	protected override Void ExecuteDefaultActionAtTarget(EventBase evt) { }
	// RVA: 0x69c71a4 VA: 0x7598fdf1a4
	protected override Void ExecuteDefaultAction(EventBase evt) { }
	// RVA: 0x69c62b8 VA: 0x7598fde2b8
	public Void .ctor() { }
}
```
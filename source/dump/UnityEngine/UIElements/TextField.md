# TextField

**Namespace:** `UnityEngine.UIElements`


## Properties

- `TextInput textInput`

- `Boolean multiline`


## Methods

- `TextInput get_textInput()`

- `Void set_multiline(Boolean)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class TextField : TextInputBaseField`1
{
	public static readonly String ussClassName; // 0x0
	public static readonly String labelUssClassName; // 0x8
	public static readonly String inputUssClassName; // 0x10

	private TextInput textInput { get; }
	public Boolean multiline { set; }
	public override String value { get; set; }

	// RVA: 0x69c5f38 VA: 0x7598fddf38
	private TextInput get_textInput() { }
	// RVA: 0x69c5fbc VA: 0x7598fddfbc
	public Void set_multiline(Boolean value) { }
	// RVA: 0x69c60a8 VA: 0x7598fde0a8
	public Void .ctor() { }
	// RVA: 0x69c60c0 VA: 0x7598fde0c0
	public Void .ctor(String label) { }
	// RVA: 0x69c60d4 VA: 0x7598fde0d4
	public Void .ctor(String label, Int32 maxLength, Boolean multiline, Boolean isPasswordField, Char maskChar) { }
	// RVA: 0x69c6300 VA: 0x7598fde300
	public override String get_value() { }
	// RVA: 0x69c6348 VA: 0x7598fde348
	public override Void set_value(String value) { }
	// RVA: 0x69c63ec VA: 0x7598fde3ec
	public override Void SetValueWithoutNotify(String newValue) { }
	// RVA: 0x69c6490 VA: 0x7598fde490
	internal override Void OnViewDataReady() { }
	// RVA: 0x69c6544 VA: 0x7598fde544
	protected override String ValueToString(String value) { }
	// RVA: 0x69c654c VA: 0x7598fde54c
	private static Void .cctor() { }
}
```
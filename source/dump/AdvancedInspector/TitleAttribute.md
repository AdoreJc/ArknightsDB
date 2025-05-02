# TitleAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `String message`

- `FontStyle style`

- `String methodName`


## Properties

- `String Message`

- `FontStyle Style`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `String get_Message()`

- `Void set_Message(String)`

- `FontStyle get_Style()`

- `Void set_Style(FontStyle)`

- `String get_MethodName()`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`

- `TitleAttribute Invoke(Int32, Object, Object)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class TitleAttribute : Attribute, IRuntimeAttribute`1, IRuntimeAttribute
{
	private String message; // 0x10
	private FontStyle style; // 0x18
	private String methodName; // 0x20
	private List`1 delegates; // 0x28

	public String Message { get; set; }
	public FontStyle Style { get; set; }
	public String MethodName { get; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b1b4cc VA: 0x75941334cc
	public String get_Message() { }
	// RVA: 0x1b1b4d4 VA: 0x75941334d4
	public Void set_Message(String value) { }
	// RVA: 0x1b1b4dc VA: 0x75941334dc
	public FontStyle get_Style() { }
	// RVA: 0x1b1b4e4 VA: 0x75941334e4
	public Void set_Style(FontStyle value) { }
	// RVA: 0x1b1b4ec VA: 0x75941334ec
	public String get_MethodName() { }
	// RVA: 0x1b1b4f4 VA: 0x75941334f4
	public Type get_Template() { }
	// RVA: 0x1b1b560 VA: 0x7594133560
	public Type get_TemplateStatic() { }
	// RVA: 0x1b1b5cc VA: 0x75941335cc
	public List`1 get_Delegates() { }
	// RVA: 0x1b1b5d4 VA: 0x75941335d4
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b1b5dc VA: 0x75941335dc
	public TitleAttribute Invoke(Int32 index, Object instance, Object value) { }
	// RVA: 0x1b1b9c8 VA: 0x75941339c8
	public Void .ctor(String methodName) { }
	// RVA: 0x1b1ba9c VA: 0x7594133a9c
	public Void .ctor(FontStyle style, String message) { }
	// RVA: 0x1b1bb7c VA: 0x7594133b7c
	public Void .ctor(Delegate method) { }
}
```
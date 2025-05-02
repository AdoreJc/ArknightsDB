# BackgroundAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `Color color`

- `String methodName`


## Properties

- `Color Color`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `Color get_Color()`

- `Void set_Color(Color)`

- `String get_MethodName()`

- `Void set_MethodName(String)`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`

- `Color Invoke(Int32, Object, Object)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class BackgroundAttribute : Attribute, IRuntimeAttribute`1, IRuntimeAttribute
{
	private Color color; // 0x10
	private String methodName; // 0x20
	private List`1 delegates; // 0x28

	public Color Color { get; set; }
	public String MethodName { get; set; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b11650 VA: 0x7594129650
	public Color get_Color() { }
	// RVA: 0x1b1165c VA: 0x759412965c
	public Void set_Color(Color value) { }
	// RVA: 0x1b11668 VA: 0x7594129668
	public String get_MethodName() { }
	// RVA: 0x1b11670 VA: 0x7594129670
	public Void set_MethodName(String value) { }
	// RVA: 0x1b11678 VA: 0x7594129678
	public Type get_Template() { }
	// RVA: 0x1b116e4 VA: 0x75941296e4
	public Type get_TemplateStatic() { }
	// RVA: 0x1b11750 VA: 0x7594129750
	public List`1 get_Delegates() { }
	// RVA: 0x1b11758 VA: 0x7594129758
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b11760 VA: 0x7594129760
	public Color Invoke(Int32 index, Object instance, Object value) { }
	// RVA: 0x1b11b8c VA: 0x7594129b8c
	public Void .ctor(String methodName) { }
	// RVA: 0x1b11c5c VA: 0x7594129c5c
	public Void .ctor(Delegate method) { }
	// RVA: 0x1b11da0 VA: 0x7594129da0
	public Void .ctor(Single r, Single g, Single b) { }
	// RVA: 0x1b11da8 VA: 0x7594129da8
	public Void .ctor(Single r, Single g, Single b, Single a) { }
}
```
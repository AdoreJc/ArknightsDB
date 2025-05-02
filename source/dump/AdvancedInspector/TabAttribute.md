# TabAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `Enum tab`

- `String methodName`


## Properties

- `Enum Tab`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `Enum get_Tab()`

- `Void set_Tab(Enum)`

- `String get_MethodName()`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`

- `Enum Invoke(Int32, Object, Object)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class TabAttribute : Attribute, IRuntimeAttribute`1, IRuntimeAttribute
{
	private Enum tab; // 0x10
	private String methodName; // 0x18
	private List`1 delegates; // 0x20

	public Enum Tab { get; set; }
	public String MethodName { get; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b1a898 VA: 0x7594132898
	public Enum get_Tab() { }
	// RVA: 0x1b1a8a0 VA: 0x75941328a0
	public Void set_Tab(Enum value) { }
	// RVA: 0x1b1a8a8 VA: 0x75941328a8
	public String get_MethodName() { }
	// RVA: 0x1b1a8b0 VA: 0x75941328b0
	public Type get_Template() { }
	// RVA: 0x1b1a91c VA: 0x759413291c
	public Type get_TemplateStatic() { }
	// RVA: 0x1b1a988 VA: 0x7594132988
	public List`1 get_Delegates() { }
	// RVA: 0x1b1a990 VA: 0x7594132990
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b1a998 VA: 0x7594132998
	public Enum Invoke(Int32 index, Object instance, Object value) { }
	// RVA: 0x1b1adb4 VA: 0x7594132db4
	public Void .ctor(Object tab) { }
	// RVA: 0x1b1aeec VA: 0x7594132eec
	public Void .ctor(String methodName) { }
}
```
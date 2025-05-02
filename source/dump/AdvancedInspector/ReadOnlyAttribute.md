# ReadOnlyAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `Boolean condition`

- `String methodName`


## Properties

- `Boolean Condition`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `Boolean get_Condition()`

- `Void set_Condition(Boolean)`

- `String get_MethodName()`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`

- `Boolean Invoke(Int32, Object, Object)`

- `Boolean IsReadOnly(Object[], Object[])`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class ReadOnlyAttribute : Attribute, IReadOnly, IListAttribute, IRuntimeAttribute`1, IRuntimeAttribute
{
	private Boolean condition; // 0x10
	private String methodName; // 0x18
	private List`1 delegates; // 0x20

	public Boolean Condition { get; set; }
	public String MethodName { get; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b18484 VA: 0x7594130484
	public Boolean get_Condition() { }
	// RVA: 0x1b1848c VA: 0x759413048c
	public Void set_Condition(Boolean value) { }
	// RVA: 0x1b18498 VA: 0x7594130498
	public String get_MethodName() { }
	// RVA: 0x1b184a0 VA: 0x75941304a0
	public Type get_Template() { }
	// RVA: 0x1b1850c VA: 0x759413050c
	public Type get_TemplateStatic() { }
	// RVA: 0x1b18578 VA: 0x7594130578
	public List`1 get_Delegates() { }
	// RVA: 0x1b18580 VA: 0x7594130580
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b18588 VA: 0x7594130588
	public Boolean Invoke(Int32 index, Object instance, Object value) { }
	// RVA: 0x1b189a0 VA: 0x75941309a0
	public Boolean IsReadOnly(Object[] instances, Object[] values) { }
	// RVA: 0x1b18ae8 VA: 0x7594130ae8
	public Void .ctor() { }
	// RVA: 0x1b18ba4 VA: 0x7594130ba4
	public Void .ctor(Boolean condition) { }
	// RVA: 0x1b18c70 VA: 0x7594130c70
	public Void .ctor(Delegate method) { }
	// RVA: 0x1b18c78 VA: 0x7594130c78
	public Void .ctor(Delegate method, Boolean condition) { }
	// RVA: 0x1b18dd0 VA: 0x7594130dd0
	public Void .ctor(String methodName) { }
	// RVA: 0x1b18dd8 VA: 0x7594130dd8
	public Void .ctor(String methodName, Boolean condition) { }
}
```
# RuntimeResolveAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `String methodName`


## Properties

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `Type GetType(Object[], Object[])`

- `String get_MethodName()`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`

- `Type Invoke(Int32, Object, Object)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class RuntimeResolveAttribute : Attribute, IListAttribute, IRuntimeAttribute`1, IRuntimeAttribute, IRuntimeType
{
	private String methodName; // 0x10
	private List`1 delegates; // 0x18

	public String MethodName { get; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b19b88 VA: 0x7594131b88
	public Type GetType(Object[] instances, Object[] values) { }
	// RVA: 0x1b1a10c VA: 0x759413210c
	public String get_MethodName() { }
	// RVA: 0x1b1a114 VA: 0x7594132114
	public Type get_Template() { }
	// RVA: 0x1b1a180 VA: 0x7594132180
	public Type get_TemplateStatic() { }
	// RVA: 0x1b1a1ec VA: 0x75941321ec
	public List`1 get_Delegates() { }
	// RVA: 0x1b1a1f4 VA: 0x75941321f4
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b19d1c VA: 0x7594131d1c
	public Type Invoke(Int32 index, Object instance, Object value) { }
	// RVA: 0x1b1a1fc VA: 0x75941321fc
	public Void .ctor() { }
	// RVA: 0x1b1a2b0 VA: 0x75941322b0
	public Void .ctor(String methodName) { }
	// RVA: 0x1b1a37c VA: 0x759413237c
	public Void .ctor(Delegate method) { }
}
```
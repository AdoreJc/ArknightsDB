# ConstructorAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `String methodName`


## Properties

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `String get_MethodName()`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`

- `Object Invoke(Int32, Object, Object)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class ConstructorAttribute : Attribute, IRuntimeAttribute`1, IRuntimeAttribute
{
	private String methodName; // 0x10
	private List`1 delegates; // 0x18

	public String MethodName { get; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b13324 VA: 0x759412b324
	public String get_MethodName() { }
	// RVA: 0x1b1332c VA: 0x759412b32c
	public Type get_Template() { }
	// RVA: 0x1b13398 VA: 0x759412b398
	public Type get_TemplateStatic() { }
	// RVA: 0x1b13404 VA: 0x759412b404
	public List`1 get_Delegates() { }
	// RVA: 0x1b1340c VA: 0x759412b40c
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b13414 VA: 0x759412b414
	public Object Invoke(Int32 index, Object instance, Object value) { }
	// RVA: 0x1b137b4 VA: 0x759412b7b4
	public Void .ctor(String methodName) { }
	// RVA: 0x1b13880 VA: 0x759412b880
	public Void .ctor(Delegate method) { }
}
```
# RestrictAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `RestrictDisplay display`

- `Int32 maxItemsPerRow`

- `String methodName`


## Properties

- `RestrictDisplay Display`

- `Int32 MaxItemsPerRow`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `RestrictDisplay get_Display()`

- `Void set_Display(RestrictDisplay)`

- `Int32 get_MaxItemsPerRow()`

- `Void set_MaxItemsPerRow(Int32)`

- `IList GetRestricted(Object[], Object[])`

- `RestrictDisplay GetDisplay(Object[], Object[])`

- `Int32 GetItemsPerRow(Object[], Object[])`

- `String get_MethodName()`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class RestrictAttribute : Attribute, IRestrict, IListAttribute, IRuntimeAttribute
{
	private RestrictDisplay display; // 0x10
	private Int32 maxItemsPerRow; // 0x14
	private String methodName; // 0x18
	private List`1 delegates; // 0x20

	public RestrictDisplay Display { get; set; }
	public Int32 MaxItemsPerRow { get; set; }
	public String MethodName { get; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b19194 VA: 0x7594131194
	public RestrictDisplay get_Display() { }
	// RVA: 0x1b1919c VA: 0x759413119c
	public Void set_Display(RestrictDisplay value) { }
	// RVA: 0x1b191a4 VA: 0x75941311a4
	public Int32 get_MaxItemsPerRow() { }
	// RVA: 0x1b191ac VA: 0x75941311ac
	public Void set_MaxItemsPerRow(Int32 value) { }
	// RVA: 0x1b191b4 VA: 0x75941311b4
	public IList GetRestricted(Object[] instances, Object[] values) { }
	// RVA: 0x1b195a4 VA: 0x75941315a4
	public RestrictDisplay GetDisplay(Object[] instances, Object[] values) { }
	// RVA: 0x1b195ac VA: 0x75941315ac
	public Int32 GetItemsPerRow(Object[] instances, Object[] values) { }
	// RVA: 0x1b195b4 VA: 0x75941315b4
	public String get_MethodName() { }
	// RVA: 0x1b195bc VA: 0x75941315bc
	public Type get_Template() { }
	// RVA: 0x1b19628 VA: 0x7594131628
	public Type get_TemplateStatic() { }
	// RVA: 0x1b19694 VA: 0x7594131694
	public List`1 get_Delegates() { }
	// RVA: 0x1b1969c VA: 0x759413169c
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b196a4 VA: 0x75941316a4
	public Void .ctor(String methodName) { }
	// RVA: 0x1b196ac VA: 0x75941316ac
	public Void .ctor(String methodName, RestrictDisplay display) { }
	// RVA: 0x1b19794 VA: 0x7594131794
	public Void .ctor(Delegate method) { }
	// RVA: 0x1b1979c VA: 0x759413179c
	public Void .ctor(Delegate method, RestrictDisplay display) { }
}
```
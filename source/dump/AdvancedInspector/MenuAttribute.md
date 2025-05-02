# MenuAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `String menuItemName`

- `String methodName`


## Properties

- `String MenuItemName`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `String get_MenuItemName()`

- `String get_MethodName()`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`

- `Void Invoke(Int32, Object, Object)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class MenuAttribute : Attribute, IListAttribute, IMenu, IRuntimeAttribute
{
	private String menuItemName; // 0x10
	private String methodName; // 0x18
	private List`1 delegates; // 0x20

	public String MenuItemName { get; }
	public String MethodName { get; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b17a30 VA: 0x759412fa30
	public String get_MenuItemName() { }
	// RVA: 0x1b17a38 VA: 0x759412fa38
	public String get_MethodName() { }
	// RVA: 0x1b17a40 VA: 0x759412fa40
	public Type get_Template() { }
	// RVA: 0x1b17aac VA: 0x759412faac
	public Type get_TemplateStatic() { }
	// RVA: 0x1b17b18 VA: 0x759412fb18
	public List`1 get_Delegates() { }
	// RVA: 0x1b17b20 VA: 0x759412fb20
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b17b28 VA: 0x759412fb28
	public Void Invoke(Int32 index, Object instance, Object value) { }
	// RVA: 0x1b17ec4 VA: 0x759412fec4
	public Void .ctor(String menuItemName, String methodName) { }
}
```
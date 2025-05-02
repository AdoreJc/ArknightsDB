# CollectionAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `Int32 size`

- `Boolean sortable`

- `CollectionDisplay display`

- `Int32 maxDisplayedItems`

- `Int32 maxItemsPerRow`

- `Boolean alwaysExpanded`

- `Boolean expandElements`

- `Type enumType`

- `String methodName`


## Properties

- `Int32 Size`

- `Boolean Sortable`

- `CollectionDisplay Display`

- `Int32 MaxDisplayedItems`

- `Int32 MaxItemsPerRow`

- `Boolean AlwaysExpanded`

- `Boolean ExpandElements`

- `Type EnumType`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `Int32 get_Size()`

- `Void set_Size(Int32)`

- `Boolean get_Sortable()`

- `Void set_Sortable(Boolean)`

- `CollectionDisplay get_Display()`

- `Void set_Display(CollectionDisplay)`

- `Int32 get_MaxDisplayedItems()`

- `Void set_MaxDisplayedItems(Int32)`

- `Int32 get_MaxItemsPerRow()`

- `Void set_MaxItemsPerRow(Int32)`

- `Boolean get_AlwaysExpanded()`

- `Void set_AlwaysExpanded(Boolean)`

- `Boolean get_ExpandElements()`

- `Void set_ExpandElements(Boolean)`

- `Type get_EnumType()`

- `Void set_EnumType(Type)`

- `String get_MethodName()`

- `Void set_MethodName(String)`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class CollectionAttribute : Attribute, IListAttribute, IRuntimeAttribute`1, IRuntimeAttribute
{
	private Int32 size; // 0x10
	private Boolean sortable; // 0x14
	private CollectionDisplay display; // 0x18
	private Int32 maxDisplayedItems; // 0x1c
	private Int32 maxItemsPerRow; // 0x20
	private Boolean alwaysExpanded; // 0x24
	private Boolean expandElements; // 0x25
	private Type enumType; // 0x28
	private String methodName; // 0x30
	private List`1 delegates; // 0x38

	public Int32 Size { get; set; }
	public Boolean Sortable { get; set; }
	public CollectionDisplay Display { get; set; }
	public Int32 MaxDisplayedItems { get; set; }
	public Int32 MaxItemsPerRow { get; set; }
	public Boolean AlwaysExpanded { get; set; }
	public Boolean ExpandElements { get; set; }
	public Type EnumType { get; set; }
	public String MethodName { get; set; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b1216c VA: 0x759412a16c
	public Int32 get_Size() { }
	// RVA: 0x1b12174 VA: 0x759412a174
	public Void set_Size(Int32 value) { }
	// RVA: 0x1b1217c VA: 0x759412a17c
	public Boolean get_Sortable() { }
	// RVA: 0x1b12184 VA: 0x759412a184
	public Void set_Sortable(Boolean value) { }
	// RVA: 0x1b12190 VA: 0x759412a190
	public CollectionDisplay get_Display() { }
	// RVA: 0x1b12198 VA: 0x759412a198
	public Void set_Display(CollectionDisplay value) { }
	// RVA: 0x1b121a0 VA: 0x759412a1a0
	public Int32 get_MaxDisplayedItems() { }
	// RVA: 0x1b121a8 VA: 0x759412a1a8
	public Void set_MaxDisplayedItems(Int32 value) { }
	// RVA: 0x1b121b0 VA: 0x759412a1b0
	public Int32 get_MaxItemsPerRow() { }
	// RVA: 0x1b121b8 VA: 0x759412a1b8
	public Void set_MaxItemsPerRow(Int32 value) { }
	// RVA: 0x1b121c0 VA: 0x759412a1c0
	public Boolean get_AlwaysExpanded() { }
	// RVA: 0x1b121c8 VA: 0x759412a1c8
	public Void set_AlwaysExpanded(Boolean value) { }
	// RVA: 0x1b121d4 VA: 0x759412a1d4
	public Boolean get_ExpandElements() { }
	// RVA: 0x1b121dc VA: 0x759412a1dc
	public Void set_ExpandElements(Boolean value) { }
	// RVA: 0x1b121e8 VA: 0x759412a1e8
	public Type get_EnumType() { }
	// RVA: 0x1b121f0 VA: 0x759412a1f0
	public Void set_EnumType(Type value) { }
	// RVA: 0x1b12544 VA: 0x759412a544
	public String get_MethodName() { }
	// RVA: 0x1b1254c VA: 0x759412a54c
	public Void set_MethodName(String value) { }
	// RVA: 0x1b12554 VA: 0x759412a554
	public Type get_Template() { }
	// RVA: 0x1b125c0 VA: 0x759412a5c0
	public Type get_TemplateStatic() { }
	// RVA: 0x1b1262c VA: 0x759412a62c
	public List`1 get_Delegates() { }
	// RVA: 0x1b12634 VA: 0x759412a634
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b1263c VA: 0x759412a63c
	public String[] Invoke(Int32 index, Object instance, Object value) { }
	// RVA: 0x1b12a64 VA: 0x759412aa64
	public Void .ctor() { }
	// RVA: 0x1b12b34 VA: 0x759412ab34
	public Void .ctor(Int32 size) { }
	// RVA: 0x1b12ba0 VA: 0x759412aba0
	public Void .ctor(Type enumType) { }
	// RVA: 0x1b12bb8 VA: 0x759412abb8
	public Void .ctor(Boolean sortable) { }
	// RVA: 0x1b12bc4 VA: 0x759412abc4
	public Void .ctor(String methodName) { }
	// RVA: 0x1b12cec VA: 0x759412acec
	public Void .ctor(CollectionDisplay display) { }
	// RVA: 0x1b12b3c VA: 0x759412ab3c
	public Void .ctor(Int32 size, Boolean sortable) { }
	// RVA: 0x1b12bac VA: 0x759412abac
	public Void .ctor(Type enumType, Boolean sortable) { }
	// RVA: 0x1b12e50 VA: 0x759412ae50
	public Void .ctor(Int32 size, CollectionDisplay display) { }
	// RVA: 0x1b12eb4 VA: 0x759412aeb4
	public Void .ctor(Type enumType, CollectionDisplay display) { }
	// RVA: 0x1b12bd4 VA: 0x759412abd4
	public Void .ctor(String methodName, Int32 size, Boolean sortable, CollectionDisplay display) { }
	// RVA: 0x1b12d4c VA: 0x759412ad4c
	public Void .ctor(Type enumType, Boolean sortable, CollectionDisplay display) { }
	// RVA: 0x1b12ec0 VA: 0x759412aec0
	public Void .ctor(Delegate method) { }
	// RVA: 0x1b13060 VA: 0x759412b060
	public Void .ctor(Delegate method, Int32 size) { }
	// RVA: 0x1b1306c VA: 0x759412b06c
	public Void .ctor(Delegate method, Boolean sortable) { }
	// RVA: 0x1b1307c VA: 0x759412b07c
	public Void .ctor(Delegate method, CollectionDisplay display) { }
	// RVA: 0x1b12ed0 VA: 0x759412aed0
	public Void .ctor(Delegate method, Int32 size, Boolean sortable, CollectionDisplay display) { }
}
```
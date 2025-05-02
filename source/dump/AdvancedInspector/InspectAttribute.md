# InspectAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `InspectorLevel level`

- `Boolean condition`

- `Int32 priority`

- `String methodName`


## Properties

- `InspectorLevel Level`

- `Boolean Condition`

- `Int32 Priority`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `InspectorLevel get_Level()`

- `Void set_Level(InspectorLevel)`

- `Boolean get_Condition()`

- `Void set_Condition(Boolean)`

- `Int32 get_Priority()`

- `Void set_Priority(Int32)`

- `Boolean IsItemVisible(Object[], Object[])`

- `InspectorLevel GetItemLevel(Object[], Object[])`

- `Int32 GetItemPriority(Object[], Object[])`

- `String get_MethodName()`

- `Void set_MethodName(String)`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class InspectAttribute : Attribute, IRuntimeAttribute, IVisibility
{
	private InspectorLevel level; // 0x10
	private Boolean condition; // 0x14
	private Int32 priority; // 0x18
	private String methodName; // 0x20
	private List`1 delegates; // 0x28

	public InspectorLevel Level { get; set; }
	public Boolean Condition { get; set; }
	public Int32 Priority { get; set; }
	public String MethodName { get; set; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b16a10 VA: 0x759412ea10
	public InspectorLevel get_Level() { }
	// RVA: 0x1b16a18 VA: 0x759412ea18
	public Void set_Level(InspectorLevel value) { }
	// RVA: 0x1b16a20 VA: 0x759412ea20
	public Boolean get_Condition() { }
	// RVA: 0x1b16a28 VA: 0x759412ea28
	public Void set_Condition(Boolean value) { }
	// RVA: 0x1b16a34 VA: 0x759412ea34
	public Int32 get_Priority() { }
	// RVA: 0x1b16a3c VA: 0x759412ea3c
	public Void set_Priority(Int32 value) { }
	// RVA: 0x1b16a44 VA: 0x759412ea44
	public Boolean IsItemVisible(Object[] instances, Object[] values) { }
	// RVA: 0x1b17174 VA: 0x759412f174
	public InspectorLevel GetItemLevel(Object[] parents, Object[] values) { }
	// RVA: 0x1b1717c VA: 0x759412f17c
	public Int32 GetItemPriority(Object[] parents, Object[] values) { }
	// RVA: 0x1b17184 VA: 0x759412f184
	public String get_MethodName() { }
	// RVA: 0x1b1718c VA: 0x759412f18c
	public Void set_MethodName(String value) { }
	// RVA: 0x1b17194 VA: 0x759412f194
	public Type get_Template() { }
	// RVA: 0x1b17200 VA: 0x759412f200
	public Type get_TemplateStatic() { }
	// RVA: 0x1b1726c VA: 0x759412f26c
	public List`1 get_Delegates() { }
	// RVA: 0x1b17274 VA: 0x759412f274
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b1727c VA: 0x759412f27c
	public Void .ctor() { }
	// RVA: 0x1b173d4 VA: 0x759412f3d4
	public Void .ctor(Int32 priority) { }
	// RVA: 0x1b17434 VA: 0x759412f434
	public Void .ctor(InspectorLevel level) { }
	// RVA: 0x1b17494 VA: 0x759412f494
	public Void .ctor(InspectorLevel level, Int32 priority) { }
	// RVA: 0x1b174f8 VA: 0x759412f4f8
	public Void .ctor(InspectorLevel level, String methodName) { }
	// RVA: 0x1b17504 VA: 0x759412f504
	public Void .ctor(InspectorLevel level, String methodName, Int32 priority) { }
	// RVA: 0x1b17510 VA: 0x759412f510
	public Void .ctor(InspectorLevel level, String methodName, Boolean condition) { }
	// RVA: 0x1b1751c VA: 0x759412f51c
	public Void .ctor(String methodName) { }
	// RVA: 0x1b17530 VA: 0x759412f530
	public Void .ctor(String methodName, Int32 priority) { }
	// RVA: 0x1b17544 VA: 0x759412f544
	public Void .ctor(String methodName, Boolean condition) { }
	// RVA: 0x1b1755c VA: 0x759412f55c
	public Void .ctor(String methodName, Boolean condition, Int32 priority) { }
	// RVA: 0x1b172d0 VA: 0x759412f2d0
	public Void .ctor(InspectorLevel level, String methodName, Boolean condition, Int32 priority) { }
	// RVA: 0x1b17574 VA: 0x759412f574
	public Void .ctor(Delegate method) { }
	// RVA: 0x1b17704 VA: 0x759412f704
	public Void .ctor(Delegate method, Int32 priority) { }
	// RVA: 0x1b17718 VA: 0x759412f718
	public Void .ctor(Delegate method, Boolean condition) { }
	// RVA: 0x1b17730 VA: 0x759412f730
	public Void .ctor(Delegate method, Boolean condition, Int32 priority) { }
	// RVA: 0x1b17748 VA: 0x759412f748
	public Void .ctor(InspectorLevel level, Delegate method) { }
	// RVA: 0x1b17754 VA: 0x759412f754
	public Void .ctor(InspectorLevel level, Delegate method, Int32 priority) { }
	// RVA: 0x1b17588 VA: 0x759412f588
	public Void .ctor(InspectorLevel level, Delegate method, Boolean condition, Int32 priority) { }
}
```
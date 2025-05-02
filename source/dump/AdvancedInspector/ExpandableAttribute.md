# ExpandableAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `Boolean expanded`

- `Boolean expandable`

- `Boolean alwaysExpanded`


## Properties

- `Boolean Expanded`

- `Boolean Expandable`

- `Boolean AlwaysExpanded`


## Methods

- `Boolean get_Expanded()`

- `Void set_Expanded(Boolean)`

- `Boolean get_Expandable()`

- `Void set_Expandable(Boolean)`

- `Boolean get_AlwaysExpanded()`

- `Void set_AlwaysExpanded(Boolean)`

- `Boolean IsExpandable(Object[], Object[])`

- `Boolean IsExpanded(Object[], Object[])`

- `Boolean IsAlwaysExpanded(Object[], Object[])`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class ExpandableAttribute : Attribute, IExpandable, IListAttribute
{
	private Boolean expanded; // 0x10
	private Boolean expandable; // 0x11
	private Boolean alwaysExpanded; // 0x12

	public Boolean Expanded { get; set; }
	public Boolean Expandable { get; set; }
	public Boolean AlwaysExpanded { get; set; }

	// RVA: 0x1b15160 VA: 0x759412d160
	public Boolean get_Expanded() { }
	// RVA: 0x1b15168 VA: 0x759412d168
	public Void set_Expanded(Boolean value) { }
	// RVA: 0x1b15174 VA: 0x759412d174
	public Boolean get_Expandable() { }
	// RVA: 0x1b1517c VA: 0x759412d17c
	public Void set_Expandable(Boolean value) { }
	// RVA: 0x1b15188 VA: 0x759412d188
	public Boolean get_AlwaysExpanded() { }
	// RVA: 0x1b15190 VA: 0x759412d190
	public Void set_AlwaysExpanded(Boolean value) { }
	// RVA: 0x1b1519c VA: 0x759412d19c
	public Void .ctor() { }
	// RVA: 0x1b151ac VA: 0x759412d1ac
	public Void .ctor(Boolean expandable) { }
	// RVA: 0x1b151dc VA: 0x759412d1dc
	public Void .ctor(Boolean expandable, Boolean expanded) { }
	// RVA: 0x1b15214 VA: 0x759412d214
	public Boolean IsExpandable(Object[] instances, Object[] values) { }
	// RVA: 0x1b1521c VA: 0x759412d21c
	public Boolean IsExpanded(Object[] instances, Object[] values) { }
	// RVA: 0x1b15224 VA: 0x759412d224
	public Boolean IsAlwaysExpanded(Object[] instances, Object[] values) { }
}
```
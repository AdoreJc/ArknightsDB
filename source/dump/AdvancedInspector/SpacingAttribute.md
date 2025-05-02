# SpacingAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `Int32 before`

- `Int32 after`


## Properties

- `Int32 Before`

- `Int32 After`


## Methods

- `Int32 get_Before()`

- `Void set_Before(Int32)`

- `Int32 get_After()`

- `Void set_After(Int32)`

- `Int32 GetAfter(Object[], Object[])`

- `Int32 GetBefore(Object[], Object[])`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class SpacingAttribute : Attribute, ISpacing
{
	private Int32 before; // 0x10
	private Int32 after; // 0x14

	public Int32 Before { get; set; }
	public Int32 After { get; set; }

	// RVA: 0x1b1a754 VA: 0x7594132754
	public Int32 get_Before() { }
	// RVA: 0x1b1a75c VA: 0x759413275c
	public Void set_Before(Int32 value) { }
	// RVA: 0x1b1a764 VA: 0x7594132764
	public Int32 get_After() { }
	// RVA: 0x1b1a76c VA: 0x759413276c
	public Void set_After(Int32 value) { }
	// RVA: 0x1b1a774 VA: 0x7594132774
	public Void .ctor() { }
	// RVA: 0x1b1a77c VA: 0x759413277c
	public Void .ctor(Int32 after) { }
	// RVA: 0x1b1a7a4 VA: 0x75941327a4
	public Void .ctor(Int32 before, Int32 after) { }
	// RVA: 0x1b1a7d0 VA: 0x75941327d0
	public Int32 GetAfter(Object[] instances, Object[] values) { }
	// RVA: 0x1b1a7d8 VA: 0x75941327d8
	public Int32 GetBefore(Object[] instances, Object[] values) { }
}
```
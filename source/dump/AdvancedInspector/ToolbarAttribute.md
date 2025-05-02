# ToolbarAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `String name`

- `String style`

- `Boolean label`

- `Boolean flexible`

- `Int32 priority`


## Properties

- `String Name`

- `String Style`

- `Boolean Label`

- `Boolean Flexible`

- `Int32 Priority`


## Methods

- `String get_Name()`

- `Void set_Name(String)`

- `String get_Style()`

- `Void set_Style(String)`

- `Boolean get_Label()`

- `Void set_Label(Boolean)`

- `Boolean get_Flexible()`

- `Void set_Flexible(Boolean)`

- `Int32 get_Priority()`

- `Void set_Priority(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class ToolbarAttribute : Attribute
{
	public const String ToolbarStyle; // 0x0
	private String name; // 0x10
	private String style; // 0x18
	private Boolean label; // 0x20
	private Boolean flexible; // 0x21
	private Int32 priority; // 0x24

	public String Name { get; set; }
	public String Style { get; set; }
	public Boolean Label { get; set; }
	public Boolean Flexible { get; set; }
	public Int32 Priority { get; set; }

	// RVA: 0x1b1bf5c VA: 0x7594133f5c
	public String get_Name() { }
	// RVA: 0x1b1bf64 VA: 0x7594133f64
	public Void set_Name(String value) { }
	// RVA: 0x1b1bf6c VA: 0x7594133f6c
	public String get_Style() { }
	// RVA: 0x1b1bf74 VA: 0x7594133f74
	public Void set_Style(String value) { }
	// RVA: 0x1b1bf7c VA: 0x7594133f7c
	public Boolean get_Label() { }
	// RVA: 0x1b1bf84 VA: 0x7594133f84
	public Void set_Label(Boolean value) { }
	// RVA: 0x1b1bf90 VA: 0x7594133f90
	public Boolean get_Flexible() { }
	// RVA: 0x1b1bf98 VA: 0x7594133f98
	public Void set_Flexible(Boolean value) { }
	// RVA: 0x1b1bfa4 VA: 0x7594133fa4
	public Int32 get_Priority() { }
	// RVA: 0x1b1bfac VA: 0x7594133fac
	public Void set_Priority(Int32 value) { }
	// RVA: 0x1b1bfb4 VA: 0x7594133fb4
	public Void .ctor(String name) { }
	// RVA: 0x1b1c0e4 VA: 0x75941340e4
	public Void .ctor(String name, Int32 priority) { }
	// RVA: 0x1b1c14c VA: 0x759413414c
	public Void .ctor(String name, String style) { }
	// RVA: 0x1b1c15c VA: 0x759413415c
	public Void .ctor(String name, String style, Int32 priority) { }
	// RVA: 0x1b1c16c VA: 0x759413416c
	public Void .ctor(String name, Boolean label) { }
	// RVA: 0x1b1c1d4 VA: 0x75941341d4
	public Void .ctor(String name, Boolean label, Int32 priority) { }
	// RVA: 0x1b1c248 VA: 0x7594134248
	public Void .ctor(String name, String style, Boolean label) { }
	// RVA: 0x1b1c258 VA: 0x7594134258
	public Void .ctor(String name, String style, Boolean label, Int32 priority) { }
	// RVA: 0x1b1c268 VA: 0x7594134268
	public Void .ctor(String name, String style, Boolean label, Boolean flexible) { }
	// RVA: 0x1b1c018 VA: 0x7594134018
	public Void .ctor(String name, String style, Boolean label, Boolean flexible, Int32 priority) { }
}
```
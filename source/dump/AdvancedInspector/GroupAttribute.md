# GroupAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `String name`

- `String description`

- `String style`

- `Int32 priority`

- `Boolean expandable`

- `Color color`


## Properties

- `String Name`

- `String Description`

- `String Style`

- `Int32 Priority`

- `Boolean Expandable`

- `Color Color`


## Methods

- `String get_Name()`

- `Void set_Name(String)`

- `String get_Description()`

- `Void set_Description(String)`

- `String get_Style()`

- `Void set_Style(String)`

- `Int32 get_Priority()`

- `Void set_Priority(Int32)`

- `Boolean get_Expandable()`

- `Void set_Expandable(Boolean)`

- `Color get_Color()`

- `Void set_Color(Color)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class GroupAttribute : Attribute
{
	private String name; // 0x10
	private String description; // 0x18
	private String style; // 0x20
	private Int32 priority; // 0x28
	private Boolean expandable; // 0x2c
	private Color color; // 0x30

	public String Name { get; set; }
	public String Description { get; set; }
	public String Style { get; set; }
	public Int32 Priority { get; set; }
	public Boolean Expandable { get; set; }
	public Color Color { get; set; }

	// RVA: 0x1b152c4 VA: 0x759412d2c4
	public String get_Name() { }
	// RVA: 0x1b152cc VA: 0x759412d2cc
	public Void set_Name(String value) { }
	// RVA: 0x1b152d4 VA: 0x759412d2d4
	public String get_Description() { }
	// RVA: 0x1b152dc VA: 0x759412d2dc
	public Void set_Description(String value) { }
	// RVA: 0x1b152e4 VA: 0x759412d2e4
	public String get_Style() { }
	// RVA: 0x1b152ec VA: 0x759412d2ec
	public Void set_Style(String value) { }
	// RVA: 0x1b152f4 VA: 0x759412d2f4
	public Int32 get_Priority() { }
	// RVA: 0x1b152fc VA: 0x759412d2fc
	public Void set_Priority(Int32 value) { }
	// RVA: 0x1b15304 VA: 0x759412d304
	public Boolean get_Expandable() { }
	// RVA: 0x1b1530c VA: 0x759412d30c
	public Void set_Expandable(Boolean value) { }
	// RVA: 0x1b15318 VA: 0x759412d318
	public Color get_Color() { }
	// RVA: 0x1b15324 VA: 0x759412d324
	public Void set_Color(Color value) { }
	// RVA: 0x1b15330 VA: 0x759412d330
	public Void .ctor(String name) { }
	// RVA: 0x1b1540c VA: 0x759412d40c
	public Void .ctor(String name, Int32 priority) { }
	// RVA: 0x1b1546c VA: 0x759412d46c
	public Void .ctor(String name, String style) { }
	// RVA: 0x1b15474 VA: 0x759412d474
	public Void .ctor(String name, Single r, Single g, Single b) { }
	// RVA: 0x1b15618 VA: 0x759412d618
	public Void .ctor(String name, Single r, Single g, Single b, Single a) { }
	// RVA: 0x1b1538c VA: 0x759412d38c
	public Void .ctor(String name, String style, Int32 priority) { }
	// RVA: 0x1b156a8 VA: 0x759412d6a8
	public Void .ctor(String name, String style, Single r, Single g, Single b) { }
	// RVA: 0x1b15738 VA: 0x759412d738
	public Void .ctor(String name, String style, Single r, Single g, Single b, Single a) { }
	// RVA: 0x1b157cc VA: 0x759412d7cc
	public Void .ctor(String name, String style, Int32 priority, Single r, Single g, Single b) { }
	// RVA: 0x1b15868 VA: 0x759412d868
	public Void .ctor(String name, String style, Int32 priority, Single r, Single g, Single b, Single a) { }
	// RVA: 0x1b15500 VA: 0x759412d500
	public Void .ctor(String name, String description, String style, Int32 priority, Single r, Single g, Single b, Single a) { }
}
```
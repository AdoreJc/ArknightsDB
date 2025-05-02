# StyleAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `String style`

- `Boolean label`


## Properties

- `String Style`

- `Boolean Label`


## Methods

- `String get_Style()`

- `Void set_Style(String)`

- `Boolean get_Label()`

- `Void set_Label(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class StyleAttribute : Attribute
{
	private String style; // 0x10
	private Boolean label; // 0x18

	public String Style { get; set; }
	public Boolean Label { get; set; }

	// RVA: 0x1b1a7e0 VA: 0x75941327e0
	public String get_Style() { }
	// RVA: 0x1b1a7e8 VA: 0x75941327e8
	public Void set_Style(String value) { }
	// RVA: 0x1b1a7f0 VA: 0x75941327f0
	public Boolean get_Label() { }
	// RVA: 0x1b1a7f8 VA: 0x75941327f8
	public Void set_Label(Boolean value) { }
	// RVA: 0x1b1a804 VA: 0x7594132804
	public Void .ctor(String style) { }
	// RVA: 0x1b1a80c VA: 0x759413280c
	public Void .ctor(String style, Boolean label) { }
}
```
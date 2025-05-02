# EnumAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `Boolean masked`

- `EnumDisplay display`

- `Int32 maxItemsPerRow`


## Properties

- `Boolean Masked`

- `EnumDisplay Display`

- `Int32 MaxItemsPerRow`


## Methods

- `Boolean get_Masked()`

- `Void set_Masked(Boolean)`

- `EnumDisplay get_Display()`

- `Void set_Display(EnumDisplay)`

- `Int32 get_MaxItemsPerRow()`

- `Void set_MaxItemsPerRow(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class EnumAttribute : Attribute, IListAttribute
{
	private Boolean masked; // 0x10
	private EnumDisplay display; // 0x14
	private Int32 maxItemsPerRow; // 0x18

	public Boolean Masked { get; set; }
	public EnumDisplay Display { get; set; }
	public Int32 MaxItemsPerRow { get; set; }

	// RVA: 0x1b15094 VA: 0x759412d094
	public Boolean get_Masked() { }
	// RVA: 0x1b1509c VA: 0x759412d09c
	public Void set_Masked(Boolean value) { }
	// RVA: 0x1b150a8 VA: 0x759412d0a8
	public EnumDisplay get_Display() { }
	// RVA: 0x1b150b0 VA: 0x759412d0b0
	public Void set_Display(EnumDisplay value) { }
	// RVA: 0x1b150b8 VA: 0x759412d0b8
	public Int32 get_MaxItemsPerRow() { }
	// RVA: 0x1b150c0 VA: 0x759412d0c0
	public Void set_MaxItemsPerRow(Int32 value) { }
	// RVA: 0x1b150c8 VA: 0x759412d0c8
	public Void .ctor(Boolean masked) { }
	// RVA: 0x1b150f8 VA: 0x759412d0f8
	public Void .ctor(EnumDisplay display) { }
	// RVA: 0x1b15128 VA: 0x759412d128
	public Void .ctor(Boolean masked, EnumDisplay display) { }
}
```
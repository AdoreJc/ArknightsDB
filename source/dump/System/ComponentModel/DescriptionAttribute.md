# DescriptionAttribute

**Namespace:** `System.ComponentModel`


## Fields

- `String <DescriptionValue>k__BackingField`


## Properties

- `String DescriptionValue`


## Methods

- `String get_DescriptionValue()`

- `Void set_DescriptionValue(String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class DescriptionAttribute : Attribute
{
	public static readonly DescriptionAttribute Default; // 0x0
	private String <DescriptionValue>k__BackingField; // 0x10

	public virtual String Description { get; }
	protected String DescriptionValue { get; set; }

	// RVA: 0x63b1b7c VA: 0x75989c9b7c
	public Void .ctor() { }
	// RVA: 0x63b1be0 VA: 0x75989c9be0
	public Void .ctor(String description) { }
	// RVA: 0x63b1c10 VA: 0x75989c9c10
	public virtual String get_Description() { }
	// RVA: 0x63b1c18 VA: 0x75989c9c18
	protected String get_DescriptionValue() { }
	// RVA: 0x63b1c20 VA: 0x75989c9c20
	protected Void set_DescriptionValue(String value) { }
	// RVA: 0x63b1c28 VA: 0x75989c9c28
	public override Boolean Equals(Object obj) { }
	// RVA: 0x63b1cf4 VA: 0x75989c9cf4
	public override Int32 GetHashCode() { }
	// RVA: 0x63b1d1c VA: 0x75989c9d1c
	public override Boolean IsDefaultAttribute() { }
	// RVA: 0x63b1d84 VA: 0x75989c9d84
	private static Void .cctor() { }
}
```
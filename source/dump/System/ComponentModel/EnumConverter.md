# EnumConverter

**Namespace:** `System.ComponentModel`


## Fields

- `StandardValuesCollection values`

- `Type type`


## Properties

- `Type EnumType`

- `StandardValuesCollection Values`


## Methods

- `Type get_EnumType()`

- `StandardValuesCollection get_Values()`

- `Void set_Values(StandardValuesCollection)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class EnumConverter : TypeConverter
{
	private StandardValuesCollection values; // 0x10
	private Type type; // 0x18

	protected Type EnumType { get; }
	protected StandardValuesCollection Values { get; set; }
	protected virtual IComparer Comparer { get; }

	// RVA: 0x63e05e8 VA: 0x75989f85e8
	public Void .ctor(Type type) { }
	// RVA: 0x63e0618 VA: 0x75989f8618
	protected Type get_EnumType() { }
	// RVA: 0x63e0620 VA: 0x75989f8620
	protected StandardValuesCollection get_Values() { }
	// RVA: 0x63e0628 VA: 0x75989f8628
	protected Void set_Values(StandardValuesCollection value) { }
	// RVA: 0x63e0630 VA: 0x75989f8630
	public override Boolean CanConvertFrom(ITypeDescriptorContext context, Type sourceType) { }
	// RVA: 0x63e0740 VA: 0x75989f8740
	public override Boolean CanConvertTo(ITypeDescriptorContext context, Type destinationType) { }
	// RVA: 0x63e0850 VA: 0x75989f8850
	protected virtual IComparer get_Comparer() { }
	// RVA: 0x63e08a8 VA: 0x75989f88a8
	public override Object ConvertFrom(ITypeDescriptorContext context, CultureInfo culture, Object value) { }
	// RVA: 0x63e0db4 VA: 0x75989f8db4
	public override Object ConvertTo(ITypeDescriptorContext context, CultureInfo culture, Object value, Type destinationType) { }
	// RVA: 0x63e1bb4 VA: 0x75989f9bb4
	public override StandardValuesCollection GetStandardValues(ITypeDescriptorContext context) { }
	// RVA: 0x63e1fbc VA: 0x75989f9fbc
	public override Boolean GetStandardValuesExclusive(ITypeDescriptorContext context) { }
	// RVA: 0x63e2064 VA: 0x75989fa064
	public override Boolean GetStandardValuesSupported(ITypeDescriptorContext context) { }
	// RVA: 0x63e206c VA: 0x75989fa06c
	public override Boolean IsValid(ITypeDescriptorContext context, Object value) { }
}
```
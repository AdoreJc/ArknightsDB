# ReferenceConverter

**Namespace:** `System.ComponentModel`


## Fields

- `Type _type`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class ReferenceConverter : TypeConverter
{
	private static readonly String s_none; // 0x0
	private Type _type; // 0x10


	// RVA: 0x63d4a38 VA: 0x75989eca38
	public Void .ctor(Type type) { }
	// RVA: 0x63d4a68 VA: 0x75989eca68
	public override Boolean CanConvertFrom(ITypeDescriptorContext context, Type sourceType) { }
	// RVA: 0x63d4b34 VA: 0x75989ecb34
	public override Object ConvertFrom(ITypeDescriptorContext context, CultureInfo culture, Object value) { }
	// RVA: 0x63d4e80 VA: 0x75989ece80
	public override Object ConvertTo(ITypeDescriptorContext context, CultureInfo culture, Object value, Type destinationType) { }
	// RVA: 0x63d52d4 VA: 0x75989ed2d4
	public override StandardValuesCollection GetStandardValues(ITypeDescriptorContext context) { }
	// RVA: 0x63d5b1c VA: 0x75989edb1c
	public override Boolean GetStandardValuesExclusive(ITypeDescriptorContext context) { }
	// RVA: 0x63d5b24 VA: 0x75989edb24
	public override Boolean GetStandardValuesSupported(ITypeDescriptorContext context) { }
	// RVA: 0x63d5b2c VA: 0x75989edb2c
	protected virtual Boolean IsValueAllowed(ITypeDescriptorContext context, Object value) { }
	// RVA: 0x63d5b34 VA: 0x75989edb34
	private static Void .cctor() { }
}
```
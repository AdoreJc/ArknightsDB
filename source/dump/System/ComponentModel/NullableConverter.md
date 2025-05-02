# NullableConverter

**Namespace:** `System.ComponentModel`


## Properties

- `Type NullableType`

- `Type UnderlyingType`

- `TypeConverter UnderlyingTypeConverter`


## Methods

- `Type get_NullableType()`

- `Type get_UnderlyingType()`

- `TypeConverter get_UnderlyingTypeConverter()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class NullableConverter : TypeConverter
{
	private readonly Type <NullableType>k__BackingField; // 0x10
	private readonly Type <UnderlyingType>k__BackingField; // 0x18
	private readonly TypeConverter <UnderlyingTypeConverter>k__BackingField; // 0x20

	public Type NullableType { get; }
	public Type UnderlyingType { get; }
	public TypeConverter UnderlyingTypeConverter { get; }

	// RVA: 0x63cf6f0 VA: 0x75989e76f0
	public Void .ctor(Type type) { }
	// RVA: 0x63cf840 VA: 0x75989e7840
	public override Boolean CanConvertFrom(ITypeDescriptorContext context, Type sourceType) { }
	// RVA: 0x63cf904 VA: 0x75989e7904
	public override Object ConvertFrom(ITypeDescriptorContext context, CultureInfo culture, Object value) { }
	// RVA: 0x63cfa40 VA: 0x75989e7a40
	public override Boolean CanConvertTo(ITypeDescriptorContext context, Type destinationType) { }
	// RVA: 0x63cfb04 VA: 0x75989e7b04
	public override Object ConvertTo(ITypeDescriptorContext context, CultureInfo culture, Object value, Type destinationType) { }
	// RVA: 0x63cfcf4 VA: 0x75989e7cf4
	public override Object CreateInstance(ITypeDescriptorContext context, IDictionary propertyValues) { }
	// RVA: 0x63cfd18 VA: 0x75989e7d18
	public override Boolean GetCreateInstanceSupported(ITypeDescriptorContext context) { }
	// RVA: 0x63cfd3c VA: 0x75989e7d3c
	public override PropertyDescriptorCollection GetProperties(ITypeDescriptorContext context, Object value, Attribute[] attributes) { }
	// RVA: 0x63cfd60 VA: 0x75989e7d60
	public override Boolean GetPropertiesSupported(ITypeDescriptorContext context) { }
	// RVA: 0x63cfd84 VA: 0x75989e7d84
	public override StandardValuesCollection GetStandardValues(ITypeDescriptorContext context) { }
	// RVA: 0x63d014c VA: 0x75989e814c
	public override Boolean GetStandardValuesExclusive(ITypeDescriptorContext context) { }
	// RVA: 0x63d0174 VA: 0x75989e8174
	public override Boolean GetStandardValuesSupported(ITypeDescriptorContext context) { }
	// RVA: 0x63d019c VA: 0x75989e819c
	public override Boolean IsValid(ITypeDescriptorContext context, Object value) { }
	// RVA: 0x63d01d0 VA: 0x75989e81d0
	public Type get_NullableType() { }
	// RVA: 0x63d01d8 VA: 0x75989e81d8
	public Type get_UnderlyingType() { }
	// RVA: 0x63d01e0 VA: 0x75989e81e0
	public TypeConverter get_UnderlyingTypeConverter() { }
}
```
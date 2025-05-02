# TypeConverter

**Namespace:** `System.ComponentModel`


## Methods

- `Boolean CanConvertFrom(Type)`

- `Boolean CanConvertTo(Type)`

- `Object ConvertFrom(Object)`

- `Object ConvertFromInvariantString(String)`

- `Object ConvertFromInvariantString(ITypeDescriptorContext, String)`

- `Object ConvertFromString(String)`

- `Object ConvertFromString(ITypeDescriptorContext, String)`

- `Object ConvertFromString(ITypeDescriptorContext, CultureInfo, String)`

- `Object ConvertTo(Object, Type)`

- `String ConvertToInvariantString(Object)`

- `String ConvertToInvariantString(ITypeDescriptorContext, Object)`

- `String ConvertToString(Object)`

- `String ConvertToString(ITypeDescriptorContext, Object)`

- `String ConvertToString(ITypeDescriptorContext, CultureInfo, Object)`

- `Object CreateInstance(IDictionary)`

- `Exception GetConvertFromException(Object)`

- `Exception GetConvertToException(Object, Type)`

- `Boolean GetCreateInstanceSupported()`

- `PropertyDescriptorCollection GetProperties(Object)`

- `PropertyDescriptorCollection GetProperties(ITypeDescriptorContext, Object)`

- `Boolean GetPropertiesSupported()`

- `ICollection GetStandardValues()`

- `Boolean GetStandardValuesExclusive()`

- `Boolean GetStandardValuesSupported()`

- `Boolean IsValid(Object)`

- `PropertyDescriptorCollection SortProperties(PropertyDescriptorCollection, String[])`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class TypeConverter
{
	private const String s_UseCompatibleTypeConverterBehavior; // 0x0
	private static Boolean useCompatibleTypeConversion; // 0x0

	private static Boolean UseCompatibleTypeConversion { get; }

	// RVA: 0x63f2aa4 VA: 0x7598a0aaa4
	private static Boolean get_UseCompatibleTypeConversion() { }
	// RVA: 0x63f2af4 VA: 0x7598a0aaf4
	public Boolean CanConvertFrom(Type sourceType) { }
	// RVA: 0x63f2b08 VA: 0x7598a0ab08
	public virtual Boolean CanConvertFrom(ITypeDescriptorContext context, Type sourceType) { }
	// RVA: 0x63f2b90 VA: 0x7598a0ab90
	public Boolean CanConvertTo(Type destinationType) { }
	// RVA: 0x63f2ba4 VA: 0x7598a0aba4
	public virtual Boolean CanConvertTo(ITypeDescriptorContext context, Type destinationType) { }
	// RVA: 0x63f2c2c VA: 0x7598a0ac2c
	public Object ConvertFrom(Object value) { }
	// RVA: 0x63f2ca8 VA: 0x7598a0aca8
	public virtual Object ConvertFrom(ITypeDescriptorContext context, CultureInfo culture, Object value) { }
	// RVA: 0x63f31b4 VA: 0x7598a0b1b4
	public Object ConvertFromInvariantString(String text) { }
	// RVA: 0x63f323c VA: 0x7598a0b23c
	public Object ConvertFromInvariantString(ITypeDescriptorContext context, String text) { }
	// RVA: 0x63f32bc VA: 0x7598a0b2bc
	public Object ConvertFromString(String text) { }
	// RVA: 0x63f32d4 VA: 0x7598a0b2d4
	public Object ConvertFromString(ITypeDescriptorContext context, String text) { }
	// RVA: 0x63f3230 VA: 0x7598a0b230
	public Object ConvertFromString(ITypeDescriptorContext context, CultureInfo culture, String text) { }
	// RVA: 0x63f3354 VA: 0x7598a0b354
	public Object ConvertTo(Object value, Type destinationType) { }
	// RVA: 0x63f3370 VA: 0x7598a0b370
	public virtual Object ConvertTo(ITypeDescriptorContext context, CultureInfo culture, Object value, Type destinationType) { }
	// RVA: 0x63f3728 VA: 0x7598a0b728
	public String ConvertToInvariantString(Object value) { }
	// RVA: 0x63f3878 VA: 0x7598a0b878
	public String ConvertToInvariantString(ITypeDescriptorContext context, Object value) { }
	// RVA: 0x63f38f0 VA: 0x7598a0b8f0
	public String ConvertToString(Object value) { }
	// RVA: 0x63f39f0 VA: 0x7598a0b9f0
	public String ConvertToString(ITypeDescriptorContext context, Object value) { }
	// RVA: 0x63f379c VA: 0x7598a0b79c
	public String ConvertToString(ITypeDescriptorContext context, CultureInfo culture, Object value) { }
	// RVA: 0x63f3af4 VA: 0x7598a0baf4
	public Object CreateInstance(IDictionary propertyValues) { }
	// RVA: 0x63f3b08 VA: 0x7598a0bb08
	public virtual Object CreateInstance(ITypeDescriptorContext context, IDictionary propertyValues) { }
	// RVA: 0x63f3080 VA: 0x7598a0b080
	protected Exception GetConvertFromException(Object value) { }
	// RVA: 0x63f35a8 VA: 0x7598a0b5a8
	protected Exception GetConvertToException(Object value, Type destinationType) { }
	// RVA: 0x63f3b10 VA: 0x7598a0bb10
	public Boolean GetCreateInstanceSupported() { }
	// RVA: 0x63f3b20 VA: 0x7598a0bb20
	public virtual Boolean GetCreateInstanceSupported(ITypeDescriptorContext context) { }
	// RVA: 0x63f3b28 VA: 0x7598a0bb28
	public PropertyDescriptorCollection GetProperties(Object value) { }
	// RVA: 0x63f3b34 VA: 0x7598a0bb34
	public PropertyDescriptorCollection GetProperties(ITypeDescriptorContext context, Object value) { }
	// RVA: 0x63f3c30 VA: 0x7598a0bc30
	public virtual PropertyDescriptorCollection GetProperties(ITypeDescriptorContext context, Object value, Attribute[] attributes) { }
	// RVA: 0x63f3c38 VA: 0x7598a0bc38
	public Boolean GetPropertiesSupported() { }
	// RVA: 0x63f3c48 VA: 0x7598a0bc48
	public virtual Boolean GetPropertiesSupported(ITypeDescriptorContext context) { }
	// RVA: 0x63f3c50 VA: 0x7598a0bc50
	public ICollection GetStandardValues() { }
	// RVA: 0x63f3c60 VA: 0x7598a0bc60
	public virtual StandardValuesCollection GetStandardValues(ITypeDescriptorContext context) { }
	// RVA: 0x63f3c68 VA: 0x7598a0bc68
	public Boolean GetStandardValuesExclusive() { }
	// RVA: 0x63f3c7c VA: 0x7598a0bc7c
	public virtual Boolean GetStandardValuesExclusive(ITypeDescriptorContext context) { }
	// RVA: 0x63f3c84 VA: 0x7598a0bc84
	public Boolean GetStandardValuesSupported() { }
	// RVA: 0x63f3c98 VA: 0x7598a0bc98
	public virtual Boolean GetStandardValuesSupported(ITypeDescriptorContext context) { }
	// RVA: 0x63f3ca0 VA: 0x7598a0bca0
	public Boolean IsValid(Object value) { }
	// RVA: 0x63f3cb8 VA: 0x7598a0bcb8
	public virtual Boolean IsValid(ITypeDescriptorContext context, Object value) { }
	// RVA: 0x63f3df8 VA: 0x7598a0bdf8
	protected PropertyDescriptorCollection SortProperties(PropertyDescriptorCollection props, String[] names) { }
	// RVA: 0x63f3e30 VA: 0x7598a0be30
	public Void .ctor() { }
}
```
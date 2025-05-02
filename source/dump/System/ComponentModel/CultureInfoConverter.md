# CultureInfoConverter

**Namespace:** `System.ComponentModel`


## Fields

- `StandardValuesCollection _values`


## Properties

- `String DefaultCultureString`


## Methods

- `String get_DefaultCultureString()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class CultureInfoConverter : TypeConverter
{
	private StandardValuesCollection _values; // 0x10
	private const String DefaultInvariantCultureString; // 0x0

	private String DefaultCultureString { get; }

	// RVA: 0x63b8584 VA: 0x75989d0584
	private String get_DefaultCultureString() { }
	// RVA: 0x63b85c4 VA: 0x75989d05c4
	protected virtual String GetCultureName(CultureInfo culture) { }
	// RVA: 0x63b85e4 VA: 0x75989d05e4
	public override Boolean CanConvertFrom(ITypeDescriptorContext context, Type sourceType) { }
	// RVA: 0x63b86ac VA: 0x75989d06ac
	public override Boolean CanConvertTo(ITypeDescriptorContext context, Type destinationType) { }
	// RVA: 0x63b8774 VA: 0x75989d0774
	public override Object ConvertFrom(ITypeDescriptorContext context, CultureInfo culture, Object value) { }
	// RVA: 0x63b9130 VA: 0x75989d1130
	public override Object ConvertTo(ITypeDescriptorContext context, CultureInfo culture, Object value, Type destinationType) { }
	// RVA: 0x63b95ac VA: 0x75989d15ac
	public override StandardValuesCollection GetStandardValues(ITypeDescriptorContext context) { }
	// RVA: 0x63b97fc VA: 0x75989d17fc
	public override Boolean GetStandardValuesExclusive(ITypeDescriptorContext context) { }
	// RVA: 0x63b9804 VA: 0x75989d1804
	public override Boolean GetStandardValuesSupported(ITypeDescriptorContext context) { }
	// RVA: 0x63b980c VA: 0x75989d180c
	public Void .ctor() { }
}
```
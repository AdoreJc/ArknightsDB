# UriTypeConverter

**Namespace:** `System`


## Methods

- `Boolean CanConvert(Type)`


## Dump
```C#
// Dll : System.dll
// Namespace : System
public class UriTypeConverter : TypeConverter
{


	// RVA: 0x6374f3c VA: 0x759898cf3c
	public Void .ctor() { }
	// RVA: 0x6374f44 VA: 0x759898cf44
	private Boolean CanConvert(Type type) { }
	// RVA: 0x6375028 VA: 0x759898d028
	public override Boolean CanConvertFrom(ITypeDescriptorContext context, Type sourceType) { }
	// RVA: 0x63750dc VA: 0x759898d0dc
	public override Boolean CanConvertTo(ITypeDescriptorContext context, Type destinationType) { }
	// RVA: 0x6375154 VA: 0x759898d154
	public override Object ConvertFrom(ITypeDescriptorContext context, CultureInfo culture, Object value) { }
	// RVA: 0x6375300 VA: 0x759898d300
	public override Object ConvertTo(ITypeDescriptorContext context, CultureInfo culture, Object value, Type destinationType) { }
}
```
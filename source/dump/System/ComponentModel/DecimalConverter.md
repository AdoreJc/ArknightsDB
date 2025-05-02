# DecimalConverter

**Namespace:** `System.ComponentModel`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class DecimalConverter : BaseNumberConverter
{

	internal override Boolean AllowHex { get; }
	internal override Type TargetType { get; }

	// RVA: 0x63bf354 VA: 0x75989d7354
	internal override Boolean get_AllowHex() { }
	// RVA: 0x63bf35c VA: 0x75989d735c
	internal override Type get_TargetType() { }
	// RVA: 0x63bf3c8 VA: 0x75989d73c8
	public override Boolean CanConvertTo(ITypeDescriptorContext context, Type destinationType) { }
	// RVA: 0x63bf48c VA: 0x75989d748c
	public override Object ConvertTo(ITypeDescriptorContext context, CultureInfo culture, Object value, Type destinationType) { }
	// RVA: 0x63bf7cc VA: 0x75989d77cc
	internal override Object FromString(String value, Int32 radix) { }
	// RVA: 0x63bf8b8 VA: 0x75989d78b8
	internal override Object FromString(String value, NumberFormatInfo formatInfo) { }
	// RVA: 0x63bf964 VA: 0x75989d7964
	internal override String ToString(Object value, NumberFormatInfo formatInfo) { }
	// RVA: 0x63bfa4c VA: 0x75989d7a4c
	public Void .ctor() { }
}
```
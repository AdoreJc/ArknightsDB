# SingleConverter

**Namespace:** `System.ComponentModel`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class SingleConverter : BaseNumberConverter
{

	internal override Boolean AllowHex { get; }
	internal override Type TargetType { get; }

	// RVA: 0x63d8894 VA: 0x75989f0894
	internal override Boolean get_AllowHex() { }
	// RVA: 0x63d889c VA: 0x75989f089c
	internal override Type get_TargetType() { }
	// RVA: 0x63d8908 VA: 0x75989f0908
	internal override Object FromString(String value, Int32 radix) { }
	// RVA: 0x63d89c8 VA: 0x75989f09c8
	internal override Object FromString(String value, NumberFormatInfo formatInfo) { }
	// RVA: 0x63d8a38 VA: 0x75989f0a38
	internal override String ToString(Object value, NumberFormatInfo formatInfo) { }
	// RVA: 0x63d8ae8 VA: 0x75989f0ae8
	public Void .ctor() { }
}
```
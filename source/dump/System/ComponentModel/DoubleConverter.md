# DoubleConverter

**Namespace:** `System.ComponentModel`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class DoubleConverter : BaseNumberConverter
{

	internal override Boolean AllowHex { get; }
	internal override Type TargetType { get; }

	// RVA: 0x63c195c VA: 0x75989d995c
	internal override Boolean get_AllowHex() { }
	// RVA: 0x63c1964 VA: 0x75989d9964
	internal override Type get_TargetType() { }
	// RVA: 0x63c19d0 VA: 0x75989d99d0
	internal override Object FromString(String value, Int32 radix) { }
	// RVA: 0x63c1a90 VA: 0x75989d9a90
	internal override Object FromString(String value, NumberFormatInfo formatInfo) { }
	// RVA: 0x63c1b00 VA: 0x75989d9b00
	internal override String ToString(Object value, NumberFormatInfo formatInfo) { }
	// RVA: 0x63c1bb0 VA: 0x75989d9bb0
	public Void .ctor() { }
}
```
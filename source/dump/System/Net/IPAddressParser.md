# IPAddressParser

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class IPAddressParser
{


	// RVA: 0x64171bc VA: 0x7598a2f1bc
	internal static IPAddress Parse(ReadOnlySpan`1 ipSpan, Boolean tryParse) { }
	// RVA: 0x64178cc VA: 0x7598a2f8cc
	internal static String IPv4AddressToString(UInt32 address) { }
	// RVA: 0x641868c VA: 0x7598a3068c
	internal static Void IPv4AddressToString(UInt32 address, StringBuilder destination) { }
	// RVA: 0x64185f0 VA: 0x7598a305f0
	private static Int32 IPv4AddressToStringHelper(UInt32 address, Char* addressString) { }
	// RVA: 0x64178b8 VA: 0x7598a2f8b8
	internal static String IPv6AddressToString(UInt16[] address, UInt32 scopeId) { }
	// RVA: 0x64187b4 VA: 0x7598a307b4
	internal static StringBuilder IPv6AddressToStringHelper(UInt16[] address, UInt32 scopeId) { }
	// RVA: 0x64186fc VA: 0x7598a306fc
	private static Void FormatIPv4AddressNumber(Int32 number, Char* addressString, ref Int32 offset) { }
	// RVA: 0x641851c VA: 0x7598a3051c
	public static Boolean Ipv4StringToAddress(ReadOnlySpan`1 ipSpan, out Int64 address) { }
	// RVA: 0x64183b8 VA: 0x7598a303b8
	public static Boolean Ipv6StringToAddress(ReadOnlySpan`1 ipSpan, UInt16* numbers, Int32 numbersLength, out UInt32 scope) { }
	// RVA: 0x64188d4 VA: 0x7598a308d4
	private static Void AppendSections(UInt16[] address, Int32 fromInclusive, Int32 toExclusive, StringBuilder buffer) { }
	// RVA: 0x6418ac8 VA: 0x7598a30ac8
	private static Void AppendHex(UInt16 value, StringBuilder buffer) { }
	// RVA: 0x6418a8c VA: 0x7598a30a8c
	private static UInt32 ExtractIPv4Address(UInt16[] address) { }
	// RVA: 0x6418b30 VA: 0x7598a30b30
	private static UInt16 Reverse(UInt16 number) { }
}
```
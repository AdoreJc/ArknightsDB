# WWWTranscoder

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.UnityWebRequestModule.dll
// Namespace : UnityEngine
internal class WWWTranscoder
{
	private static Byte[] ucHexChars; // 0x0
	private static Byte[] lcHexChars; // 0x8
	private static Byte urlEscapeChar; // 0x10
	private static Byte[] urlSpace; // 0x18
	private static Byte[] dataSpace; // 0x20
	private static Byte[] urlForbidden; // 0x28
	private static Byte qpEscapeChar; // 0x30
	private static Byte[] qpSpace; // 0x38
	private static Byte[] qpForbidden; // 0x40


	// RVA: 0x6a84cb4 VA: 0x759909ccb4
	private static Byte Hex2Byte(Byte[] b, Int32 offset) { }
	// RVA: 0x6a84d60 VA: 0x759909cd60
	private static Void Byte2Hex(Byte b, Byte[] hexChars, out Byte byte0, out Byte byte1) { }
	// RVA: 0x6a84db4 VA: 0x759909cdb4
	public static Byte[] URLEncode(Byte[] toEncode) { }
	// RVA: 0x6a851cc VA: 0x759909d1cc
	public static String DataEncode(String toEncode, Encoding e) { }
	// RVA: 0x6a849b4 VA: 0x759909c9b4
	public static Byte[] DataEncode(Byte[] toEncode) { }
	// RVA: 0x6a848c0 VA: 0x759909c8c0
	public static String QPEncode(String toEncode, Encoding e) { }
	// RVA: 0x6a84e20 VA: 0x759909ce20
	public static Byte[] Encode(Byte[] input, Byte escapeChar, Byte[] space, Byte[] forbidden, Boolean uppercase) { }
	// RVA: 0x6a852c0 VA: 0x759909d2c0
	private static Boolean ByteArrayContains(Byte[] array, Byte b) { }
	// RVA: 0x6a82cd8 VA: 0x759909acd8
	public static Byte[] URLDecode(Byte[] toEncode) { }
	// RVA: 0x6a855ec VA: 0x759909d5ec
	private static Boolean ByteSubArrayEquals(Byte[] array, Int32 index, Byte[] comperand) { }
	// RVA: 0x6a8530c VA: 0x759909d30c
	public static Byte[] Decode(Byte[] input, Byte escapeChar, Byte[] space) { }
	// RVA: 0x6a84770 VA: 0x759909c770
	public static Boolean SevenBitClean(String s, Encoding e) { }
	// RVA: 0x6a85664 VA: 0x759909d664
	public static Boolean SevenBitClean(Byte* input, Int32 inputLength) { }
	// RVA: 0x6a8569c VA: 0x759909d69c
	private static Void .cctor() { }
}
```
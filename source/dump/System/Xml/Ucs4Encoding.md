# Ucs4Encoding

**Namespace:** `System.Xml`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class Ucs4Encoding : Encoding
{
	internal Ucs4Decoder ucs4Decoder; // 0x38

	public override String WebName { get; }
	public override Int32 CodePage { get; }
	internal static Encoding UCS4_Littleendian { get; }
	internal static Encoding UCS4_Bigendian { get; }
	internal static Encoding UCS4_2143 { get; }
	internal static Encoding UCS4_3412 { get; }

	// RVA: 0x62cc128 VA: 0x75988e4128
	public override String get_WebName() { }
	// RVA: 0x62cc134 VA: 0x75988e4134
	public override Decoder GetDecoder() { }
	// RVA: 0x62cc13c VA: 0x75988e413c
	public override Int32 GetByteCount(Char[] chars, Int32 index, Int32 count) { }
	// RVA: 0x62cc19c VA: 0x75988e419c
	public override Byte[] GetBytes(String s) { }
	// RVA: 0x62cc1a4 VA: 0x75988e41a4
	public override Int32 GetBytes(Char[] chars, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex) { }
	// RVA: 0x62cc1ac VA: 0x75988e41ac
	public override Int32 GetMaxByteCount(Int32 charCount) { }
	// RVA: 0x62cc1b4 VA: 0x75988e41b4
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x62cc1d4 VA: 0x75988e41d4
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex) { }
	// RVA: 0x62cc1f4 VA: 0x75988e41f4
	public override Int32 GetMaxCharCount(Int32 byteCount) { }
	// RVA: 0x62cc20c VA: 0x75988e420c
	public override Int32 get_CodePage() { }
	// RVA: 0x62cc214 VA: 0x75988e4214
	public override Encoder GetEncoder() { }
	// RVA: 0x62cc21c VA: 0x75988e421c
	internal static Encoding get_UCS4_Littleendian() { }
	// RVA: 0x62cc2e4 VA: 0x75988e42e4
	internal static Encoding get_UCS4_Bigendian() { }
	// RVA: 0x62cc3ac VA: 0x75988e43ac
	internal static Encoding get_UCS4_2143() { }
	// RVA: 0x62cc474 VA: 0x75988e4474
	internal static Encoding get_UCS4_3412() { }
	// RVA: 0x62cc53c VA: 0x75988e453c
	public Void .ctor() { }
}
```
# UTF16Decoder

**Namespace:** `System.Xml`


## Fields

- `Boolean bigEndian`

- `Int32 lastByte`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class UTF16Decoder : Decoder
{
	private Boolean bigEndian; // 0x20
	private Int32 lastByte; // 0x24


	// RVA: 0x62cba24 VA: 0x75988e3a24
	public Void .ctor(Boolean bigEndian) { }
	// RVA: 0x62cba54 VA: 0x75988e3a54
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x62cba64 VA: 0x75988e3a64
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count, Boolean flush) { }
	// RVA: 0x62cbb50 VA: 0x75988e3b50
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex) { }
	// RVA: 0x62cbd88 VA: 0x75988e3d88
	public override Void Convert(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex, Int32 charCount, Boolean flush, out Int32 bytesUsed, out Int32 charsUsed, out Boolean completed) { }
}
```
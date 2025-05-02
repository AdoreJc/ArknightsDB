# BinHexDecoder

**Namespace:** `System.Xml`


## Fields

- `Int32 curIndex`

- `Int32 endIndex`

- `Boolean hasHalfByteCached`

- `Byte cachedHalfByte`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class BinHexDecoder : IncrementalReadDecoder
{
	private Byte[] buffer; // 0x10
	private Int32 curIndex; // 0x18
	private Int32 endIndex; // 0x1c
	private Boolean hasHalfByteCached; // 0x20
	private Byte cachedHalfByte; // 0x21

	internal override Boolean IsFull { get; }

	// RVA: 0x6271960 VA: 0x7598889960
	internal override Boolean get_IsFull() { }
	// RVA: 0x6271970 VA: 0x7598889970
	internal override Int32 Decode(Char[] chars, Int32 startPos, Int32 len) { }
	// RVA: 0x6271c94 VA: 0x7598889c94
	public static Byte[] Decode(Char[] chars, Boolean allowOddChars) { }
	// RVA: 0x6271ac8 VA: 0x7598889ac8
	private static Void Decode(Char* pChars, Char* pCharsEndPos, Byte* pBytes, Byte* pBytesEndPos, ref Boolean hasHalfByteCached, ref Byte cachedHalfByte, out Int32 charsDecoded, out Int32 bytesDecoded) { }
}
```
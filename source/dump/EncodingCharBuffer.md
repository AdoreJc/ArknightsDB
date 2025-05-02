# EncodingCharBuffer

**Namespace:** ` `


## Fields

- `Int32 charCountResult`

- `Encoding enc`

- `DecoderNLS decoder`

- `DecoderFallbackBuffer fallbackBuffer`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class EncodingCharBuffer
{
	private Char* chars; // 0x10
	private Char* charStart; // 0x18
	private Char* charEnd; // 0x20
	private Int32 charCountResult; // 0x28
	private Encoding enc; // 0x30
	private DecoderNLS decoder; // 0x38
	private Byte* byteStart; // 0x40
	private Byte* byteEnd; // 0x48
	private Byte* bytes; // 0x50
	private DecoderFallbackBuffer fallbackBuffer; // 0x58

	internal Boolean MoreData { get; }
	internal Int32 BytesUsed { get; }
	internal Int32 Count { get; }

	// RVA: 0x5f3cf94 VA: 0x7598554f94
	internal Void .ctor(Encoding enc, DecoderNLS decoder, Char* charStart, Int32 charCount, Byte* byteStart, Int32 byteCount) { }
	// RVA: 0x5f3d074 VA: 0x7598555074
	internal Boolean AddChar(Char ch, Int32 numBytes) { }
	// RVA: 0x5f3d0e4 VA: 0x75985550e4
	internal Boolean AddChar(Char ch) { }
	// RVA: 0x5f3d0ec VA: 0x75985550ec
	internal Void AdjustBytes(Int32 count) { }
	// RVA: 0x5f3d0fc VA: 0x75985550fc
	internal Boolean get_MoreData() { }
	// RVA: 0x5f3d10c VA: 0x759855510c
	internal Byte GetNextByte() { }
	// RVA: 0x5f3d130 VA: 0x7598555130
	internal Int32 get_BytesUsed() { }
	// RVA: 0x5f3d140 VA: 0x7598555140
	internal Boolean Fallback(Byte fallbackByte) { }
	// RVA: 0x5f3d1b8 VA: 0x75985551b8
	internal Boolean Fallback(Byte[] byteBuffer) { }
	// RVA: 0x5f3d294 VA: 0x7598555294
	internal Int32 get_Count() { }
}
```
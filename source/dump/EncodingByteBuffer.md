# EncodingByteBuffer

**Namespace:** ` `


## Fields

- `Int32 byteCountResult`

- `Encoding enc`

- `EncoderNLS encoder`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class EncodingByteBuffer
{
	private Byte* bytes; // 0x10
	private Byte* byteStart; // 0x18
	private Byte* byteEnd; // 0x20
	private Char* chars; // 0x28
	private Char* charStart; // 0x30
	private Char* charEnd; // 0x38
	private Int32 byteCountResult; // 0x40
	private Encoding enc; // 0x48
	private EncoderNLS encoder; // 0x50
	internal EncoderFallbackBuffer fallbackBuffer; // 0x58

	internal Boolean MoreData { get; }
	internal Int32 CharsUsed { get; }
	internal Int32 Count { get; }

	// RVA: 0x5f3d29c VA: 0x759855529c
	internal Void .ctor(Encoding inEncoding, EncoderNLS inEncoder, Byte* inByteStart, Int32 inByteCount, Char* inCharStart, Int32 inCharCount) { }
	// RVA: 0x5f3d4e8 VA: 0x75985554e8
	internal Boolean AddByte(Byte b, Int32 moreBytesExpected) { }
	// RVA: 0x5f3d5b8 VA: 0x75985555b8
	internal Boolean AddByte(Byte b1) { }
	// RVA: 0x5f3d5c0 VA: 0x75985555c0
	internal Boolean AddByte(Byte b1, Byte b2) { }
	// RVA: 0x5f3d5c8 VA: 0x75985555c8
	internal Boolean AddByte(Byte b1, Byte b2, Int32 moreBytesExpected) { }
	// RVA: 0x5f3d538 VA: 0x7598555538
	internal Void MovePrevious(Boolean bThrow) { }
	// RVA: 0x5f3d610 VA: 0x7598555610
	internal Boolean get_MoreData() { }
	// RVA: 0x5f3d658 VA: 0x7598555658
	internal Char GetNextChar() { }
	// RVA: 0x5f3d6a8 VA: 0x75985556a8
	internal Int32 get_CharsUsed() { }
	// RVA: 0x5f3d6c0 VA: 0x75985556c0
	internal Int32 get_Count() { }
}
```
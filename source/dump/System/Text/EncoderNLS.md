# EncoderNLS

**Namespace:** `System.Text`


## Fields

- `Encoding _encoding`

- `Boolean _mustFlush`


## Properties

- `Encoding Encoding`

- `Boolean MustFlush`


## Methods

- `Encoding get_Encoding()`

- `Boolean get_MustFlush()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Text
internal class EncoderNLS : Encoder
{
	internal Char _charLeftOver; // 0x20
	private Encoding _encoding; // 0x28
	private Boolean _mustFlush; // 0x30
	internal Boolean _throwOnOverflow; // 0x31
	internal Int32 _charsUsed; // 0x34

	public Encoding Encoding { get; }
	public Boolean MustFlush { get; }
	internal virtual Boolean HasState { get; }

	// RVA: 0x5f2482c VA: 0x759853c82c
	internal Void .ctor(Encoding encoding) { }
	// RVA: 0x5f2488c VA: 0x759853c88c
	public override Void Reset() { }
	// RVA: 0x5f248ac VA: 0x759853c8ac
	public override Int32 GetByteCount(Char[] chars, Int32 index, Int32 count, Boolean flush) { }
	// RVA: 0x5f24a84 VA: 0x759853ca84
	public override Int32 GetByteCount(Char* chars, Int32 count, Boolean flush) { }
	// RVA: 0x5f24b7c VA: 0x759853cb7c
	public override Int32 GetBytes(Char[] chars, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex, Boolean flush) { }
	// RVA: 0x5f24e14 VA: 0x759853ce14
	public override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount, Boolean flush) { }
	// RVA: 0x5f24f34 VA: 0x759853cf34
	public override Void Convert(Char[] chars, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex, Int32 byteCount, Boolean flush, out Int32 charsUsed, out Int32 bytesUsed, out Boolean completed) { }
	// RVA: 0x5f25200 VA: 0x759853d200
	public override Void Convert(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount, Boolean flush, out Int32 charsUsed, out Int32 bytesUsed, out Boolean completed) { }
	// RVA: 0x5f253a8 VA: 0x759853d3a8
	public Encoding get_Encoding() { }
	// RVA: 0x5f253b0 VA: 0x759853d3b0
	public Boolean get_MustFlush() { }
	// RVA: 0x5f253b8 VA: 0x759853d3b8
	internal virtual Boolean get_HasState() { }
	// RVA: 0x5f253c8 VA: 0x759853d3c8
	internal Void ClearMustFlush() { }
}
```
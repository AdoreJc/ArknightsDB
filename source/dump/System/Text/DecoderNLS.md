# DecoderNLS

**Namespace:** `System.Text`


## Fields

- `Encoding _encoding`

- `Boolean _mustFlush`


## Properties

- `Boolean MustFlush`


## Methods

- `Boolean get_MustFlush()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Text
internal class DecoderNLS : Decoder
{
	private Encoding _encoding; // 0x20
	private Boolean _mustFlush; // 0x28
	internal Boolean _throwOnOverflow; // 0x29
	internal Int32 _bytesUsed; // 0x2c

	public Boolean MustFlush { get; }
	internal virtual Boolean HasState { get; }

	// RVA: 0x6138d60 VA: 0x7598750d60
	internal Void .ctor(Encoding encoding) { }
	// RVA: 0x613a840 VA: 0x7598752840
	public override Void Reset() { }
	// RVA: 0x613a858 VA: 0x7598752858
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x613a868 VA: 0x7598752868
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count, Boolean flush) { }
	// RVA: 0x613aa40 VA: 0x7598752a40
	public override Int32 GetCharCount(Byte* bytes, Int32 count, Boolean flush) { }
	// RVA: 0x613ab38 VA: 0x7598752b38
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex) { }
	// RVA: 0x613ab48 VA: 0x7598752b48
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex, Boolean flush) { }
	// RVA: 0x613ade0 VA: 0x7598752de0
	public override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount, Boolean flush) { }
	// RVA: 0x613af00 VA: 0x7598752f00
	public override Void Convert(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex, Int32 charCount, Boolean flush, out Int32 bytesUsed, out Int32 charsUsed, out Boolean completed) { }
	// RVA: 0x613b1d0 VA: 0x75987531d0
	public override Void Convert(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount, Boolean flush, out Int32 bytesUsed, out Int32 charsUsed, out Boolean completed) { }
	// RVA: 0x613b37c VA: 0x759875337c
	public Boolean get_MustFlush() { }
	// RVA: 0x613b384 VA: 0x7598753384
	internal virtual Boolean get_HasState() { }
	// RVA: 0x613b38c VA: 0x759875338c
	internal Void ClearMustFlush() { }
}
```
# UnicodeEncoding

**Namespace:** `System.Text`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Text
public class UnicodeEncoding : Encoding
{
	internal static readonly UnicodeEncoding s_bigEndianDefault; // 0x0
	internal static readonly UnicodeEncoding s_littleEndianDefault; // 0x8
	private static readonly Byte[] s_bigEndianPreamble; // 0x10
	private static readonly Byte[] s_littleEndianPreamble; // 0x18
	internal Boolean isThrowException; // 0x38
	internal Boolean bigEndian; // 0x39
	internal Boolean byteOrderMark; // 0x3a
	private static readonly UInt64 highLowPatternMask; // 0x20

	public override ReadOnlySpan`1 Preamble { get; }

	// RVA: 0x5f34110 VA: 0x759854c110
	public Void .ctor() { }
	// RVA: 0x5f34144 VA: 0x759854c144
	public Void .ctor(Boolean bigEndian, Boolean byteOrderMark) { }
	// RVA: 0x5f3418c VA: 0x759854c18c
	public Void .ctor(Boolean bigEndian, Boolean byteOrderMark, Boolean throwOnInvalidBytes) { }
	// RVA: 0x5f34204 VA: 0x759854c204
	internal override Void SetDefaultFallbacks() { }
	// RVA: 0x5f34300 VA: 0x759854c300
	public override Int32 GetByteCount(Char[] chars, Int32 index, Int32 count) { }
	// RVA: 0x5f34484 VA: 0x759854c484
	public override Int32 GetByteCount(String s) { }
	// RVA: 0x5f34514 VA: 0x759854c514
	public override Int32 GetByteCount(Char* chars, Int32 count) { }
	// RVA: 0x5f345ec VA: 0x759854c5ec
	public override Int32 GetBytes(String s, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex) { }
	// RVA: 0x5f3484c VA: 0x759854c84c
	public override Int32 GetBytes(Char[] chars, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex) { }
	// RVA: 0x5f34ac8 VA: 0x759854cac8
	public override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount) { }
	// RVA: 0x5f34bc8 VA: 0x759854cbc8
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x5f34d4c VA: 0x759854cd4c
	public override Int32 GetCharCount(Byte* bytes, Int32 count) { }
	// RVA: 0x5f34e24 VA: 0x759854ce24
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex) { }
	// RVA: 0x5f350a0 VA: 0x759854d0a0
	public override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount) { }
	// RVA: 0x5f351a0 VA: 0x759854d1a0
	public override String GetString(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x5f35368 VA: 0x759854d368
	internal override Int32 GetByteCount(Char* chars, Int32 count, EncoderNLS encoder) { }
	// RVA: 0x5f358d4 VA: 0x759854d8d4
	internal override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount, EncoderNLS encoder) { }
	// RVA: 0x5f36008 VA: 0x759854e008
	internal override Int32 GetCharCount(Byte* bytes, Int32 count, DecoderNLS baseDecoder) { }
	// RVA: 0x5f366c8 VA: 0x759854e6c8
	internal override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount, DecoderNLS baseDecoder) { }
	// RVA: 0x5f36fe8 VA: 0x759854efe8
	public override Encoder GetEncoder() { }
	// RVA: 0x5f37048 VA: 0x759854f048
	public override Decoder GetDecoder() { }
	// RVA: 0x5f370ac VA: 0x759854f0ac
	public override Byte[] GetPreamble() { }
	// RVA: 0x5f371a8 VA: 0x759854f1a8
	public override ReadOnlySpan`1 get_Preamble() { }
	// RVA: 0x5f37318 VA: 0x759854f318
	public override Int32 GetMaxByteCount(Int32 charCount) { }
	// RVA: 0x5f37420 VA: 0x759854f420
	public override Int32 GetMaxCharCount(Int32 byteCount) { }
	// RVA: 0x5f3752c VA: 0x759854f52c
	public override Boolean Equals(Object value) { }
	// RVA: 0x5f37640 VA: 0x759854f640
	public override Int32 GetHashCode() { }
	// RVA: 0x5f376bc VA: 0x759854f6bc
	private static Void .cctor() { }
}
```
# ASCIIEncoding

**Namespace:** `System.Text`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Text
public class ASCIIEncoding : Encoding
{
	internal static readonly ASCIIEncodingSealed s_default; // 0x0


	// RVA: 0x6136c8c VA: 0x759874ec8c
	public Void .ctor() { }
	// RVA: 0x6136c98 VA: 0x759874ec98
	internal override Void SetDefaultFallbacks() { }
	// RVA: 0x6136e04 VA: 0x759874ee04
	public override Int32 GetByteCount(Char[] chars, Int32 index, Int32 count) { }
	// RVA: 0x6136f88 VA: 0x759874ef88
	public override Int32 GetByteCount(String chars) { }
	// RVA: 0x6137018 VA: 0x759874f018
	public override Int32 GetByteCount(Char* chars, Int32 count) { }
	// RVA: 0x61370f0 VA: 0x759874f0f0
	public override Int32 GetBytes(String chars, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex) { }
	// RVA: 0x6137350 VA: 0x759874f350
	public override Int32 GetBytes(Char[] chars, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex) { }
	// RVA: 0x61375cc VA: 0x759874f5cc
	public override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount) { }
	// RVA: 0x61376cc VA: 0x759874f6cc
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x6137850 VA: 0x759874f850
	public override Int32 GetCharCount(Byte* bytes, Int32 count) { }
	// RVA: 0x6137928 VA: 0x759874f928
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex) { }
	// RVA: 0x6137ba4 VA: 0x759874fba4
	public override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount) { }
	// RVA: 0x6137ca4 VA: 0x759874fca4
	public override String GetString(Byte[] bytes, Int32 byteIndex, Int32 byteCount) { }
	// RVA: 0x6137e6c VA: 0x759874fe6c
	internal override Int32 GetByteCount(Char* chars, Int32 charCount, EncoderNLS encoder) { }
	// RVA: 0x6138260 VA: 0x7598750260
	internal override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount, EncoderNLS encoder) { }
	// RVA: 0x61386b8 VA: 0x75987506b8
	internal override Int32 GetCharCount(Byte* bytes, Int32 count, DecoderNLS decoder) { }
	// RVA: 0x613885c VA: 0x759875085c
	internal override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount, DecoderNLS decoder) { }
	// RVA: 0x6138af4 VA: 0x7598750af4
	public override Int32 GetMaxByteCount(Int32 charCount) { }
	// RVA: 0x6138bfc VA: 0x7598750bfc
	public override Int32 GetMaxCharCount(Int32 byteCount) { }
	// RVA: 0x6138d00 VA: 0x7598750d00
	public override Decoder GetDecoder() { }
	// RVA: 0x6138dc0 VA: 0x7598750dc0
	public override Encoder GetEncoder() { }
	// RVA: 0x6138e24 VA: 0x7598750e24
	private static Void .cctor() { }
}
```
# UTF7Encoding

**Namespace:** `System.Text`


## Fields

- `Boolean _allowOptionals`


## Methods

- `Void MakeTables()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Text
public class UTF7Encoding : Encoding
{
	internal static readonly UTF7Encoding s_default; // 0x0
	private Byte[] _base64Bytes; // 0x38
	private SByte[] _base64Values; // 0x40
	private Boolean[] _directEncode; // 0x48
	private Boolean _allowOptionals; // 0x50


	// RVA: 0x5f2e890 VA: 0x7598546890
	public Void .ctor() { }
	// RVA: 0x5f2e8b4 VA: 0x75985468b4
	public Void .ctor(Boolean allowOptionals) { }
	// RVA: 0x5f2e8e4 VA: 0x75985468e4
	private Void MakeTables() { }
	// RVA: 0x5f2eb7c VA: 0x7598546b7c
	internal override Void SetDefaultFallbacks() { }
	// RVA: 0x5f2ec50 VA: 0x7598546c50
	public override Boolean Equals(Object value) { }
	// RVA: 0x5f2ed20 VA: 0x7598546d20
	public override Int32 GetHashCode() { }
	// RVA: 0x5f2ed8c VA: 0x7598546d8c
	public override Int32 GetByteCount(Char[] chars, Int32 index, Int32 count) { }
	// RVA: 0x5f2ef10 VA: 0x7598546f10
	public override Int32 GetByteCount(String s) { }
	// RVA: 0x5f2efa0 VA: 0x7598546fa0
	public override Int32 GetByteCount(Char* chars, Int32 count) { }
	// RVA: 0x5f2f078 VA: 0x7598547078
	public override Int32 GetBytes(String s, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex) { }
	// RVA: 0x5f2f2d8 VA: 0x75985472d8
	public override Int32 GetBytes(Char[] chars, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex) { }
	// RVA: 0x5f2f554 VA: 0x7598547554
	public override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount) { }
	// RVA: 0x5f2f654 VA: 0x7598547654
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x5f2f7d8 VA: 0x75985477d8
	public override Int32 GetCharCount(Byte* bytes, Int32 count) { }
	// RVA: 0x5f2f8b0 VA: 0x75985478b0
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex) { }
	// RVA: 0x5f2fb2c VA: 0x7598547b2c
	public override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount) { }
	// RVA: 0x5f2fc2c VA: 0x7598547c2c
	public override String GetString(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x5f2fdf4 VA: 0x7598547df4
	internal override Int32 GetByteCount(Char* chars, Int32 count, EncoderNLS baseEncoder) { }
	// RVA: 0x5f2fe10 VA: 0x7598547e10
	internal override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount, EncoderNLS baseEncoder) { }
	// RVA: 0x5f301ac VA: 0x75985481ac
	internal override Int32 GetCharCount(Byte* bytes, Int32 count, DecoderNLS baseDecoder) { }
	// RVA: 0x5f301c8 VA: 0x75985481c8
	internal override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount, DecoderNLS baseDecoder) { }
	// RVA: 0x5f30464 VA: 0x7598548464
	public override Decoder GetDecoder() { }
	// RVA: 0x5f304d0 VA: 0x75985484d0
	public override Encoder GetEncoder() { }
	// RVA: 0x5f30534 VA: 0x7598548534
	public override Int32 GetMaxByteCount(Int32 charCount) { }
	// RVA: 0x5f305f8 VA: 0x75985485f8
	public override Int32 GetMaxCharCount(Int32 byteCount) { }
	// RVA: 0x5f30670 VA: 0x7598548670
	private static Void .cctor() { }
}
```
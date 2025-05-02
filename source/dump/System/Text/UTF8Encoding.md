# UTF8Encoding

**Namespace:** `System.Text`


## Fields

- `Boolean _isThrowException`


## Methods

- `Boolean FallbackInvalidByteSequence(ref, Int32, DecoderFallbackBuffer, ref)`

- `Int32 FallbackInvalidByteSequence(Byte*, Int32, DecoderFallbackBuffer)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Text
public class UTF8Encoding : Encoding
{
	internal static readonly UTF8EncodingSealed s_default; // 0x0
	internal static readonly Byte[] s_preamble; // 0x8
	internal readonly Boolean _emitUTF8Identifier; // 0x38
	private Boolean _isThrowException; // 0x39

	public override ReadOnlySpan`1 Preamble { get; }

	// RVA: 0x5f30940 VA: 0x7598548940
	public Void .ctor() { }
	// RVA: 0x5f30960 VA: 0x7598548960
	public Void .ctor(Boolean encoderShouldEmitUTF8Identifier) { }
	// RVA: 0x5f30990 VA: 0x7598548990
	public Void .ctor(Boolean encoderShouldEmitUTF8Identifier, Boolean throwOnInvalidBytes) { }
	// RVA: 0x5f309f0 VA: 0x75985489f0
	internal override Void SetDefaultFallbacks() { }
	// RVA: 0x5f30aec VA: 0x7598548aec
	public override Int32 GetByteCount(Char[] chars, Int32 index, Int32 count) { }
	// RVA: 0x5f30c70 VA: 0x7598548c70
	public override Int32 GetByteCount(String chars) { }
	// RVA: 0x5f30d00 VA: 0x7598548d00
	public override Int32 GetByteCount(Char* chars, Int32 count) { }
	// RVA: 0x5f30dd8 VA: 0x7598548dd8
	public override Int32 GetBytes(String s, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex) { }
	// RVA: 0x5f31038 VA: 0x7598549038
	public override Int32 GetBytes(Char[] chars, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex) { }
	// RVA: 0x5f312b4 VA: 0x75985492b4
	public override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount) { }
	// RVA: 0x5f313b4 VA: 0x75985493b4
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x5f31538 VA: 0x7598549538
	public override Int32 GetCharCount(Byte* bytes, Int32 count) { }
	// RVA: 0x5f31610 VA: 0x7598549610
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex) { }
	// RVA: 0x5f3188c VA: 0x759854988c
	public override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount) { }
	// RVA: 0x5f3198c VA: 0x759854998c
	public override String GetString(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x5f31b54 VA: 0x7598549b54
	internal override Int32 GetByteCount(Char* chars, Int32 count, EncoderNLS baseEncoder) { }
	// RVA: 0x5f32174 VA: 0x759854a174
	private static Int32 PtrDiff(Char* a, Char* b) { }
	// RVA: 0x5f32180 VA: 0x759854a180
	private static Int32 PtrDiff(Byte* a, Byte* b) { }
	// RVA: 0x5f32160 VA: 0x759854a160
	private static Boolean InRange(Int32 ch, Int32 start, Int32 end) { }
	// RVA: 0x5f32188 VA: 0x759854a188
	internal override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount, EncoderNLS baseEncoder) { }
	// RVA: 0x5f328d0 VA: 0x759854a8d0
	internal override Int32 GetCharCount(Byte* bytes, Int32 count, DecoderNLS baseDecoder) { }
	// RVA: 0x5f32e50 VA: 0x759854ae50
	internal override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount, DecoderNLS baseDecoder) { }
	// RVA: 0x5f335d4 VA: 0x759854b5d4
	private Boolean FallbackInvalidByteSequence(ref Byte* pSrc, Int32 ch, DecoderFallbackBuffer fallback, ref Char* pTarget) { }
	// RVA: 0x5f32e10 VA: 0x759854ae10
	private Int32 FallbackInvalidByteSequence(Byte* pSrc, Int32 ch, DecoderFallbackBuffer fallback) { }
	// RVA: 0x5f33648 VA: 0x759854b648
	private Byte[] GetBytesUnknown(ref Byte* pSrc, Int32 ch) { }
	// RVA: 0x5f3383c VA: 0x759854b83c
	public override Decoder GetDecoder() { }
	// RVA: 0x5f338a8 VA: 0x759854b8a8
	public override Encoder GetEncoder() { }
	// RVA: 0x5f3390c VA: 0x759854b90c
	public override Int32 GetMaxByteCount(Int32 charCount) { }
	// RVA: 0x5f33a14 VA: 0x759854ba14
	public override Int32 GetMaxCharCount(Int32 byteCount) { }
	// RVA: 0x5f33b1c VA: 0x759854bb1c
	public override Byte[] GetPreamble() { }
	// RVA: 0x5f33bf0 VA: 0x759854bbf0
	public override ReadOnlySpan`1 get_Preamble() { }
	// RVA: 0x5f33d50 VA: 0x759854bd50
	public override Boolean Equals(Object value) { }
	// RVA: 0x5f33e20 VA: 0x759854be20
	public override Int32 GetHashCode() { }
	// RVA: 0x5f33e80 VA: 0x759854be80
	private static Void .cctor() { }
}
```
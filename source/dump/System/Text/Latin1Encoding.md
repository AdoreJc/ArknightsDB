# Latin1Encoding

**Namespace:** `System.Text`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Text
internal class Latin1Encoding : EncodingNLS, ISerializable
{
	internal static readonly Latin1Encoding s_default; // 0x0
	private static readonly Char[] arrayCharBestFit; // 0x8


	// RVA: 0x5f27234 VA: 0x759853f234
	public Void .ctor() { }
	// RVA: 0x5f27240 VA: 0x759853f240
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f2728c VA: 0x759853f28c
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f27374 VA: 0x759853f374
	internal override Int32 GetByteCount(Char* chars, Int32 charCount, EncoderNLS encoder) { }
	// RVA: 0x5f27570 VA: 0x759853f570
	internal override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount, EncoderNLS encoder) { }
	// RVA: 0x5f278c4 VA: 0x759853f8c4
	internal override Int32 GetCharCount(Byte* bytes, Int32 count, DecoderNLS decoder) { }
	// RVA: 0x5f278cc VA: 0x759853f8cc
	internal override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount, DecoderNLS decoder) { }
	// RVA: 0x5f27940 VA: 0x759853f940
	public override Int32 GetMaxByteCount(Int32 charCount) { }
	// RVA: 0x5f27a48 VA: 0x759853fa48
	public override Int32 GetMaxCharCount(Int32 byteCount) { }
	// RVA: 0x5f27b4c VA: 0x759853fb4c
	internal override Char[] GetBestFitUnicodeToBytesData() { }
	// RVA: 0x5f27ba4 VA: 0x759853fba4
	private static Void .cctor() { }
}
```
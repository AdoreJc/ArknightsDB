# DefaultDecoder

**Namespace:** ` `


## Fields

- `Encoding m_encoding`

- `Boolean m_hasInitializedEncoding`


## Methods

- `Object GetRealObject(StreamingContext)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class DefaultDecoder : Decoder, ISerializable, IObjectReference
{
	private Encoding m_encoding; // 0x20
	private Boolean m_hasInitializedEncoding; // 0x28


	// RVA: 0x5f3bc44 VA: 0x7598553c44
	public Void .ctor(Encoding encoding) { }
	// RVA: 0x5f3cae4 VA: 0x7598554ae4
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f3cdec VA: 0x7598554dec
	public Object GetRealObject(StreamingContext context) { }
	// RVA: 0x5f3ce40 VA: 0x7598554e40
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f3cee4 VA: 0x7598554ee4
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count) { }
	// RVA: 0x5f3cef4 VA: 0x7598554ef4
	public override Int32 GetCharCount(Byte[] bytes, Int32 index, Int32 count, Boolean flush) { }
	// RVA: 0x5f3cf18 VA: 0x7598554f18
	public override Int32 GetCharCount(Byte* bytes, Int32 count, Boolean flush) { }
	// RVA: 0x5f3cf3c VA: 0x7598554f3c
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex) { }
	// RVA: 0x5f3cf4c VA: 0x7598554f4c
	public override Int32 GetChars(Byte[] bytes, Int32 byteIndex, Int32 byteCount, Char[] chars, Int32 charIndex, Boolean flush) { }
	// RVA: 0x5f3cf70 VA: 0x7598554f70
	public override Int32 GetChars(Byte* bytes, Int32 byteCount, Char* chars, Int32 charCount, Boolean flush) { }
}
```
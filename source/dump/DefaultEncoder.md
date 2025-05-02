# DefaultEncoder

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
internal class DefaultEncoder : Encoder, ISerializable, IObjectReference
{
	private Encoding m_encoding; // 0x20
	private Boolean m_hasInitializedEncoding; // 0x28
	internal Char charLeftOver; // 0x2a


	// RVA: 0x5f3bee0 VA: 0x7598553ee0
	public Void .ctor(Encoding encoding) { }
	// RVA: 0x5f3c55c VA: 0x759855455c
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f3c8e8 VA: 0x75985548e8
	public Object GetRealObject(StreamingContext context) { }
	// RVA: 0x5f3c9b0 VA: 0x75985549b0
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f3ca54 VA: 0x7598554a54
	public override Int32 GetByteCount(Char[] chars, Int32 index, Int32 count, Boolean flush) { }
	// RVA: 0x5f3ca78 VA: 0x7598554a78
	public override Int32 GetByteCount(Char* chars, Int32 count, Boolean flush) { }
	// RVA: 0x5f3ca9c VA: 0x7598554a9c
	public override Int32 GetBytes(Char[] chars, Int32 charIndex, Int32 charCount, Byte[] bytes, Int32 byteIndex, Boolean flush) { }
	// RVA: 0x5f3cac0 VA: 0x7598554ac0
	public override Int32 GetBytes(Char* chars, Int32 charCount, Byte* bytes, Int32 byteCount, Boolean flush) { }
}
```
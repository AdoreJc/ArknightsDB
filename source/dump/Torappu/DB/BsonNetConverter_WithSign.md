# BsonNetConverter_WithSign

**Namespace:** `Torappu.DB`


## Fields

- `String m_signPubKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class BsonNetConverter_WithSign : BsonNetConverter
{
	private const Int32 SIGN_HEADER_LENGTH; // 0x0
	private String m_signPubKey; // 0x28


	// RVA: 0x37173c8 VA: 0x7595d2f3c8
	public Void .ctor() { }
	// RVA: 0x371743c VA: 0x7595d2f43c
	protected override Void ProcessStreamAfterSerialize(Stream inStream, Stream outStream) { }
	// RVA: 0x VA: 0x0
	protected override T DeserializeInternal(Stream stream) { }
}
```
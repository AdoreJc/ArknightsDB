# DerOutputStream

**Namespace:** `Org.BouncyCastle.Asn1`


## Methods

- `Void WriteLength(Int32)`

- `Void WriteNull()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerOutputStream : FilterStream
{


	// RVA: 0x658cff4 VA: 0x7598ba4ff4
	public Void .ctor(Stream os) { }
	// RVA: 0x65a0640 VA: 0x7598bb8640
	private Void WriteLength(Int32 length) { }
	// RVA: 0x659af80 VA: 0x7598bb2f80
	internal Void WriteEncoded(Int32 tag, Byte[] bytes) { }
	// RVA: 0x65969c8 VA: 0x7598bae9c8
	internal Void WriteEncoded(Int32 tag, Byte first, Byte[] bytes) { }
	// RVA: 0x65a0468 VA: 0x7598bb8468
	internal Void WriteEncoded(Int32 tag, Byte[] bytes, Int32 offset, Int32 length) { }
	// RVA: 0x65999a0 VA: 0x7598bb19a0
	internal Void WriteTag(Int32 flags, Int32 tagNo) { }
	// RVA: 0x659a894 VA: 0x7598bb2894
	internal Void WriteEncoded(Int32 flags, Int32 tagNo, Byte[] bytes) { }
	// RVA: 0x6591ee8 VA: 0x7598ba9ee8
	protected Void WriteNull() { }
	// RVA: 0x65a06e0 VA: 0x7598bb86e0
	public virtual Void WriteObject(Object obj) { }
	// RVA: 0x65a083c VA: 0x7598bb883c
	public virtual Void WriteObject(Asn1Encodable obj) { }
	// RVA: 0x65a08ac VA: 0x7598bb88ac
	public virtual Void WriteObject(Asn1Object obj) { }
}
```
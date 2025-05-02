# Asn1InputStream

**Namespace:** `Org.BouncyCastle.Asn1`


## Methods

- `Asn1Object BuildObject(Int32, Int32, Int32)`

- `Asn1Object ReadObject()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class Asn1InputStream : FilterStream
{
	private readonly Int32 limit; // 0x30
	private readonly Byte[][] tmpBuffers; // 0x38


	// RVA: 0x658dbe8 VA: 0x7598ba5be8
	internal static Int32 FindLimit(Stream input) { }
	// RVA: 0x658dcd4 VA: 0x7598ba5cd4
	public Void .ctor(Stream inputStream) { }
	// RVA: 0x658dd04 VA: 0x7598ba5d04
	public Void .ctor(Stream inputStream, Int32 limit) { }
	// RVA: 0x658dd80 VA: 0x7598ba5d80
	public Void .ctor(Byte[] input) { }
	// RVA: 0x658de00 VA: 0x7598ba5e00
	private Asn1Object BuildObject(Int32 tag, Int32 tagNo, Int32 length) { }
	// RVA: 0x658ef04 VA: 0x7598ba6f04
	internal Asn1EncodableVector BuildEncodableVector() { }
	// RVA: 0x658f4f8 VA: 0x7598ba74f8
	internal virtual Asn1EncodableVector BuildDerEncodableVector(DefiniteLengthInputStream dIn) { }
	// RVA: 0x658f568 VA: 0x7598ba7568
	internal virtual DerSequence CreateDerSequence(DefiniteLengthInputStream dIn) { }
	// RVA: 0x658f680 VA: 0x7598ba7680
	internal virtual DerSet CreateDerSet(DefiniteLengthInputStream dIn) { }
	// RVA: 0x658f050 VA: 0x7598ba7050
	public Asn1Object ReadObject() { }
	// RVA: 0x658f7a4 VA: 0x7598ba77a4
	internal static Int32 ReadTagNumber(Stream s, Int32 tag) { }
	// RVA: 0x658f8a4 VA: 0x7598ba78a4
	internal static Int32 ReadLength(Stream s, Int32 limit) { }
	// RVA: 0x65900a4 VA: 0x7598ba80a4
	internal static Byte[] GetBuffer(DefiniteLengthInputStream defIn, Byte[][] tmpBuffers) { }
	// RVA: 0x658e958 VA: 0x7598ba6958
	internal static Asn1Object CreatePrimitiveDerObject(Int32 tagNo, DefiniteLengthInputStream defIn, Byte[][] tmpBuffers) { }
}
```
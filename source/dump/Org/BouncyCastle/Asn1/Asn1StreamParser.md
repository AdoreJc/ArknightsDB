# Asn1StreamParser

**Namespace:** `Org.BouncyCastle.Asn1`


## Methods

- `Void Set00Check(Boolean)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class Asn1StreamParser
{
	private readonly Stream _in; // 0x10
	private readonly Int32 _limit; // 0x18
	private readonly Byte[][] tmpBuffers; // 0x20


	// RVA: 0x658e380 VA: 0x7598ba6380
	public Void .ctor(Stream inStream) { }
	// RVA: 0x658fa94 VA: 0x7598ba7a94
	public Void .ctor(Stream inStream, Int32 limit) { }
	// RVA: 0x6594e2c VA: 0x7598bace2c
	public Void .ctor(Byte[] encoding) { }
	// RVA: 0x6594eac VA: 0x7598baceac
	internal IAsn1Convertible ReadIndef(Int32 tagValue) { }
	// RVA: 0x6595018 VA: 0x7598bad018
	internal IAsn1Convertible ReadImplicit(Boolean constructed, Int32 tag) { }
	// RVA: 0x658e3b0 VA: 0x7598ba63b0
	internal Asn1Object ReadTaggedObject(Boolean constructed, Int32 tag) { }
	// RVA: 0x65955c0 VA: 0x7598bad5c0
	public virtual IAsn1Convertible ReadObject() { }
	// RVA: 0x6595b40 VA: 0x7598badb40
	private Void Set00Check(Boolean enabled) { }
	// RVA: 0x6595348 VA: 0x7598bad348
	internal Asn1EncodableVector ReadVector() { }
}
```
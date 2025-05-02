# DigestInfo

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `AlgorithmIdentifier AlgorithmID`


## Methods

- `AlgorithmIdentifier get_AlgorithmID()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class DigestInfo : Asn1Encodable
{
	private readonly Byte[] digest; // 0x10
	private readonly AlgorithmIdentifier algID; // 0x18

	public AlgorithmIdentifier AlgorithmID { get; }

	// RVA: 0x65b1608 VA: 0x7598bc9608
	public static DigestInfo GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b1620 VA: 0x7598bc9620
	public static DigestInfo GetInstance(Object obj) { }
	// RVA: 0x65b18b0 VA: 0x7598bc98b0
	public Void .ctor(AlgorithmIdentifier algID, Byte[] digest) { }
	// RVA: 0x65b17a8 VA: 0x7598bc97a8
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b18f4 VA: 0x7598bc98f4
	public AlgorithmIdentifier get_AlgorithmID() { }
	// RVA: 0x65b18fc VA: 0x7598bc98fc
	public Byte[] GetDigest() { }
	// RVA: 0x65b1904 VA: 0x7598bc9904
	public override Asn1Object ToAsn1Object() { }
}
```
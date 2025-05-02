# SubjectPublicKeyInfo

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `AlgorithmIdentifier AlgorithmID`

- `DerBitString PublicKeyData`


## Methods

- `AlgorithmIdentifier get_AlgorithmID()`

- `Asn1Object GetPublicKey()`

- `DerBitString get_PublicKeyData()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class SubjectPublicKeyInfo : Asn1Encodable
{
	private readonly AlgorithmIdentifier algID; // 0x10
	private readonly DerBitString keyData; // 0x18

	public AlgorithmIdentifier AlgorithmID { get; }
	public DerBitString PublicKeyData { get; }

	// RVA: 0x65b5e9c VA: 0x7598bcde9c
	public static SubjectPublicKeyInfo GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b5eb4 VA: 0x7598bcdeb4
	public static SubjectPublicKeyInfo GetInstance(Object obj) { }
	// RVA: 0x65b60d4 VA: 0x7598bce0d4
	public Void .ctor(AlgorithmIdentifier algID, Asn1Encodable publicKey) { }
	// RVA: 0x65b616c VA: 0x7598bce16c
	public Void .ctor(AlgorithmIdentifier algID, Byte[] publicKey) { }
	// RVA: 0x65b5f58 VA: 0x7598bcdf58
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b6204 VA: 0x7598bce204
	public AlgorithmIdentifier get_AlgorithmID() { }
	// RVA: 0x65b620c VA: 0x7598bce20c
	public Asn1Object GetPublicKey() { }
	// RVA: 0x65b6234 VA: 0x7598bce234
	public DerBitString get_PublicKeyData() { }
	// RVA: 0x65b623c VA: 0x7598bce23c
	public override Asn1Object ToAsn1Object() { }
}
```
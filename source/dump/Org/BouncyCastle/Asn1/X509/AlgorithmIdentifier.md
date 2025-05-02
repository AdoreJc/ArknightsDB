# AlgorithmIdentifier

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class AlgorithmIdentifier : Asn1Encodable
{
	private readonly DerObjectIdentifier algorithm; // 0x10
	private readonly Asn1Encodable parameters; // 0x18

	public virtual DerObjectIdentifier Algorithm { get; }
	public virtual DerObjectIdentifier ObjectID { get; }
	public virtual Asn1Encodable Parameters { get; }

	// RVA: 0x65af2bc VA: 0x7598bc72bc
	public static AlgorithmIdentifier GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65af2d4 VA: 0x7598bc72d4
	public static AlgorithmIdentifier GetInstance(Object obj) { }
	// RVA: 0x65af528 VA: 0x7598bc7528
	public Void .ctor(DerObjectIdentifier algorithm) { }
	// RVA: 0x65af558 VA: 0x7598bc7558
	public Void .ctor(String algorithm) { }
	// RVA: 0x65af5dc VA: 0x7598bc75dc
	public Void .ctor(DerObjectIdentifier algorithm, Asn1Encodable parameters) { }
	// RVA: 0x65af378 VA: 0x7598bc7378
	internal Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65af620 VA: 0x7598bc7620
	public virtual DerObjectIdentifier get_Algorithm() { }
	// RVA: 0x65af628 VA: 0x7598bc7628
	public virtual DerObjectIdentifier get_ObjectID() { }
	// RVA: 0x65af630 VA: 0x7598bc7630
	public virtual Asn1Encodable get_Parameters() { }
	// RVA: 0x65af638 VA: 0x7598bc7638
	public override Asn1Object ToAsn1Object() { }
}
```
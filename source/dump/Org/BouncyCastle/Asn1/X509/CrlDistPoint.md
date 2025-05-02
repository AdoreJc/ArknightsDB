# CrlDistPoint

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class CrlDistPoint : Asn1Encodable
{
	internal readonly Asn1Sequence seq; // 0x10


	// RVA: 0x65b08f0 VA: 0x7598bc88f0
	public static CrlDistPoint GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b0908 VA: 0x7598bc8908
	public static CrlDistPoint GetInstance(Object obj) { }
	// RVA: 0x65b0aa0 VA: 0x7598bc8aa0
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b0ad0 VA: 0x7598bc8ad0
	public Void .ctor(DistributionPoint[] points) { }
	// RVA: 0x65b0b54 VA: 0x7598bc8b54
	public DistributionPoint[] GetDistributionPoints() { }
	// RVA: 0x65b0de4 VA: 0x7598bc8de4
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65b0dec VA: 0x7598bc8dec
	public override String ToString() { }
}
```
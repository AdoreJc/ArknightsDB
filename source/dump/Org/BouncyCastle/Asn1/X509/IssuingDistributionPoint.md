# IssuingDistributionPoint

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `Boolean OnlyContainsUserCerts`

- `Boolean OnlyContainsCACerts`

- `Boolean IsIndirectCrl`

- `Boolean OnlyContainsAttributeCerts`

- `DistributionPointName DistributionPoint`

- `ReasonFlags OnlySomeReasons`


## Methods

- `Boolean get_OnlyContainsUserCerts()`

- `Boolean get_OnlyContainsCACerts()`

- `Boolean get_IsIndirectCrl()`

- `Boolean get_OnlyContainsAttributeCerts()`

- `DistributionPointName get_DistributionPoint()`

- `ReasonFlags get_OnlySomeReasons()`

- `Void appendObject(StringBuilder, String, String, String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class IssuingDistributionPoint : Asn1Encodable
{
	private readonly DistributionPointName _distributionPoint; // 0x10
	private readonly Boolean _onlyContainsUserCerts; // 0x18
	private readonly Boolean _onlyContainsCACerts; // 0x19
	private readonly ReasonFlags _onlySomeReasons; // 0x20
	private readonly Boolean _indirectCRL; // 0x28
	private readonly Boolean _onlyContainsAttributeCerts; // 0x29
	private readonly Asn1Sequence seq; // 0x30

	public Boolean OnlyContainsUserCerts { get; }
	public Boolean OnlyContainsCACerts { get; }
	public Boolean IsIndirectCrl { get; }
	public Boolean OnlyContainsAttributeCerts { get; }
	public DistributionPointName DistributionPoint { get; }
	public ReasonFlags OnlySomeReasons { get; }

	// RVA: 0x65b4828 VA: 0x7598bcc828
	public static IssuingDistributionPoint GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b4840 VA: 0x7598bcc840
	public static IssuingDistributionPoint GetInstance(Object obj) { }
	// RVA: 0x65b4ca4 VA: 0x7598bccca4
	public Void .ctor(DistributionPointName distributionPoint, Boolean onlyContainsUserCerts, Boolean onlyContainsCACerts, ReasonFlags onlySomeReasons, Boolean indirectCRL, Boolean onlyContainsAttributeCerts) { }
	// RVA: 0x65b49c8 VA: 0x7598bcc9c8
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b51cc VA: 0x7598bcd1cc
	public Boolean get_OnlyContainsUserCerts() { }
	// RVA: 0x65b51d4 VA: 0x7598bcd1d4
	public Boolean get_OnlyContainsCACerts() { }
	// RVA: 0x65b51dc VA: 0x7598bcd1dc
	public Boolean get_IsIndirectCrl() { }
	// RVA: 0x65b51e4 VA: 0x7598bcd1e4
	public Boolean get_OnlyContainsAttributeCerts() { }
	// RVA: 0x65b51ec VA: 0x7598bcd1ec
	public DistributionPointName get_DistributionPoint() { }
	// RVA: 0x65b51f4 VA: 0x7598bcd1f4
	public ReasonFlags get_OnlySomeReasons() { }
	// RVA: 0x65b51fc VA: 0x7598bcd1fc
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65b5204 VA: 0x7598bcd204
	public override String ToString() { }
	// RVA: 0x65b54e8 VA: 0x7598bcd4e8
	private Void appendObject(StringBuilder buf, String sep, String name, String val) { }
}
```
# DistributionPoint

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `DistributionPointName DistributionPointName`

- `ReasonFlags Reasons`

- `GeneralNames CrlIssuer`


## Methods

- `DistributionPointName get_DistributionPointName()`

- `ReasonFlags get_Reasons()`

- `GeneralNames get_CrlIssuer()`

- `Void appendObject(StringBuilder, String, String, String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class DistributionPoint : Asn1Encodable
{
	internal readonly DistributionPointName distributionPoint; // 0x10
	internal readonly ReasonFlags reasons; // 0x18
	internal readonly GeneralNames cRLIssuer; // 0x20

	public DistributionPointName DistributionPointName { get; }
	public ReasonFlags Reasons { get; }
	public GeneralNames CrlIssuer { get; }

	// RVA: 0x65b1a40 VA: 0x7598bc9a40
	public static DistributionPoint GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b0c6c VA: 0x7598bc8c6c
	public static DistributionPoint GetInstance(Object obj) { }
	// RVA: 0x65b1a58 VA: 0x7598bc9a58
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b1cbc VA: 0x7598bc9cbc
	public Void .ctor(DistributionPointName distributionPointName, ReasonFlags reasons, GeneralNames crlIssuer) { }
	// RVA: 0x65b1d1c VA: 0x7598bc9d1c
	public DistributionPointName get_DistributionPointName() { }
	// RVA: 0x65b1d24 VA: 0x7598bc9d24
	public ReasonFlags get_Reasons() { }
	// RVA: 0x65b1d2c VA: 0x7598bc9d2c
	public GeneralNames get_CrlIssuer() { }
	// RVA: 0x65b1d34 VA: 0x7598bc9d34
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65b1fec VA: 0x7598bc9fec
	public override String ToString() { }
	// RVA: 0x65b21a8 VA: 0x7598bca1a8
	private Void appendObject(StringBuilder buf, String sep, String name, String val) { }
}
```
# DistributionPointName

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `Int32 PointType`

- `Asn1Encodable Name`


## Methods

- `Int32 get_PointType()`

- `Asn1Encodable get_Name()`

- `Void appendObject(StringBuilder, String, String, String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class DistributionPointName : Asn1Encodable, IAsn1Choice
{
	internal readonly Asn1Encodable name; // 0x10
	internal readonly Int32 type; // 0x18
	public const Int32 FullName; // 0x0
	public const Int32 NameRelativeToCrlIssuer; // 0x0

	public Int32 PointType { get; }
	public Asn1Encodable Name { get; }

	// RVA: 0x65b1bf8 VA: 0x7598bc9bf8
	public static DistributionPointName GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b22a0 VA: 0x7598bca2a0
	public static DistributionPointName GetInstance(Object obj) { }
	// RVA: 0x65b2488 VA: 0x7598bca488
	public Void .ctor(Int32 type, Asn1Encodable name) { }
	// RVA: 0x65b24c0 VA: 0x7598bca4c0
	public Void .ctor(GeneralNames name) { }
	// RVA: 0x65b24f4 VA: 0x7598bca4f4
	public Int32 get_PointType() { }
	// RVA: 0x65b24fc VA: 0x7598bca4fc
	public Asn1Encodable get_Name() { }
	// RVA: 0x65b2428 VA: 0x7598bca428
	public Void .ctor(Asn1TaggedObject obj) { }
	// RVA: 0x65b2504 VA: 0x7598bca504
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65b2578 VA: 0x7598bca578
	public override String ToString() { }
	// RVA: 0x65b26e4 VA: 0x7598bca6e4
	private Void appendObject(StringBuilder buf, String sep, String name, String val) { }
}
```
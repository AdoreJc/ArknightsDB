# X509Extensions

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `IEnumerable ExtensionOids`


## Methods

- `IEnumerator Oids()`

- `IEnumerable get_ExtensionOids()`

- `X509Extension GetExtension(DerObjectIdentifier)`

- `Boolean Equivalent(X509Extensions)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class X509Extensions : Asn1Encodable
{
	public static readonly DerObjectIdentifier SubjectDirectoryAttributes; // 0x0
	public static readonly DerObjectIdentifier SubjectKeyIdentifier; // 0x8
	public static readonly DerObjectIdentifier KeyUsage; // 0x10
	public static readonly DerObjectIdentifier PrivateKeyUsagePeriod; // 0x18
	public static readonly DerObjectIdentifier SubjectAlternativeName; // 0x20
	public static readonly DerObjectIdentifier IssuerAlternativeName; // 0x28
	public static readonly DerObjectIdentifier BasicConstraints; // 0x30
	public static readonly DerObjectIdentifier CrlNumber; // 0x38
	public static readonly DerObjectIdentifier ReasonCode; // 0x40
	public static readonly DerObjectIdentifier InstructionCode; // 0x48
	public static readonly DerObjectIdentifier InvalidityDate; // 0x50
	public static readonly DerObjectIdentifier DeltaCrlIndicator; // 0x58
	public static readonly DerObjectIdentifier IssuingDistributionPoint; // 0x60
	public static readonly DerObjectIdentifier CertificateIssuer; // 0x68
	public static readonly DerObjectIdentifier NameConstraints; // 0x70
	public static readonly DerObjectIdentifier CrlDistributionPoints; // 0x78
	public static readonly DerObjectIdentifier CertificatePolicies; // 0x80
	public static readonly DerObjectIdentifier PolicyMappings; // 0x88
	public static readonly DerObjectIdentifier AuthorityKeyIdentifier; // 0x90
	public static readonly DerObjectIdentifier PolicyConstraints; // 0x98
	public static readonly DerObjectIdentifier ExtendedKeyUsage; // 0xa0
	public static readonly DerObjectIdentifier FreshestCrl; // 0xa8
	public static readonly DerObjectIdentifier InhibitAnyPolicy; // 0xb0
	public static readonly DerObjectIdentifier AuthorityInfoAccess; // 0xb8
	public static readonly DerObjectIdentifier SubjectInfoAccess; // 0xc0
	public static readonly DerObjectIdentifier LogoType; // 0xc8
	public static readonly DerObjectIdentifier BiometricInfo; // 0xd0
	public static readonly DerObjectIdentifier QCStatements; // 0xd8
	public static readonly DerObjectIdentifier AuditIdentity; // 0xe0
	public static readonly DerObjectIdentifier NoRevAvail; // 0xe8
	public static readonly DerObjectIdentifier TargetInformation; // 0xf0
	private readonly IDictionary extensions; // 0x10
	private readonly IList ordering; // 0x18

	public IEnumerable ExtensionOids { get; }

	// RVA: 0x65b8984 VA: 0x7598bd0984
	public static X509Extensions GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b6a64 VA: 0x7598bcea64
	public static X509Extensions GetInstance(Object obj) { }
	// RVA: 0x65b89fc VA: 0x7598bd09fc
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b9160 VA: 0x7598bd1160
	public Void .ctor(IDictionary extensions) { }
	// RVA: 0x65b916c VA: 0x7598bd116c
	public Void .ctor(IList ordering, IDictionary extensions) { }
	// RVA: 0x65b96ec VA: 0x7598bd16ec
	public Void .ctor(IList oids, IList values) { }
	// RVA: 0x65b9c04 VA: 0x7598bd1c04
	public Void .ctor(Hashtable extensions) { }
	// RVA: 0x65b9c10 VA: 0x7598bd1c10
	public Void .ctor(ArrayList ordering, Hashtable extensions) { }
	// RVA: 0x65ba104 VA: 0x7598bd2104
	public Void .ctor(ArrayList oids, ArrayList values) { }
	// RVA: 0x65ba5c4 VA: 0x7598bd25c4
	public IEnumerator Oids() { }
	// RVA: 0x65ba66c VA: 0x7598bd266c
	public IEnumerable get_ExtensionOids() { }
	// RVA: 0x65ba6d4 VA: 0x7598bd26d4
	public X509Extension GetExtension(DerObjectIdentifier oid) { }
	// RVA: 0x65ba7c8 VA: 0x7598bd27c8
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65baf2c VA: 0x7598bd2f2c
	public Boolean Equivalent(X509Extensions other) { }
	// RVA: 0x65bb4fc VA: 0x7598bd34fc
	public DerObjectIdentifier[] GetExtensionOids() { }
	// RVA: 0x65bb684 VA: 0x7598bd3684
	public DerObjectIdentifier[] GetNonCriticalExtensionOids() { }
	// RVA: 0x65bbb98 VA: 0x7598bd3b98
	public DerObjectIdentifier[] GetCriticalExtensionOids() { }
	// RVA: 0x65bb68c VA: 0x7598bd368c
	private DerObjectIdentifier[] GetExtensionOids(Boolean isCritical) { }
	// RVA: 0x65bb554 VA: 0x7598bd3554
	private static DerObjectIdentifier[] ToOidArray(IList oids) { }
	// RVA: 0x65bbba0 VA: 0x7598bd3ba0
	private static Void .cctor() { }
}
```
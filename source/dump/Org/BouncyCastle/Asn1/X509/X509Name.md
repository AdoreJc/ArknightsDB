# X509Name

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Fields

- `IList values`

- `IList added`

- `Asn1Sequence seq`


## Methods

- `DerObjectIdentifier DecodeOid(String, IDictionary)`

- `IList GetOidList()`

- `IList GetValueList()`

- `IList GetValueList(DerObjectIdentifier)`

- `Boolean Equivalent(X509Name, Boolean)`

- `Boolean Equivalent(X509Name)`

- `Void AppendValue(StringBuilder, IDictionary, DerObjectIdentifier, String)`

- `String ToString(Boolean, IDictionary)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class X509Name : Asn1Encodable
{
	public static readonly DerObjectIdentifier C; // 0x0
	public static readonly DerObjectIdentifier O; // 0x8
	public static readonly DerObjectIdentifier OU; // 0x10
	public static readonly DerObjectIdentifier T; // 0x18
	public static readonly DerObjectIdentifier CN; // 0x20
	public static readonly DerObjectIdentifier Street; // 0x28
	public static readonly DerObjectIdentifier SerialNumber; // 0x30
	public static readonly DerObjectIdentifier L; // 0x38
	public static readonly DerObjectIdentifier ST; // 0x40
	public static readonly DerObjectIdentifier Surname; // 0x48
	public static readonly DerObjectIdentifier GivenName; // 0x50
	public static readonly DerObjectIdentifier Initials; // 0x58
	public static readonly DerObjectIdentifier Generation; // 0x60
	public static readonly DerObjectIdentifier UniqueIdentifier; // 0x68
	public static readonly DerObjectIdentifier BusinessCategory; // 0x70
	public static readonly DerObjectIdentifier PostalCode; // 0x78
	public static readonly DerObjectIdentifier DnQualifier; // 0x80
	public static readonly DerObjectIdentifier Pseudonym; // 0x88
	public static readonly DerObjectIdentifier DateOfBirth; // 0x90
	public static readonly DerObjectIdentifier PlaceOfBirth; // 0x98
	public static readonly DerObjectIdentifier Gender; // 0xa0
	public static readonly DerObjectIdentifier CountryOfCitizenship; // 0xa8
	public static readonly DerObjectIdentifier CountryOfResidence; // 0xb0
	public static readonly DerObjectIdentifier NameAtBirth; // 0xb8
	public static readonly DerObjectIdentifier PostalAddress; // 0xc0
	public static readonly DerObjectIdentifier DmdName; // 0xc8
	public static readonly DerObjectIdentifier TelephoneNumber; // 0xd0
	public static readonly DerObjectIdentifier Name; // 0xd8
	public static readonly DerObjectIdentifier EmailAddress; // 0xe0
	public static readonly DerObjectIdentifier UnstructuredName; // 0xe8
	public static readonly DerObjectIdentifier UnstructuredAddress; // 0xf0
	public static readonly DerObjectIdentifier E; // 0xf8
	public static readonly DerObjectIdentifier DC; // 0x100
	public static readonly DerObjectIdentifier UID; // 0x108
	private static readonly Boolean[] defaultReverse; // 0x110
	public static readonly Hashtable DefaultSymbols; // 0x118
	public static readonly Hashtable RFC2253Symbols; // 0x120
	public static readonly Hashtable RFC1779Symbols; // 0x128
	public static readonly Hashtable DefaultLookup; // 0x130
	private readonly IList ordering; // 0x10
	private readonly X509NameEntryConverter converter; // 0x18
	private IList values; // 0x20
	private IList added; // 0x28
	private Asn1Sequence seq; // 0x30

	public static Boolean DefaultReverse { get; set; }

	// RVA: 0x65bc434 VA: 0x7598bd4434
	public static Boolean get_DefaultReverse() { }
	// RVA: 0x65bc4a4 VA: 0x7598bd44a4
	public static Void set_DefaultReverse(Boolean value) { }
	// RVA: 0x65bc51c VA: 0x7598bd451c
	private static Void .cctor() { }
	// RVA: 0x65b381c VA: 0x7598bcb81c
	public static X509Name GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b39ec VA: 0x7598bcb9ec
	public static X509Name GetInstance(Object obj) { }
	// RVA: 0x65be9e0 VA: 0x7598bd69e0
	protected Void .ctor() { }
	// RVA: 0x65be044 VA: 0x7598bd6044
	protected Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65bea80 VA: 0x7598bd6a80
	public Void .ctor(IList ordering, IDictionary attributes) { }
	// RVA: 0x65beafc VA: 0x7598bd6afc
	public Void .ctor(IList ordering, IDictionary attributes, X509NameEntryConverter converter) { }
	// RVA: 0x65bf1c4 VA: 0x7598bd71c4
	public Void .ctor(IList oids, IList values) { }
	// RVA: 0x65bf240 VA: 0x7598bd7240
	public Void .ctor(IList oids, IList values, X509NameEntryConverter converter) { }
	// RVA: 0x65b3038 VA: 0x7598bcb038
	public Void .ctor(String dirName) { }
	// RVA: 0x65bf794 VA: 0x7598bd7794
	public Void .ctor(String dirName, X509NameEntryConverter converter) { }
	// RVA: 0x65c02f8 VA: 0x7598bd82f8
	public Void .ctor(Boolean reverse, String dirName) { }
	// RVA: 0x65c0370 VA: 0x7598bd8370
	public Void .ctor(Boolean reverse, String dirName, X509NameEntryConverter converter) { }
	// RVA: 0x65bf708 VA: 0x7598bd7708
	public Void .ctor(Boolean reverse, IDictionary lookUp, String dirName) { }
	// RVA: 0x65c03f8 VA: 0x7598bd83f8
	private DerObjectIdentifier DecodeOid(String name, IDictionary lookUp) { }
	// RVA: 0x65bf814 VA: 0x7598bd7814
	public Void .ctor(Boolean reverse, IDictionary lookUp, String dirName, X509NameEntryConverter converter) { }
	// RVA: 0x65c0904 VA: 0x7598bd8904
	public IList GetOidList() { }
	// RVA: 0x65c0960 VA: 0x7598bd8960
	public IList GetValueList() { }
	// RVA: 0x65c0968 VA: 0x7598bd8968
	public IList GetValueList(DerObjectIdentifier oid) { }
	// RVA: 0x65c0c60 VA: 0x7598bd8c60
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65c1338 VA: 0x7598bd9338
	public Boolean Equivalent(X509Name other, Boolean inOrder) { }
	// RVA: 0x65c17c0 VA: 0x7598bd97c0
	public Boolean Equivalent(X509Name other) { }
	// RVA: 0x65c1da0 VA: 0x7598bd9da0
	private static Boolean equivalentStrings(String s1, String s2) { }
	// RVA: 0x65c1e78 VA: 0x7598bd9e78
	private static String canonicalize(String s) { }
	// RVA: 0x65c2140 VA: 0x7598bda140
	private static Asn1Object decodeObject(String v) { }
	// RVA: 0x65c2044 VA: 0x7598bda044
	private static String stripInternalSpaces(String str) { }
	// RVA: 0x65c22b8 VA: 0x7598bda2b8
	private Void AppendValue(StringBuilder buf, IDictionary oidSymbols, DerObjectIdentifier oid, String val) { }
	// RVA: 0x65c258c VA: 0x7598bda58c
	public String ToString(Boolean reverse, IDictionary oidSymbols) { }
	// RVA: 0x65c2b68 VA: 0x7598bdab68
	public override String ToString() { }
}
```
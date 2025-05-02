# SignerInfo

**Namespace:** ` `


## Fields

- `Byte version`

- `String hashAlgorithm`

- `ArrayList authenticatedAttributes`

- `ArrayList unauthenticatedAttributes`

- `String issuer`


## Properties

- `String IssuerName`

- `ArrayList AuthenticatedAttributes`

- `String HashName`

- `ArrayList UnauthenticatedAttributes`

- `Byte Version`


## Methods

- `String get_IssuerName()`

- `ArrayList get_AuthenticatedAttributes()`

- `String get_HashName()`

- `Void set_HashName(String)`

- `ArrayList get_UnauthenticatedAttributes()`

- `Byte get_Version()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : 
public class SignerInfo
{
	private Byte version; // 0x10
	private String hashAlgorithm; // 0x18
	private ArrayList authenticatedAttributes; // 0x20
	private ArrayList unauthenticatedAttributes; // 0x28
	private Byte[] signature; // 0x30
	private String issuer; // 0x38
	private Byte[] serial; // 0x40
	private Byte[] ski; // 0x48

	public String IssuerName { get; }
	public Byte[] SerialNumber { get; }
	public ArrayList AuthenticatedAttributes { get; }
	public String HashName { get; set; }
	public Byte[] Signature { get; }
	public ArrayList UnauthenticatedAttributes { get; }
	public Byte Version { get; }

	// RVA: 0x5ed6578 VA: 0x75984ee578
	public Void .ctor() { }
	// RVA: 0x5ed61c8 VA: 0x75984ee1c8
	public Void .ctor(ASN1 asn1) { }
	// RVA: 0x5ed695c VA: 0x75984ee95c
	public String get_IssuerName() { }
	// RVA: 0x5ed6964 VA: 0x75984ee964
	public Byte[] get_SerialNumber() { }
	// RVA: 0x5ed69d8 VA: 0x75984ee9d8
	public ArrayList get_AuthenticatedAttributes() { }
	// RVA: 0x5ed69e0 VA: 0x75984ee9e0
	public String get_HashName() { }
	// RVA: 0x5ed69e8 VA: 0x75984ee9e8
	public Void set_HashName(String value) { }
	// RVA: 0x5ed69f0 VA: 0x75984ee9f0
	public Byte[] get_Signature() { }
	// RVA: 0x5ed6a64 VA: 0x75984eea64
	public ArrayList get_UnauthenticatedAttributes() { }
	// RVA: 0x5ed6a6c VA: 0x75984eea6c
	public Byte get_Version() { }
}
```
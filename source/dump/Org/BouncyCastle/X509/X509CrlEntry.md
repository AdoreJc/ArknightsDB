# X509CrlEntry

**Namespace:** `Org.BouncyCastle.X509`


## Fields

- `CrlEntry c`

- `Boolean isIndirect`

- `X509Name previousCertificateIssuer`

- `X509Name certificateIssuer`


## Properties

- `BigInteger SerialNumber`

- `DateTime RevocationDate`

- `Boolean HasExtensions`


## Methods

- `X509Name loadCertificateIssuer()`

- `X509Name GetCertificateIssuer()`

- `BigInteger get_SerialNumber()`

- `DateTime get_RevocationDate()`

- `Boolean get_HasExtensions()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.X509
public class X509CrlEntry : X509ExtensionBase
{
	private CrlEntry c; // 0x10
	private Boolean isIndirect; // 0x18
	private X509Name previousCertificateIssuer; // 0x20
	private X509Name certificateIssuer; // 0x28

	public BigInteger SerialNumber { get; }
	public DateTime RevocationDate { get; }
	public Boolean HasExtensions { get; }

	// RVA: 0x66e6520 VA: 0x7598cfe520
	public Void .ctor(CrlEntry c) { }
	// RVA: 0x66e4ab8 VA: 0x7598cfcab8
	public Void .ctor(CrlEntry c, Boolean isIndirect, X509Name previousCertificateIssuer) { }
	// RVA: 0x66e6568 VA: 0x7598cfe568
	private X509Name loadCertificateIssuer() { }
	// RVA: 0x66e6708 VA: 0x7598cfe708
	public X509Name GetCertificateIssuer() { }
	// RVA: 0x66e6710 VA: 0x7598cfe710
	protected override X509Extensions GetX509Extensions() { }
	// RVA: 0x66e672c VA: 0x7598cfe72c
	public Byte[] GetEncoded() { }
	// RVA: 0x66e6824 VA: 0x7598cfe824
	public BigInteger get_SerialNumber() { }
	// RVA: 0x66e6848 VA: 0x7598cfe848
	public DateTime get_RevocationDate() { }
	// RVA: 0x66e686c VA: 0x7598cfe86c
	public Boolean get_HasExtensions() { }
	// RVA: 0x66e6894 VA: 0x7598cfe894
	public override String ToString() { }
}
```
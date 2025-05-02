# X509CrlParser

**Namespace:** `Org.BouncyCastle.X509`


## Fields

- `Asn1Set sCrlData`

- `Int32 sCrlDataObjectCount`

- `Stream currentCrlStream`


## Methods

- `X509Crl ReadPemCrl(Stream)`

- `X509Crl ReadDerCrl(Asn1InputStream)`

- `X509Crl GetCrl()`

- `X509Crl ReadCrl(Byte[])`

- `ICollection ReadCrls(Byte[])`

- `X509Crl ReadCrl(Stream)`

- `ICollection ReadCrls(Stream)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.X509
public class X509CrlParser
{
	private static readonly PemParser PemCrlParser; // 0x0
	private readonly Boolean lazyAsn1; // 0x10
	private Asn1Set sCrlData; // 0x18
	private Int32 sCrlDataObjectCount; // 0x20
	private Stream currentCrlStream; // 0x28


	// RVA: 0x66e70a4 VA: 0x7598cff0a4
	public Void .ctor() { }
	// RVA: 0x66e70c0 VA: 0x7598cff0c0
	public Void .ctor(Boolean lazyAsn1) { }
	// RVA: 0x66e70e8 VA: 0x7598cff0e8
	private X509Crl ReadPemCrl(Stream inStream) { }
	// RVA: 0x66e718c VA: 0x7598cff18c
	private X509Crl ReadDerCrl(Asn1InputStream dIn) { }
	// RVA: 0x66e73b0 VA: 0x7598cff3b0
	private X509Crl GetCrl() { }
	// RVA: 0x66e7434 VA: 0x7598cff434
	protected virtual X509Crl CreateX509Crl(CertificateList c) { }
	// RVA: 0x66e7494 VA: 0x7598cff494
	public X509Crl ReadCrl(Byte[] input) { }
	// RVA: 0x66e789c VA: 0x7598cff89c
	public ICollection ReadCrls(Byte[] input) { }
	// RVA: 0x66e750c VA: 0x7598cff50c
	public X509Crl ReadCrl(Stream inStream) { }
	// RVA: 0x66e7914 VA: 0x7598cff914
	public ICollection ReadCrls(Stream inStream) { }
	// RVA: 0x66e7a20 VA: 0x7598cffa20
	private static Void .cctor() { }
}
```
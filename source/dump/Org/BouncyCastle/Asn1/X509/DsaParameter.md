# DsaParameter

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `BigInteger P`

- `BigInteger Q`

- `BigInteger G`


## Methods

- `BigInteger get_P()`

- `BigInteger get_Q()`

- `BigInteger get_G()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class DsaParameter : Asn1Encodable
{
	internal readonly DerInteger p; // 0x10
	internal readonly DerInteger q; // 0x18
	internal readonly DerInteger g; // 0x20

	public BigInteger P { get; }
	public BigInteger Q { get; }
	public BigInteger G { get; }

	// RVA: 0x65b27dc VA: 0x7598bca7dc
	public static DsaParameter GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b27f4 VA: 0x7598bca7f4
	public static DsaParameter GetInstance(Object obj) { }
	// RVA: 0x65b2ac8 VA: 0x7598bcaac8
	public Void .ctor(BigInteger p, BigInteger q, BigInteger g) { }
	// RVA: 0x65b296c VA: 0x7598bca96c
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b2bb4 VA: 0x7598bcabb4
	public BigInteger get_P() { }
	// RVA: 0x65b2bd0 VA: 0x7598bcabd0
	public BigInteger get_Q() { }
	// RVA: 0x65b2bec VA: 0x7598bcabec
	public BigInteger get_G() { }
	// RVA: 0x65b2c08 VA: 0x7598bcac08
	public override Asn1Object ToAsn1Object() { }
}
```
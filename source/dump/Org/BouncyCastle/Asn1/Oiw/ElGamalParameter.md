# ElGamalParameter

**Namespace:** `Org.BouncyCastle.Asn1.Oiw`


## Properties

- `BigInteger P`

- `BigInteger G`


## Methods

- `BigInteger get_P()`

- `BigInteger get_G()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Oiw
public class ElGamalParameter : Asn1Encodable
{
	internal DerInteger p; // 0x10
	internal DerInteger g; // 0x18

	public BigInteger P { get; }
	public BigInteger G { get; }

	// RVA: 0x65d887c VA: 0x7598bf087c
	public Void .ctor(BigInteger p, BigInteger g) { }
	// RVA: 0x65d8930 VA: 0x7598bf0930
	public Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65d8a2c VA: 0x7598bf0a2c
	public BigInteger get_P() { }
	// RVA: 0x65d8a48 VA: 0x7598bf0a48
	public BigInteger get_G() { }
	// RVA: 0x65d8a64 VA: 0x7598bf0a64
	public override Asn1Object ToAsn1Object() { }
}
```
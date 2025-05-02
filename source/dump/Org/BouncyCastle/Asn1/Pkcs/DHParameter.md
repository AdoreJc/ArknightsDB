# DHParameter

**Namespace:** `Org.BouncyCastle.Asn1.Pkcs`


## Properties

- `BigInteger P`

- `BigInteger G`

- `BigInteger L`


## Methods

- `BigInteger get_P()`

- `BigInteger get_G()`

- `BigInteger get_L()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Pkcs
public class DHParameter : Asn1Encodable
{
	internal DerInteger p; // 0x10
	internal DerInteger g; // 0x18
	internal DerInteger l; // 0x20

	public BigInteger P { get; }
	public BigInteger G { get; }
	public BigInteger L { get; }

	// RVA: 0x65d4b04 VA: 0x7598becb04
	public Void .ctor(BigInteger p, BigInteger g, Int32 l) { }
	// RVA: 0x65d4c08 VA: 0x7598becc08
	public Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65d5010 VA: 0x7598bed010
	public BigInteger get_P() { }
	// RVA: 0x65d502c VA: 0x7598bed02c
	public BigInteger get_G() { }
	// RVA: 0x65d5048 VA: 0x7598bed048
	public BigInteger get_L() { }
	// RVA: 0x65d505c VA: 0x7598bed05c
	public override Asn1Object ToAsn1Object() { }
}
```
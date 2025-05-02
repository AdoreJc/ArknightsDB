# RsaPublicKeyStructure

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Fields

- `BigInteger modulus`

- `BigInteger publicExponent`


## Properties

- `BigInteger Modulus`

- `BigInteger PublicExponent`


## Methods

- `BigInteger get_Modulus()`

- `BigInteger get_PublicExponent()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class RsaPublicKeyStructure : Asn1Encodable
{
	private BigInteger modulus; // 0x10
	private BigInteger publicExponent; // 0x18

	public BigInteger Modulus { get; }
	public BigInteger PublicExponent { get; }

	// RVA: 0x65b5918 VA: 0x7598bcd918
	public static RsaPublicKeyStructure GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b5930 VA: 0x7598bcd930
	public static RsaPublicKeyStructure GetInstance(Object obj) { }
	// RVA: 0x65b5be0 VA: 0x7598bcdbe0
	public Void .ctor(BigInteger modulus, BigInteger publicExponent) { }
	// RVA: 0x65b5aa8 VA: 0x7598bcdaa8
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b5d34 VA: 0x7598bcdd34
	public BigInteger get_Modulus() { }
	// RVA: 0x65b5d3c VA: 0x7598bcdd3c
	public BigInteger get_PublicExponent() { }
	// RVA: 0x65b5d44 VA: 0x7598bcdd44
	public override Asn1Object ToAsn1Object() { }
}
```
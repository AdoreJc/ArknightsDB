# Gost3410ParamSetParameters

**Namespace:** `Org.BouncyCastle.Asn1.CryptoPro`


## Properties

- `Int32 KeySize`

- `BigInteger P`

- `BigInteger Q`

- `BigInteger A`


## Methods

- `Int32 get_KeySize()`

- `BigInteger get_P()`

- `BigInteger get_Q()`

- `BigInteger get_A()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.CryptoPro
public class Gost3410ParamSetParameters : Asn1Encodable
{
	private readonly Int32 keySize; // 0x10
	private readonly DerInteger p; // 0x18
	private readonly DerInteger q; // 0x20
	private readonly DerInteger a; // 0x28

	public Int32 KeySize { get; }
	public BigInteger P { get; }
	public BigInteger Q { get; }
	public BigInteger A { get; }

	// RVA: 0x65df208 VA: 0x7598bf7208
	public static Gost3410ParamSetParameters GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65df220 VA: 0x7598bf7220
	public static Gost3410ParamSetParameters GetInstance(Object obj) { }
	// RVA: 0x65debe4 VA: 0x7598bf6be4
	public Void .ctor(Int32 keySize, BigInteger p, BigInteger q, BigInteger a) { }
	// RVA: 0x65df398 VA: 0x7598bf7398
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65df4f8 VA: 0x7598bf74f8
	public Int32 get_KeySize() { }
	// RVA: 0x65df500 VA: 0x7598bf7500
	public BigInteger get_P() { }
	// RVA: 0x65df51c VA: 0x7598bf751c
	public BigInteger get_Q() { }
	// RVA: 0x65df538 VA: 0x7598bf7538
	public BigInteger get_A() { }
	// RVA: 0x65df554 VA: 0x7598bf7554
	public override Asn1Object ToAsn1Object() { }
}
```
# ECDomainParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `ECCurve Curve`

- `ECPoint G`

- `BigInteger N`

- `BigInteger H`


## Methods

- `ECCurve get_Curve()`

- `ECPoint get_G()`

- `BigInteger get_N()`

- `BigInteger get_H()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ECDomainParameters
{
	internal ECCurve curve; // 0x10
	internal Byte[] seed; // 0x18
	internal ECPoint g; // 0x20
	internal BigInteger n; // 0x28
	internal BigInteger h; // 0x30

	public ECCurve Curve { get; }
	public ECPoint G { get; }
	public BigInteger N { get; }
	public BigInteger H { get; }

	// RVA: 0x6516c7c VA: 0x7598b2ec7c
	public Void .ctor(ECCurve curve, ECPoint g, BigInteger n) { }
	// RVA: 0x6516d08 VA: 0x7598b2ed08
	public Void .ctor(ECCurve curve, ECPoint g, BigInteger n, BigInteger h) { }
	// RVA: 0x6516d10 VA: 0x7598b2ed10
	public Void .ctor(ECCurve curve, ECPoint g, BigInteger n, BigInteger h, Byte[] seed) { }
	// RVA: 0x6516e88 VA: 0x7598b2ee88
	public ECCurve get_Curve() { }
	// RVA: 0x6516e90 VA: 0x7598b2ee90
	public ECPoint get_G() { }
	// RVA: 0x6516e98 VA: 0x7598b2ee98
	public BigInteger get_N() { }
	// RVA: 0x6516ea0 VA: 0x7598b2eea0
	public BigInteger get_H() { }
	// RVA: 0x6516ea8 VA: 0x7598b2eea8
	public Byte[] GetSeed() { }
	// RVA: 0x6516eb4 VA: 0x7598b2eeb4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6516f58 VA: 0x7598b2ef58
	protected virtual Boolean Equals(ECDomainParameters other) { }
	// RVA: 0x6516ffc VA: 0x7598b2effc
	public override Int32 GetHashCode() { }
}
```
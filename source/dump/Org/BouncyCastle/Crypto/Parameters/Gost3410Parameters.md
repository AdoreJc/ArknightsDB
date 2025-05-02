# Gost3410Parameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger P`

- `BigInteger Q`

- `BigInteger A`

- `Gost3410ValidationParameters ValidationParameters`


## Methods

- `BigInteger get_P()`

- `BigInteger get_Q()`

- `BigInteger get_A()`

- `Gost3410ValidationParameters get_ValidationParameters()`

- `Boolean Equals(Gost3410Parameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class Gost3410Parameters : ICipherParameters
{
	private readonly BigInteger p; // 0x10
	private readonly BigInteger q; // 0x18
	private readonly BigInteger a; // 0x20
	private readonly Gost3410ValidationParameters validation; // 0x28

	public BigInteger P { get; }
	public BigInteger Q { get; }
	public BigInteger A { get; }
	public Gost3410ValidationParameters ValidationParameters { get; }

	// RVA: 0x6518dc4 VA: 0x7598b30dc4
	public Void .ctor(BigInteger p, BigInteger q, BigInteger a) { }
	// RVA: 0x6518dcc VA: 0x7598b30dcc
	public Void .ctor(BigInteger p, BigInteger q, BigInteger a, Gost3410ValidationParameters validation) { }
	// RVA: 0x6518ee0 VA: 0x7598b30ee0
	public BigInteger get_P() { }
	// RVA: 0x6518ee8 VA: 0x7598b30ee8
	public BigInteger get_Q() { }
	// RVA: 0x6518ef0 VA: 0x7598b30ef0
	public BigInteger get_A() { }
	// RVA: 0x6518ef8 VA: 0x7598b30ef8
	public Gost3410ValidationParameters get_ValidationParameters() { }
	// RVA: 0x6518f00 VA: 0x7598b30f00
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6518f9c VA: 0x7598b30f9c
	protected Boolean Equals(Gost3410Parameters other) { }
	// RVA: 0x651901c VA: 0x7598b3101c
	public override Int32 GetHashCode() { }
}
```
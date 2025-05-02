# ElGamalParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger P`

- `BigInteger G`

- `Int32 L`


## Methods

- `BigInteger get_P()`

- `BigInteger get_G()`

- `Int32 get_L()`

- `Boolean Equals(ElGamalParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ElGamalParameters : ICipherParameters
{
	private readonly BigInteger p; // 0x10
	private readonly BigInteger g; // 0x18
	private readonly Int32 l; // 0x20

	public BigInteger P { get; }
	public BigInteger G { get; }
	public Int32 L { get; }

	// RVA: 0x65185bc VA: 0x7598b305bc
	public Void .ctor(BigInteger p, BigInteger g) { }
	// RVA: 0x65185c4 VA: 0x7598b305c4
	public Void .ctor(BigInteger p, BigInteger g, Int32 l) { }
	// RVA: 0x6518694 VA: 0x7598b30694
	public BigInteger get_P() { }
	// RVA: 0x651869c VA: 0x7598b3069c
	public BigInteger get_G() { }
	// RVA: 0x65186a4 VA: 0x7598b306a4
	public Int32 get_L() { }
	// RVA: 0x65186ac VA: 0x7598b306ac
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6518748 VA: 0x7598b30748
	protected Boolean Equals(ElGamalParameters other) { }
	// RVA: 0x65187bc VA: 0x7598b307bc
	public override Int32 GetHashCode() { }
}
```
# DsaParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger P`

- `BigInteger Q`

- `BigInteger G`

- `DsaValidationParameters ValidationParameters`


## Methods

- `BigInteger get_P()`

- `BigInteger get_Q()`

- `BigInteger get_G()`

- `DsaValidationParameters get_ValidationParameters()`

- `Boolean Equals(DsaParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DsaParameters : ICipherParameters
{
	private readonly BigInteger p; // 0x10
	private readonly BigInteger q; // 0x18
	private readonly BigInteger g; // 0x20
	private readonly DsaValidationParameters validation; // 0x28

	public BigInteger P { get; }
	public BigInteger Q { get; }
	public BigInteger G { get; }
	public DsaValidationParameters ValidationParameters { get; }

	// RVA: 0x6516340 VA: 0x7598b2e340
	public Void .ctor(BigInteger p, BigInteger q, BigInteger g) { }
	// RVA: 0x6516348 VA: 0x7598b2e348
	public Void .ctor(BigInteger p, BigInteger q, BigInteger g, DsaValidationParameters parameters) { }
	// RVA: 0x651645c VA: 0x7598b2e45c
	public BigInteger get_P() { }
	// RVA: 0x6516464 VA: 0x7598b2e464
	public BigInteger get_Q() { }
	// RVA: 0x651646c VA: 0x7598b2e46c
	public BigInteger get_G() { }
	// RVA: 0x6516474 VA: 0x7598b2e474
	public DsaValidationParameters get_ValidationParameters() { }
	// RVA: 0x651647c VA: 0x7598b2e47c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6516518 VA: 0x7598b2e518
	protected Boolean Equals(DsaParameters other) { }
	// RVA: 0x6516598 VA: 0x7598b2e598
	public override Int32 GetHashCode() { }
}
```
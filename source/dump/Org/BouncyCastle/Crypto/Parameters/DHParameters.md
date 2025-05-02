# DHParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger P`

- `BigInteger G`

- `BigInteger Q`

- `BigInteger J`

- `Int32 M`

- `Int32 L`

- `DHValidationParameters ValidationParameters`


## Methods

- `BigInteger get_P()`

- `BigInteger get_G()`

- `BigInteger get_Q()`

- `BigInteger get_J()`

- `Int32 get_M()`

- `Int32 get_L()`

- `DHValidationParameters get_ValidationParameters()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DHParameters : ICipherParameters
{
	private const Int32 DefaultMinimumLength; // 0x0
	private readonly BigInteger p; // 0x10
	private readonly BigInteger g; // 0x18
	private readonly BigInteger q; // 0x20
	private readonly BigInteger j; // 0x28
	private readonly Int32 m; // 0x30
	private readonly Int32 l; // 0x34
	private readonly DHValidationParameters validation; // 0x38

	public BigInteger P { get; }
	public BigInteger G { get; }
	public BigInteger Q { get; }
	public BigInteger J { get; }
	public Int32 M { get; }
	public Int32 L { get; }
	public DHValidationParameters ValidationParameters { get; }

	// RVA: 0x6515344 VA: 0x7598b2d344
	private static Int32 GetDefaultMParam(Int32 lParam) { }
	// RVA: 0x65153b4 VA: 0x7598b2d3b4
	public Void .ctor(BigInteger p, BigInteger g) { }
	// RVA: 0x651548c VA: 0x7598b2d48c
	public Void .ctor(BigInteger p, BigInteger g, BigInteger q) { }
	// RVA: 0x6515428 VA: 0x7598b2d428
	public Void .ctor(BigInteger p, BigInteger g, BigInteger q, Int32 l) { }
	// RVA: 0x65158d4 VA: 0x7598b2d8d4
	public Void .ctor(BigInteger p, BigInteger g, BigInteger q, Int32 m, Int32 l) { }
	// RVA: 0x65158f4 VA: 0x7598b2d8f4
	public Void .ctor(BigInteger p, BigInteger g, BigInteger q, BigInteger j, DHValidationParameters validation) { }
	// RVA: 0x6515504 VA: 0x7598b2d504
	public Void .ctor(BigInteger p, BigInteger g, BigInteger q, Int32 m, Int32 l, BigInteger j, DHValidationParameters validation) { }
	// RVA: 0x651591c VA: 0x7598b2d91c
	public BigInteger get_P() { }
	// RVA: 0x6515924 VA: 0x7598b2d924
	public BigInteger get_G() { }
	// RVA: 0x651592c VA: 0x7598b2d92c
	public BigInteger get_Q() { }
	// RVA: 0x6515934 VA: 0x7598b2d934
	public BigInteger get_J() { }
	// RVA: 0x651593c VA: 0x7598b2d93c
	public Int32 get_M() { }
	// RVA: 0x6515944 VA: 0x7598b2d944
	public Int32 get_L() { }
	// RVA: 0x651594c VA: 0x7598b2d94c
	public DHValidationParameters get_ValidationParameters() { }
	// RVA: 0x6515954 VA: 0x7598b2d954
	public override Boolean Equals(Object obj) { }
	// RVA: 0x65159f8 VA: 0x7598b2d9f8
	protected virtual Boolean Equals(DHParameters other) { }
	// RVA: 0x6515a70 VA: 0x7598b2da70
	public override Int32 GetHashCode() { }
}
```
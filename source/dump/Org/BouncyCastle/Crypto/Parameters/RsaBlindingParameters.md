# RsaBlindingParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `RsaKeyParameters PublicKey`

- `BigInteger BlindingFactor`


## Methods

- `RsaKeyParameters get_PublicKey()`

- `BigInteger get_BlindingFactor()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class RsaBlindingParameters : ICipherParameters
{
	private readonly RsaKeyParameters publicKey; // 0x10
	private readonly BigInteger blindingFactor; // 0x18

	public RsaKeyParameters PublicKey { get; }
	public BigInteger BlindingFactor { get; }

	// RVA: 0x651a248 VA: 0x7598b32248
	public Void .ctor(RsaKeyParameters publicKey, BigInteger blindingFactor) { }
	// RVA: 0x651a2e8 VA: 0x7598b322e8
	public RsaKeyParameters get_PublicKey() { }
	// RVA: 0x651a2f0 VA: 0x7598b322f0
	public BigInteger get_BlindingFactor() { }
}
```
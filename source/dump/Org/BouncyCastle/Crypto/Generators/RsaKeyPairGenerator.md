# RsaKeyPairGenerator

**Namespace:** `Org.BouncyCastle.Crypto.Generators`


## Fields

- `RsaKeyGenerationParameters parameters`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Generators
public class RsaKeyPairGenerator : IAsymmetricCipherKeyPairGenerator
{
	private static readonly Int32[] SPECIAL_E_VALUES; // 0x0
	private static readonly Int32 SPECIAL_E_HIGHEST; // 0x8
	private static readonly Int32 SPECIAL_E_BITS; // 0xc
	protected static readonly BigInteger One; // 0x10
	protected static readonly BigInteger DefaultPublicExponent; // 0x18
	protected const Int32 DefaultTests; // 0x0
	protected RsaKeyGenerationParameters parameters; // 0x10


	// RVA: 0x65381b0 VA: 0x7598b501b0
	public virtual Void Init(KeyGenerationParameters parameters) { }
	// RVA: 0x65382d8 VA: 0x7598b502d8
	public virtual AsymmetricCipherKeyPair GenerateKeyPair() { }
	// RVA: 0x6538644 VA: 0x7598b50644
	protected virtual BigInteger ChooseRandomPrime(Int32 bitlength, BigInteger e) { }
	// RVA: 0x6538848 VA: 0x7598b50848
	public Void .ctor() { }
	// RVA: 0x6538850 VA: 0x7598b50850
	private static Void .cctor() { }
}
```
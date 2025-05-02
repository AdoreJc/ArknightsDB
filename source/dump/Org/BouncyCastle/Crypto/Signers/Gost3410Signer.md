# Gost3410Signer

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `Gost3410KeyParameters key`

- `SecureRandom random`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class Gost3410Signer : IDsa
{
	private Gost3410KeyParameters key; // 0x10
	private SecureRandom random; // 0x18

	public virtual String AlgorithmName { get; }

	// RVA: 0x650cb50 VA: 0x7598b24b50
	public virtual String get_AlgorithmName() { }
	// RVA: 0x650cb90 VA: 0x7598b24b90
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x650cd9c VA: 0x7598b24d9c
	public virtual BigInteger[] GenerateSignature(Byte[] message) { }
	// RVA: 0x650d064 VA: 0x7598b25064
	public virtual Boolean VerifySignature(Byte[] message, BigInteger r, BigInteger s) { }
	// RVA: 0x650d34c VA: 0x7598b2534c
	public Void .ctor() { }
}
```
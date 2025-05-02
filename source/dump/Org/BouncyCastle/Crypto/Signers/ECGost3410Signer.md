# ECGost3410Signer

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `ECKeyParameters key`

- `SecureRandom random`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class ECGost3410Signer : IDsa
{
	private ECKeyParameters key; // 0x10
	private SecureRandom random; // 0x18

	public virtual String AlgorithmName { get; }

	// RVA: 0x6509f7c VA: 0x7598b21f7c
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6509fbc VA: 0x7598b21fbc
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x650a1c8 VA: 0x7598b221c8
	public virtual BigInteger[] GenerateSignature(Byte[] message) { }
	// RVA: 0x650a56c VA: 0x7598b2256c
	public virtual Boolean VerifySignature(Byte[] message, BigInteger r, BigInteger s) { }
	// RVA: 0x650a860 VA: 0x7598b22860
	protected virtual ECMultiplier CreateBasePointMultiplier() { }
	// RVA: 0x650a8bc VA: 0x7598b228bc
	public Void .ctor() { }
}
```
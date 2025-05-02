# ECNRSigner

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `Boolean forSigning`

- `ECKeyParameters key`

- `SecureRandom random`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class ECNRSigner : IDsa
{
	private Boolean forSigning; // 0x10
	private ECKeyParameters key; // 0x18
	private SecureRandom random; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x650a8c4 VA: 0x7598b228c4
	public virtual String get_AlgorithmName() { }
	// RVA: 0x650a904 VA: 0x7598b22904
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x650ab18 VA: 0x7598b22b18
	public virtual BigInteger[] GenerateSignature(Byte[] message) { }
	// RVA: 0x650af30 VA: 0x7598b22f30
	public virtual Boolean VerifySignature(Byte[] message, BigInteger r, BigInteger s) { }
	// RVA: 0x650b208 VA: 0x7598b23208
	public Void .ctor() { }
}
```
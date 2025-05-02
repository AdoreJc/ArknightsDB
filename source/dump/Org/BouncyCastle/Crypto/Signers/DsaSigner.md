# DsaSigner

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `DsaKeyParameters key`

- `SecureRandom random`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class DsaSigner : IDsa
{
	protected readonly IDsaKCalculator kCalculator; // 0x10
	protected DsaKeyParameters key; // 0x18
	protected SecureRandom random; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x650865c VA: 0x7598b2065c
	public Void .ctor() { }
	// RVA: 0x65086d8 VA: 0x7598b206d8
	public Void .ctor(IDsaKCalculator kCalculator) { }
	// RVA: 0x6508708 VA: 0x7598b20708
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6508748 VA: 0x7598b20748
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x65089f4 VA: 0x7598b209f4
	public virtual BigInteger[] GenerateSignature(Byte[] message) { }
	// RVA: 0x6508dc0 VA: 0x7598b20dc0
	public virtual Boolean VerifySignature(Byte[] message, BigInteger r, BigInteger s) { }
	// RVA: 0x6508fd8 VA: 0x7598b20fd8
	protected virtual BigInteger CalculateE(BigInteger n, Byte[] message) { }
	// RVA: 0x65090b8 VA: 0x7598b210b8
	protected virtual SecureRandom InitSecureRandom(Boolean needed, SecureRandom provided) { }
}
```
# ECDsaSigner

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `ECKeyParameters key`

- `SecureRandom random`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class ECDsaSigner : IDsa
{
	private static readonly BigInteger Eight; // 0x0
	protected readonly IDsaKCalculator kCalculator; // 0x10
	protected ECKeyParameters key; // 0x18
	protected SecureRandom random; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x650912c VA: 0x7598b2112c
	public Void .ctor() { }
	// RVA: 0x65091a0 VA: 0x7598b211a0
	public Void .ctor(IDsaKCalculator kCalculator) { }
	// RVA: 0x65091d0 VA: 0x7598b211d0
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6509210 VA: 0x7598b21210
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x65094bc VA: 0x7598b214bc
	public virtual BigInteger[] GenerateSignature(Byte[] message) { }
	// RVA: 0x6509950 VA: 0x7598b21950
	public virtual Boolean VerifySignature(Byte[] message, BigInteger r, BigInteger s) { }
	// RVA: 0x6509cd4 VA: 0x7598b21cd4
	protected virtual BigInteger CalculateE(BigInteger n, Byte[] message) { }
	// RVA: 0x6509d94 VA: 0x7598b21d94
	protected virtual ECMultiplier CreateBasePointMultiplier() { }
	// RVA: 0x6509df0 VA: 0x7598b21df0
	protected virtual ECFieldElement GetDenominator(Int32 coordinateSystem, ECPoint p) { }
	// RVA: 0x6509e84 VA: 0x7598b21e84
	protected virtual SecureRandom InitSecureRandom(Boolean needed, SecureRandom provided) { }
	// RVA: 0x6509ef8 VA: 0x7598b21ef8
	private static Void .cctor() { }
}
```
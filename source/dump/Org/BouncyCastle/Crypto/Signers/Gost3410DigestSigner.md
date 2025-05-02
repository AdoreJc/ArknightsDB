# Gost3410DigestSigner

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `Boolean forSigning`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class Gost3410DigestSigner : ISigner
{
	private readonly IDigest digest; // 0x10
	private readonly IDsa dsaSigner; // 0x18
	private Boolean forSigning; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x650be84 VA: 0x7598b23e84
	public Void .ctor(IDsa signer, IDigest digest) { }
	// RVA: 0x650bec8 VA: 0x7598b23ec8
	public virtual String get_AlgorithmName() { }
	// RVA: 0x650c008 VA: 0x7598b24008
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x650c230 VA: 0x7598b24230
	public virtual Void Update(Byte input) { }
	// RVA: 0x650c2dc VA: 0x7598b242dc
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x650c3a0 VA: 0x7598b243a0
	public virtual Byte[] GenerateSignature() { }
	// RVA: 0x650c758 VA: 0x7598b24758
	public virtual Boolean VerifySignature(Byte[] signature) { }
	// RVA: 0x650caac VA: 0x7598b24aac
	public virtual Void Reset() { }
}
```
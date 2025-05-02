# GenericSigner

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `Boolean forSigning`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class GenericSigner : ISigner
{
	private readonly IAsymmetricBlockCipher engine; // 0x10
	private readonly IDigest digest; // 0x18
	private Boolean forSigning; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x64ff0a8 VA: 0x7598b170a8
	public Void .ctor(IAsymmetricBlockCipher engine, IDigest digest) { }
	// RVA: 0x650b210 VA: 0x7598b23210
	public virtual String get_AlgorithmName() { }
	// RVA: 0x650b4f0 VA: 0x7598b234f0
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x650b718 VA: 0x7598b23718
	public virtual Void Update(Byte input) { }
	// RVA: 0x650b7c4 VA: 0x7598b237c4
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x650b888 VA: 0x7598b23888
	public virtual Byte[] GenerateSignature() { }
	// RVA: 0x650baa8 VA: 0x7598b23aa8
	public virtual Boolean VerifySignature(Byte[] signature) { }
	// RVA: 0x650bde0 VA: 0x7598b23de0
	public virtual Void Reset() { }
}
```
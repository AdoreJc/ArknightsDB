# RsaDigestSigner

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `Boolean forSigning`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class RsaDigestSigner : ISigner
{
	private readonly IAsymmetricBlockCipher rsaEngine; // 0x10
	private readonly AlgorithmIdentifier algId; // 0x18
	private readonly IDigest digest; // 0x20
	private Boolean forSigning; // 0x28
	private static readonly IDictionary oidMap; // 0x0

	public virtual String AlgorithmName { get; }

	// RVA: 0x6511914 VA: 0x7598b29914
	private static Void .cctor() { }
	// RVA: 0x65120d4 VA: 0x7598b2a0d4
	public Void .ctor(IDigest digest) { }
	// RVA: 0x64feff8 VA: 0x7598b16ff8
	public Void .ctor(IDigest digest, DerObjectIdentifier digestOid) { }
	// RVA: 0x6512280 VA: 0x7598b2a280
	public Void .ctor(IDigest digest, AlgorithmIdentifier algId) { }
	// RVA: 0x6512354 VA: 0x7598b2a354
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6512414 VA: 0x7598b2a414
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x651263c VA: 0x7598b2a63c
	public virtual Void Update(Byte input) { }
	// RVA: 0x65126e8 VA: 0x7598b2a6e8
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x65127ac VA: 0x7598b2a7ac
	public virtual Byte[] GenerateSignature() { }
	// RVA: 0x6512a64 VA: 0x7598b2aa64
	public virtual Boolean VerifySignature(Byte[] signature) { }
	// RVA: 0x6512e64 VA: 0x7598b2ae64
	public virtual Void Reset() { }
	// RVA: 0x65129dc VA: 0x7598b2a9dc
	private Byte[] DerEncode(Byte[] hash) { }
}
```
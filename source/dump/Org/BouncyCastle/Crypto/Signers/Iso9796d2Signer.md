# Iso9796d2Signer

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `IDigest digest`

- `IAsymmetricBlockCipher cipher`

- `Int32 trailer`

- `Int32 keyBits`

- `Int32 messageLength`

- `Boolean fullMessage`


## Methods

- `Boolean IsSameAs(Byte[], Byte[])`

- `Void ClearBlock(Byte[])`

- `Boolean ReturnFalse(Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class Iso9796d2Signer : ISignerWithRecovery, ISigner
{
	public const Int32 TrailerImplicit; // 0x0
	public const Int32 TrailerRipeMD160; // 0x0
	public const Int32 TrailerRipeMD128; // 0x0
	public const Int32 TrailerSha1; // 0x0
	public const Int32 TrailerSha256; // 0x0
	public const Int32 TrailerSha512; // 0x0
	public const Int32 TrailerSha384; // 0x0
	public const Int32 TrailerWhirlpool; // 0x0
	private IDigest digest; // 0x10
	private IAsymmetricBlockCipher cipher; // 0x18
	private Int32 trailer; // 0x20
	private Int32 keyBits; // 0x24
	private Byte[] block; // 0x28
	private Byte[] mBuf; // 0x30
	private Int32 messageLength; // 0x38
	private Boolean fullMessage; // 0x3c
	private Byte[] recoveredMessage; // 0x40
	private Byte[] preSig; // 0x48
	private Byte[] preBlock; // 0x50

	public virtual String AlgorithmName { get; }

	// RVA: 0x650dc50 VA: 0x7598b25c50
	public Byte[] GetRecoveredMessage() { }
	// RVA: 0x650dc58 VA: 0x7598b25c58
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest digest, Boolean isImplicit) { }
	// RVA: 0x650e054 VA: 0x7598b26054
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest digest) { }
	// RVA: 0x650e05c VA: 0x7598b2605c
	public virtual String get_AlgorithmName() { }
	// RVA: 0x650e11c VA: 0x7598b2611c
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x650e350 VA: 0x7598b26350
	private Boolean IsSameAs(Byte[] a, Byte[] b) { }
	// RVA: 0x650e400 VA: 0x7598b26400
	private Void ClearBlock(Byte[] block) { }
	// RVA: 0x650e424 VA: 0x7598b26424
	public virtual Void UpdateWithRecoveredMessage(Byte[] signature) { }
	// RVA: 0x650e8e0 VA: 0x7598b268e0
	public virtual Void Update(Byte input) { }
	// RVA: 0x650e9c8 VA: 0x7598b269c8
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x650eafc VA: 0x7598b26afc
	public virtual Void Reset() { }
	// RVA: 0x650ec0c VA: 0x7598b26c0c
	public virtual Byte[] GenerateSignature() { }
	// RVA: 0x650efe8 VA: 0x7598b26fe8
	public virtual Boolean VerifySignature(Byte[] signature) { }
	// RVA: 0x650f790 VA: 0x7598b27790
	private Boolean ReturnFalse(Byte[] block) { }
	// RVA: 0x650f7b8 VA: 0x7598b277b8
	public virtual Boolean HasFullMessage() { }
}
```
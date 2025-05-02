# X931Signer

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `IDigest digest`

- `IAsymmetricBlockCipher cipher`

- `RsaKeyParameters kParam`

- `Int32 trailer`

- `Int32 keyBits`


## Methods

- `Void ClearBlock(Byte[])`

- `Void CreateSignatureBlock()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class X931Signer : ISigner
{
	public const Int32 TRAILER_IMPLICIT; // 0x0
	public const Int32 TRAILER_RIPEMD160; // 0x0
	public const Int32 TRAILER_RIPEMD128; // 0x0
	public const Int32 TRAILER_SHA1; // 0x0
	public const Int32 TRAILER_SHA256; // 0x0
	public const Int32 TRAILER_SHA512; // 0x0
	public const Int32 TRAILER_SHA384; // 0x0
	public const Int32 TRAILER_WHIRLPOOL; // 0x0
	public const Int32 TRAILER_SHA224; // 0x0
	private IDigest digest; // 0x10
	private IAsymmetricBlockCipher cipher; // 0x18
	private RsaKeyParameters kParam; // 0x20
	private Int32 trailer; // 0x28
	private Int32 keyBits; // 0x2c
	private Byte[] block; // 0x30

	public virtual String AlgorithmName { get; }

	// RVA: 0x6512f08 VA: 0x7598b2af08
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest digest, Boolean isImplicit) { }
	// RVA: 0x651302c VA: 0x7598b2b02c
	public virtual String get_AlgorithmName() { }
	// RVA: 0x651318c VA: 0x7598b2b18c
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest digest) { }
	// RVA: 0x6513194 VA: 0x7598b2b194
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x6513350 VA: 0x7598b2b350
	private Void ClearBlock(Byte[] block) { }
	// RVA: 0x6513374 VA: 0x7598b2b374
	public virtual Void Update(Byte b) { }
	// RVA: 0x6513420 VA: 0x7598b2b420
	public virtual Void BlockUpdate(Byte[] input, Int32 off, Int32 len) { }
	// RVA: 0x65134e4 VA: 0x7598b2b4e4
	public virtual Void Reset() { }
	// RVA: 0x6513588 VA: 0x7598b2b588
	public virtual Byte[] GenerateSignature() { }
	// RVA: 0x6513700 VA: 0x7598b2b700
	private Void CreateSignatureBlock() { }
	// RVA: 0x6513980 VA: 0x7598b2b980
	public virtual Boolean VerifySignature(Byte[] signature) { }
}
```
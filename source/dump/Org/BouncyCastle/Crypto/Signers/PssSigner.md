# PssSigner

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `SecureRandom random`

- `Int32 hLen`

- `Int32 mgfhLen`

- `Int32 sLen`

- `Boolean sSet`

- `Int32 emBits`

- `Byte trailer`


## Methods

- `Void ClearBlock(Byte[])`

- `Void ItoOSP(Int32, Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class PssSigner : ISigner
{
	public const Byte TrailerImplicit; // 0x0
	private readonly IDigest contentDigest1; // 0x10
	private readonly IDigest contentDigest2; // 0x18
	private readonly IDigest mgfDigest; // 0x20
	private readonly IAsymmetricBlockCipher cipher; // 0x28
	private SecureRandom random; // 0x30
	private Int32 hLen; // 0x38
	private Int32 mgfhLen; // 0x3c
	private Int32 sLen; // 0x40
	private Boolean sSet; // 0x44
	private Int32 emBits; // 0x48
	private Byte[] salt; // 0x50
	private Byte[] mDash; // 0x58
	private Byte[] block; // 0x60
	private Byte trailer; // 0x68

	public virtual String AlgorithmName { get; }

	// RVA: 0x650fe94 VA: 0x7598b27e94
	public static PssSigner CreateRawSigner(IAsymmetricBlockCipher cipher, IDigest digest) { }
	// RVA: 0x65101cc VA: 0x7598b281cc
	public static PssSigner CreateRawSigner(IAsymmetricBlockCipher cipher, IDigest contentDigest, IDigest mgfDigest, Int32 saltLen, Byte trailer) { }
	// RVA: 0x6510298 VA: 0x7598b28298
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest digest) { }
	// RVA: 0x6510378 VA: 0x7598b28378
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest digest, Int32 saltLen) { }
	// RVA: 0x65103d0 VA: 0x7598b283d0
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest digest, Byte[] salt) { }
	// RVA: 0x6510404 VA: 0x7598b28404
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest contentDigest, IDigest mgfDigest, Int32 saltLen) { }
	// RVA: 0x651045c VA: 0x7598b2845c
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest contentDigest, IDigest mgfDigest, Byte[] salt) { }
	// RVA: 0x65103a4 VA: 0x7598b283a4
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest digest, Int32 saltLen, Byte trailer) { }
	// RVA: 0x6510430 VA: 0x7598b28430
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest contentDigest, IDigest mgfDigest, Int32 saltLen, Byte trailer) { }
	// RVA: 0x650ffc8 VA: 0x7598b27fc8
	private Void .ctor(IAsymmetricBlockCipher cipher, IDigest contentDigest1, IDigest contentDigest2, IDigest mgfDigest, Int32 saltLen, Byte[] salt, Byte trailer) { }
	// RVA: 0x6510490 VA: 0x7598b28490
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6510550 VA: 0x7598b28550
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x65107f4 VA: 0x7598b287f4
	private Void ClearBlock(Byte[] block) { }
	// RVA: 0x6510818 VA: 0x7598b28818
	public virtual Void Update(Byte input) { }
	// RVA: 0x65108c4 VA: 0x7598b288c4
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x6510988 VA: 0x7598b28988
	public virtual Void Reset() { }
	// RVA: 0x6510a2c VA: 0x7598b28a2c
	public virtual Byte[] GenerateSignature() { }
	// RVA: 0x65112d8 VA: 0x7598b292d8
	public virtual Boolean VerifySignature(Byte[] signature) { }
	// RVA: 0x6511774 VA: 0x7598b29774
	private Void ItoOSP(Int32 i, Byte[] sp) { }
	// RVA: 0x6510e68 VA: 0x7598b28e68
	private Byte[] MaskGeneratorFunction1(Byte[] Z, Int32 zOff, Int32 zLen, Int32 length) { }
}
```
# RC2WrapEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `CbcBlockCipher engine`

- `ICipherParameters parameters`

- `ParametersWithIV paramPlusIV`

- `Boolean forWrapping`

- `SecureRandom sr`

- `IDigest sha1`


## Methods

- `Boolean CheckCmsKeyChecksum(Byte[], Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class RC2WrapEngine : IWrapper
{
	private CbcBlockCipher engine; // 0x10
	private ICipherParameters parameters; // 0x18
	private ParametersWithIV paramPlusIV; // 0x20
	private Byte[] iv; // 0x28
	private Boolean forWrapping; // 0x30
	private SecureRandom sr; // 0x38
	private static readonly Byte[] IV2; // 0x0
	private IDigest sha1; // 0x40
	private Byte[] digest; // 0x48

	public virtual String AlgorithmName { get; }

	// RVA: 0x654f52c VA: 0x7598b6752c
	public virtual Void Init(Boolean forWrapping, ICipherParameters parameters) { }
	// RVA: 0x654f874 VA: 0x7598b67874
	public virtual String get_AlgorithmName() { }
	// RVA: 0x654f8b4 VA: 0x7598b678b4
	public virtual Byte[] Wrap(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x654fea8 VA: 0x7598b67ea8
	public virtual Byte[] Unwrap(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x654fd28 VA: 0x7598b67d28
	private Byte[] CalculateCmsKeyChecksum(Byte[] key) { }
	// RVA: 0x6550480 VA: 0x7598b68480
	private Boolean CheckCmsKeyChecksum(Byte[] key, Byte[] checksum) { }
	// RVA: 0x655049c VA: 0x7598b6849c
	public Void .ctor() { }
	// RVA: 0x6550540 VA: 0x7598b68540
	private static Void .cctor() { }
}
```
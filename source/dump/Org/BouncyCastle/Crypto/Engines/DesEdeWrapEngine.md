# DesEdeWrapEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `CbcBlockCipher engine`

- `KeyParameter param`

- `ParametersWithIV paramPlusIV`

- `Boolean forWrapping`


## Methods

- `Boolean CheckCmsKeyChecksum(Byte[], Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class DesEdeWrapEngine : IWrapper
{
	private CbcBlockCipher engine; // 0x10
	private KeyParameter param; // 0x18
	private ParametersWithIV paramPlusIV; // 0x20
	private Byte[] iv; // 0x28
	private Boolean forWrapping; // 0x30
	private static readonly Byte[] IV2; // 0x0
	private readonly IDigest sha1; // 0x38
	private readonly Byte[] digest; // 0x40

	public virtual String AlgorithmName { get; }

	// RVA: 0x6547314 VA: 0x7598b5f314
	public virtual Void Init(Boolean forWrapping, ICipherParameters parameters) { }
	// RVA: 0x6547720 VA: 0x7598b5f720
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6547760 VA: 0x7598b5f760
	public virtual Byte[] Wrap(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x6547cc0 VA: 0x7598b5fcc0
	public virtual Byte[] Unwrap(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x6547a98 VA: 0x7598b5fa98
	private Byte[] CalculateCmsKeyChecksum(Byte[] key) { }
	// RVA: 0x6548110 VA: 0x7598b60110
	private Boolean CheckCmsKeyChecksum(Byte[] key, Byte[] checksum) { }
	// RVA: 0x6547c18 VA: 0x7598b5fc18
	private static Byte[] reverse(Byte[] bs) { }
	// RVA: 0x654812c VA: 0x7598b6012c
	public Void .ctor() { }
	// RVA: 0x65481d0 VA: 0x7598b601d0
	private static Void .cctor() { }
}
```
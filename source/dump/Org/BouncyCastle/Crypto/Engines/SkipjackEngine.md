# SkipjackEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean encrypting`


## Methods

- `Int32 G(Int32, Int32)`

- `Int32 H(Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class SkipjackEngine : IBlockCipher
{
	private const Int32 BLOCK_SIZE; // 0x0
	private static readonly Int16[] ftable; // 0x0
	private Int32[] key0; // 0x10
	private Int32[] key1; // 0x18
	private Int32[] key2; // 0x20
	private Int32[] key3; // 0x28
	private Boolean encrypting; // 0x30

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x655d7f0 VA: 0x7598b757f0
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x655db34 VA: 0x7598b75b34
	public virtual String get_AlgorithmName() { }
	// RVA: 0x655db74 VA: 0x7598b75b74
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x655db7c VA: 0x7598b75b7c
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x655db84 VA: 0x7598b75b84
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x655dcb8 VA: 0x7598b75cb8
	public virtual Void Reset() { }
	// RVA: 0x655dcbc VA: 0x7598b75cbc
	private Int32 G(Int32 k, Int32 w) { }
	// RVA: 0x655de18 VA: 0x7598b75e18
	public virtual Int32 EncryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x655e064 VA: 0x7598b76064
	private Int32 H(Int32 k, Int32 w) { }
	// RVA: 0x655e1c0 VA: 0x7598b761c0
	public virtual Int32 DecryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x655e420 VA: 0x7598b76420
	public Void .ctor() { }
	// RVA: 0x655e428 VA: 0x7598b76428
	private static Void .cctor() { }
}
```
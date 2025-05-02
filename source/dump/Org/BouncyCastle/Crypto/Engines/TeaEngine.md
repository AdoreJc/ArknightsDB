# TeaEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `UInt32 _a`

- `UInt32 _b`

- `UInt32 _c`

- `UInt32 _d`

- `Boolean _initialised`

- `Boolean _forEncryption`


## Methods

- `Void setKey(Byte[])`

- `Int32 encryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 decryptBlock(Byte[], Int32, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class TeaEngine : IBlockCipher
{
	private const Int32 rounds; // 0x0
	private const Int32 block_size; // 0x0
	private const UInt32 delta; // 0x0
	private const UInt32 d_sum; // 0x0
	private UInt32 _a; // 0x10
	private UInt32 _b; // 0x14
	private UInt32 _c; // 0x18
	private UInt32 _d; // 0x1c
	private Boolean _initialised; // 0x20
	private Boolean _forEncryption; // 0x21

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x655e4c8 VA: 0x7598b764c8
	public Void .ctor() { }
	// RVA: 0x655e4e4 VA: 0x7598b764e4
	public virtual String get_AlgorithmName() { }
	// RVA: 0x655e524 VA: 0x7598b76524
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x655e52c VA: 0x7598b7652c
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x655e534 VA: 0x7598b76534
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x655e6e8 VA: 0x7598b766e8
	public virtual Int32 ProcessBlock(Byte[] inBytes, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x655ea10 VA: 0x7598b76a10
	public virtual Void Reset() { }
	// RVA: 0x655e67c VA: 0x7598b7667c
	private Void setKey(Byte[] key) { }
	// RVA: 0x655e92c VA: 0x7598b7692c
	private Int32 encryptBlock(Byte[] inBytes, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x655e848 VA: 0x7598b76848
	private Int32 decryptBlock(Byte[] inBytes, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
}
```
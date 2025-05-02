# XteaEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

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
public class XteaEngine : IBlockCipher
{
	private const Int32 rounds; // 0x0
	private const Int32 block_size; // 0x0
	private const Int32 delta; // 0x0
	private UInt32[] _S; // 0x10
	private UInt32[] _sum0; // 0x18
	private UInt32[] _sum1; // 0x20
	private Boolean _initialised; // 0x28
	private Boolean _forEncryption; // 0x29

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x656e104 VA: 0x7598b86104
	public Void .ctor() { }
	// RVA: 0x656e1a8 VA: 0x7598b861a8
	public virtual String get_AlgorithmName() { }
	// RVA: 0x656e1e8 VA: 0x7598b861e8
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x656e1f0 VA: 0x7598b861f0
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x656e1f8 VA: 0x7598b861f8
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x656e448 VA: 0x7598b86448
	public virtual Int32 ProcessBlock(Byte[] inBytes, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x656e7ac VA: 0x7598b867ac
	public virtual Void Reset() { }
	// RVA: 0x656e340 VA: 0x7598b86340
	private Void setKey(Byte[] key) { }
	// RVA: 0x656e6a8 VA: 0x7598b866a8
	private Int32 encryptBlock(Byte[] inBytes, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x656e5a8 VA: 0x7598b865a8
	private Int32 decryptBlock(Byte[] inBytes, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
}
```
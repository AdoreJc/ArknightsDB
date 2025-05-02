# NoekeonEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean _initialised`

- `Boolean _forEncryption`


## Methods

- `Void setKey(Byte[])`

- `Int32 encryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 decryptBlock(Byte[], Int32, Byte[], Int32)`

- `Void gamma(UInt32[])`

- `Void theta(UInt32[], UInt32[])`

- `Void pi1(UInt32[])`

- `Void pi2(UInt32[])`

- `UInt32 rotl(UInt32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class NoekeonEngine : IBlockCipher
{
	private const Int32 GenericSize; // 0x0
	private static readonly UInt32[] nullVector; // 0x0
	private static readonly UInt32[] roundConstants; // 0x8
	private UInt32[] state; // 0x10
	private UInt32[] subKeys; // 0x18
	private UInt32[] decryptKeys; // 0x20
	private Boolean _initialised; // 0x28
	private Boolean _forEncryption; // 0x29

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x654d950 VA: 0x7598b65950
	public Void .ctor() { }
	// RVA: 0x654d9f4 VA: 0x7598b659f4
	public virtual String get_AlgorithmName() { }
	// RVA: 0x654da34 VA: 0x7598b65a34
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x654da3c VA: 0x7598b65a3c
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x654da44 VA: 0x7598b65a44
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x654dc5c VA: 0x7598b65c5c
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x654e29c VA: 0x7598b6629c
	public virtual Void Reset() { }
	// RVA: 0x654db9c VA: 0x7598b65b9c
	private Void setKey(Byte[] key) { }
	// RVA: 0x654e064 VA: 0x7598b66064
	private Int32 encryptBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x654ddbc VA: 0x7598b65dbc
	private Int32 decryptBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x654e3b8 VA: 0x7598b663b8
	private Void gamma(UInt32[] a) { }
	// RVA: 0x654e2a0 VA: 0x7598b662a0
	private Void theta(UInt32[] a, UInt32[] k) { }
	// RVA: 0x654e360 VA: 0x7598b66360
	private Void pi1(UInt32[] a) { }
	// RVA: 0x654e424 VA: 0x7598b66424
	private Void pi2(UInt32[] a) { }
	// RVA: 0x654e47c VA: 0x7598b6647c
	private UInt32 rotl(UInt32 x, Int32 y) { }
	// RVA: 0x654e488 VA: 0x7598b66488
	private static Void .cctor() { }
}
```
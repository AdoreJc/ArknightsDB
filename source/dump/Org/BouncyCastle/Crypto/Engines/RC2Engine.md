# RC2Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean encrypting`


## Methods

- `Int32 RotateWordLeft(Int32, Int32)`

- `Void EncryptBlock(Byte[], Int32, Byte[], Int32)`

- `Void DecryptBlock(Byte[], Int32, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class RC2Engine : IBlockCipher
{
	private static readonly Byte[] piTable; // 0x0
	private const Int32 BLOCK_SIZE; // 0x0
	private Int32[] workingKey; // 0x10
	private Boolean encrypting; // 0x18

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x654e548 VA: 0x7598b66548
	private Int32[] GenerateWorkingKey(Byte[] key, Int32 bits) { }
	// RVA: 0x654e828 VA: 0x7598b66828
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x654e9a4 VA: 0x7598b669a4
	public virtual Void Reset() { }
	// RVA: 0x654e9a8 VA: 0x7598b669a8
	public virtual String get_AlgorithmName() { }
	// RVA: 0x654e9e8 VA: 0x7598b669e8
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x654e9f0 VA: 0x7598b669f0
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x654e9f8 VA: 0x7598b669f8
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x654f468 VA: 0x7598b67468
	private Int32 RotateWordLeft(Int32 x, Int32 y) { }
	// RVA: 0x654eb30 VA: 0x7598b66b30
	private Void EncryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x654f010 VA: 0x7598b67010
	private Void DecryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x654f484 VA: 0x7598b67484
	public Void .ctor() { }
	// RVA: 0x654f48c VA: 0x7598b6748c
	private static Void .cctor() { }
}
```
# RC532Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Int32 _noRounds`

- `Boolean forEncryption`


## Methods

- `Void SetKey(Byte[])`

- `Int32 EncryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 DecryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 RotateLeft(Int32, Int32)`

- `Int32 RotateRight(Int32, Int32)`

- `Int32 BytesToWord(Byte[], Int32)`

- `Void WordToBytes(Int32, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class RC532Engine : IBlockCipher
{
	private Int32 _noRounds; // 0x10
	private Int32[] _S; // 0x18
	private static readonly Int32 P32; // 0x0
	private static readonly Int32 Q32; // 0x4
	private Boolean forEncryption; // 0x20

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x6550c00 VA: 0x7598b68c00
	public Void .ctor() { }
	// RVA: 0x6550c20 VA: 0x7598b68c20
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6550c60 VA: 0x7598b68c60
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x6550c68 VA: 0x7598b68c68
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x6550c70 VA: 0x7598b68c70
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6551104 VA: 0x7598b69104
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x6551344 VA: 0x7598b69344
	public virtual Void Reset() { }
	// RVA: 0x6550ea4 VA: 0x7598b68ea4
	private Void SetKey(Byte[] key) { }
	// RVA: 0x6551234 VA: 0x7598b69234
	private Int32 EncryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6551128 VA: 0x7598b69128
	private Int32 DecryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6551348 VA: 0x7598b69348
	private Int32 RotateLeft(Int32 x, Int32 y) { }
	// RVA: 0x6551444 VA: 0x7598b69444
	private Int32 RotateRight(Int32 x, Int32 y) { }
	// RVA: 0x6551354 VA: 0x7598b69354
	private Int32 BytesToWord(Byte[] src, Int32 srcOff) { }
	// RVA: 0x65513c4 VA: 0x7598b693c4
	private Void WordToBytes(Int32 word, Byte[] dst, Int32 dstOff) { }
	// RVA: 0x655144c VA: 0x7598b6944c
	private static Void .cctor() { }
}
```
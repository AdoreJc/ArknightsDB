# AesEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Int32 ROUNDS`

- `UInt32 C0`

- `UInt32 C1`

- `UInt32 C2`

- `UInt32 C3`

- `Boolean forEncryption`


## Methods

- `Void UnPackBlock(Byte[], Int32)`

- `Void PackBlock(Byte[], Int32)`

- `Void EncryptBlock(UInt32[][])`

- `Void DecryptBlock(UInt32[][])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class AesEngine : IBlockCipher
{
	private static readonly Byte[] S; // 0x0
	private static readonly Byte[] Si; // 0x8
	private static readonly Byte[] rcon; // 0x10
	private static readonly UInt32[] T0; // 0x18
	private static readonly UInt32[] Tinv0; // 0x20
	private const UInt32 m1; // 0x0
	private const UInt32 m2; // 0x0
	private const UInt32 m3; // 0x0
	private const UInt32 m4; // 0x0
	private const UInt32 m5; // 0x0
	private Int32 ROUNDS; // 0x10
	private UInt32[][] WorkingKey; // 0x18
	private UInt32 C0; // 0x20
	private UInt32 C1; // 0x24
	private UInt32 C2; // 0x28
	private UInt32 C3; // 0x2c
	private Boolean forEncryption; // 0x30
	private const Int32 BLOCK_SIZE; // 0x0

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x65389a8 VA: 0x7598b509a8
	private static UInt32 Shift(UInt32 r, Int32 shift) { }
	// RVA: 0x65389b0 VA: 0x7598b509b0
	private static UInt32 FFmulX(UInt32 x) { }
	// RVA: 0x65389d0 VA: 0x7598b509d0
	private static UInt32 FFmulX2(UInt32 x) { }
	// RVA: 0x65389ec VA: 0x7598b509ec
	private static UInt32 Inv_Mcol(UInt32 x) { }
	// RVA: 0x6538a84 VA: 0x7598b50a84
	private static UInt32 SubWord(UInt32 x) { }
	// RVA: 0x6538b48 VA: 0x7598b50b48
	private UInt32[][] GenerateWorkingKey(Byte[] key, Boolean forEncryption) { }
	// RVA: 0x6539668 VA: 0x7598b51668
	public Void .ctor() { }
	// RVA: 0x6539670 VA: 0x7598b51670
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x65397a0 VA: 0x7598b517a0
	public virtual String get_AlgorithmName() { }
	// RVA: 0x65397e0 VA: 0x7598b517e0
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x65397e8 VA: 0x7598b517e8
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x65397f0 VA: 0x7598b517f0
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x653a95c VA: 0x7598b5295c
	public virtual Void Reset() { }
	// RVA: 0x6539928 VA: 0x7598b51928
	private Void UnPackBlock(Byte[] bytes, Int32 off) { }
	// RVA: 0x653a8f8 VA: 0x7598b528f8
	private Void PackBlock(Byte[] bytes, Int32 off) { }
	// RVA: 0x6539998 VA: 0x7598b51998
	private Void EncryptBlock(UInt32[][] KW) { }
	// RVA: 0x653a034 VA: 0x7598b52034
	private Void DecryptBlock(UInt32[][] KW) { }
	// RVA: 0x653a960 VA: 0x7598b52960
	private static Void .cctor() { }
}
```
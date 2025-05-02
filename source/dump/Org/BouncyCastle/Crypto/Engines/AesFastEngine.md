# AesFastEngine

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
public class AesFastEngine : IBlockCipher
{
	private static readonly Byte[] S; // 0x0
	private static readonly Byte[] Si; // 0x8
	private static readonly Byte[] rcon; // 0x10
	private static readonly UInt32[] T0; // 0x18
	private static readonly UInt32[] T1; // 0x20
	private static readonly UInt32[] T2; // 0x28
	private static readonly UInt32[] T3; // 0x30
	private static readonly UInt32[] Tinv0; // 0x38
	private static readonly UInt32[] Tinv1; // 0x40
	private static readonly UInt32[] Tinv2; // 0x48
	private static readonly UInt32[] Tinv3; // 0x50
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

	// RVA: 0x653ab34 VA: 0x7598b52b34
	private static UInt32 Shift(UInt32 r, Int32 shift) { }
	// RVA: 0x653ab3c VA: 0x7598b52b3c
	private static UInt32 FFmulX(UInt32 x) { }
	// RVA: 0x653ab5c VA: 0x7598b52b5c
	private static UInt32 FFmulX2(UInt32 x) { }
	// RVA: 0x653ab78 VA: 0x7598b52b78
	private static UInt32 Inv_Mcol(UInt32 x) { }
	// RVA: 0x653ac10 VA: 0x7598b52c10
	private static UInt32 SubWord(UInt32 x) { }
	// RVA: 0x653acd4 VA: 0x7598b52cd4
	private UInt32[][] GenerateWorkingKey(Byte[] key, Boolean forEncryption) { }
	// RVA: 0x653b7f4 VA: 0x7598b537f4
	public Void .ctor() { }
	// RVA: 0x653b7fc VA: 0x7598b537fc
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x653b92c VA: 0x7598b5392c
	public virtual String get_AlgorithmName() { }
	// RVA: 0x653b96c VA: 0x7598b5396c
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x653b974 VA: 0x7598b53974
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x653b97c VA: 0x7598b5397c
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x653cb18 VA: 0x7598b54b18
	public virtual Void Reset() { }
	// RVA: 0x653bab4 VA: 0x7598b53ab4
	private Void UnPackBlock(Byte[] bytes, Int32 off) { }
	// RVA: 0x653cab4 VA: 0x7598b54ab4
	private Void PackBlock(Byte[] bytes, Int32 off) { }
	// RVA: 0x653bb24 VA: 0x7598b53b24
	private Void EncryptBlock(UInt32[][] KW) { }
	// RVA: 0x653c1f4 VA: 0x7598b541f4
	private Void DecryptBlock(UInt32[][] KW) { }
	// RVA: 0x653cb1c VA: 0x7598b54b1c
	private static Void .cctor() { }
}
```
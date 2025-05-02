# RijndaelEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Int32 BC`

- `Int64 BC_MASK`

- `Int32 ROUNDS`

- `Int32 blockBits`

- `Int64 A0`

- `Int64 A1`

- `Int64 A2`

- `Int64 A3`

- `Boolean forEncryption`


## Methods

- `Byte Mul0x2(Int32)`

- `Byte Mul0x3(Int32)`

- `Byte Mul0x9(Int32)`

- `Byte Mul0xb(Int32)`

- `Byte Mul0xd(Int32)`

- `Byte Mul0xe(Int32)`

- `Void KeyAddition(Int64[])`

- `Int64 Shift(Int64, Int32)`

- `Void ShiftRow(Byte[])`

- `Int64 ApplyS(Int64, Byte[])`

- `Void Substitution(Byte[])`

- `Void MixColumn()`

- `Void InvMixColumn()`

- `Void UnPackBlock(Byte[], Int32)`

- `Void PackBlock(Byte[], Int32)`

- `Void EncryptBlock(Int64[][])`

- `Void DecryptBlock(Int64[][])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class RijndaelEngine : IBlockCipher
{
	private static readonly Int32 MAXROUNDS; // 0x0
	private static readonly Int32 MAXKC; // 0x4
	private static readonly Byte[] Logtable; // 0x8
	private static readonly Byte[] Alogtable; // 0x10
	private static readonly Byte[] S; // 0x18
	private static readonly Byte[] Si; // 0x20
	private static readonly Byte[] rcon; // 0x28
	private static readonly Byte[][] shifts0; // 0x30
	private static readonly Byte[][] shifts1; // 0x38
	private Int32 BC; // 0x10
	private Int64 BC_MASK; // 0x18
	private Int32 ROUNDS; // 0x20
	private Int32 blockBits; // 0x24
	private Int64[][] workingKey; // 0x28
	private Int64 A0; // 0x30
	private Int64 A1; // 0x38
	private Int64 A2; // 0x40
	private Int64 A3; // 0x48
	private Boolean forEncryption; // 0x50
	private Byte[] shifts0SC; // 0x58
	private Byte[] shifts1SC; // 0x60

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x6554284 VA: 0x7598b6c284
	private Byte Mul0x2(Int32 b) { }
	// RVA: 0x655432c VA: 0x7598b6c32c
	private Byte Mul0x3(Int32 b) { }
	// RVA: 0x65543d4 VA: 0x7598b6c3d4
	private Byte Mul0x9(Int32 b) { }
	// RVA: 0x6554460 VA: 0x7598b6c460
	private Byte Mul0xb(Int32 b) { }
	// RVA: 0x65544ec VA: 0x7598b6c4ec
	private Byte Mul0xd(Int32 b) { }
	// RVA: 0x6554578 VA: 0x7598b6c578
	private Byte Mul0xe(Int32 b) { }
	// RVA: 0x6554604 VA: 0x7598b6c604
	private Void KeyAddition(Int64[] rk) { }
	// RVA: 0x655467c VA: 0x7598b6c67c
	private Int64 Shift(Int64 r, Int32 shift) { }
	// RVA: 0x65546a8 VA: 0x7598b6c6a8
	private Void ShiftRow(Byte[] shiftsSC) { }
	// RVA: 0x6554768 VA: 0x7598b6c768
	private Int64 ApplyS(Int64 r, Byte[] box) { }
	// RVA: 0x65547d0 VA: 0x7598b6c7d0
	private Void Substitution(Byte[] box) { }
	// RVA: 0x655483c VA: 0x7598b6c83c
	private Void MixColumn() { }
	// RVA: 0x65549c0 VA: 0x7598b6c9c0
	private Void InvMixColumn() { }
	// RVA: 0x6554cd8 VA: 0x7598b6ccd8
	private Int64[][] GenerateWorkingKey(Byte[] key) { }
	// RVA: 0x6555450 VA: 0x7598b6d450
	public Void .ctor() { }
	// RVA: 0x6555458 VA: 0x7598b6d458
	public Void .ctor(Int32 blockBits) { }
	// RVA: 0x6555760 VA: 0x7598b6d760
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6555904 VA: 0x7598b6d904
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6555944 VA: 0x7598b6d944
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x655594c VA: 0x7598b6d94c
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x6555960 VA: 0x7598b6d960
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x6555ec0 VA: 0x7598b6dec0
	public virtual Void Reset() { }
	// RVA: 0x6555abc VA: 0x7598b6dabc
	private Void UnPackBlock(Byte[] bytes, Int32 off) { }
	// RVA: 0x6555e00 VA: 0x7598b6de00
	private Void PackBlock(Byte[] bytes, Int32 off) { }
	// RVA: 0x6555bd8 VA: 0x7598b6dbd8
	private Void EncryptBlock(Int64[][] rk) { }
	// RVA: 0x6555cd4 VA: 0x7598b6dcd4
	private Void DecryptBlock(Int64[][] rk) { }
	// RVA: 0x6555ec4 VA: 0x7598b6dec4
	private static Void .cctor() { }
}
```
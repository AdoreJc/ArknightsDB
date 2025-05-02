# SeedEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean forEncryption`


## Methods

- `Int32 extractW1(Int64)`

- `Int32 extractW0(Int64)`

- `Int64 rotateLeft8(Int64)`

- `Int64 rotateRight8(Int64)`

- `Int64 bytesToLong(Byte[], Int32)`

- `Void longToBytes(Byte[], Int32, Int64)`

- `Int32 G(Int32)`

- `Int64 F(Int32, Int32, Int64)`

- `Int32 phaseCalc1(Int32, Int32, Int32, Int32)`

- `Int32 phaseCalc2(Int32, Int32, Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class SeedEngine : IBlockCipher
{
	private const Int32 BlockSize; // 0x0
	private static readonly UInt32[] SS0; // 0x0
	private static readonly UInt32[] SS1; // 0x8
	private static readonly UInt32[] SS2; // 0x10
	private static readonly UInt32[] SS3; // 0x18
	private static readonly UInt32[] KC; // 0x20
	private Int32[] wKey; // 0x10
	private Boolean forEncryption; // 0x18

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x6558264 VA: 0x7598b70264
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x65584c0 VA: 0x7598b704c0
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6558500 VA: 0x7598b70500
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x6558508 VA: 0x7598b70508
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x6558510 VA: 0x7598b70510
	public virtual Int32 ProcessBlock(Byte[] inBuf, Int32 inOff, Byte[] outBuf, Int32 outOff) { }
	// RVA: 0x6558820 VA: 0x7598b70820
	public virtual Void Reset() { }
	// RVA: 0x6558318 VA: 0x7598b70318
	private Int32[] createWorkingKey(Byte[] inKey) { }
	// RVA: 0x655882c VA: 0x7598b7082c
	private Int32 extractW1(Int64 lVal) { }
	// RVA: 0x6558824 VA: 0x7598b70824
	private Int32 extractW0(Int64 lVal) { }
	// RVA: 0x6558928 VA: 0x7598b70928
	private Int64 rotateLeft8(Int64 x) { }
	// RVA: 0x6558920 VA: 0x7598b70920
	private Int64 rotateRight8(Int64 x) { }
	// RVA: 0x6558708 VA: 0x7598b70708
	private Int64 bytesToLong(Byte[] src, Int32 srcOff) { }
	// RVA: 0x65587c8 VA: 0x7598b707c8
	private Void longToBytes(Byte[] dest, Int32 destOff, Int64 value) { }
	// RVA: 0x6558834 VA: 0x7598b70834
	private Int32 G(Int32 x) { }
	// RVA: 0x6558764 VA: 0x7598b70764
	private Int64 F(Int32 ki0, Int32 ki1, Int64 r) { }
	// RVA: 0x6558970 VA: 0x7598b70970
	private Int32 phaseCalc1(Int32 r0, Int32 ki0, Int32 r1, Int32 ki1) { }
	// RVA: 0x6558930 VA: 0x7598b70930
	private Int32 phaseCalc2(Int32 r0, Int32 ki0, Int32 r1, Int32 ki1) { }
	// RVA: 0x6558990 VA: 0x7598b70990
	public Void .ctor() { }
	// RVA: 0x6558998 VA: 0x7598b70998
	private static Void .cctor() { }
}
```
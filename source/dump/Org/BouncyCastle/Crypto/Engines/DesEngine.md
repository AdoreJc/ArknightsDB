# DesEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class DesEngine : IBlockCipher
{
	internal const Int32 BLOCK_SIZE; // 0x0
	private Int32[] workingKey; // 0x10
	private static readonly Int16[] bytebit; // 0x0
	private static readonly Int32[] bigbyte; // 0x8
	private static readonly Byte[] pc1; // 0x10
	private static readonly Byte[] totrot; // 0x18
	private static readonly Byte[] pc2; // 0x20
	private static readonly UInt32[] SP1; // 0x28
	private static readonly UInt32[] SP2; // 0x30
	private static readonly UInt32[] SP3; // 0x38
	private static readonly UInt32[] SP4; // 0x40
	private static readonly UInt32[] SP5; // 0x48
	private static readonly UInt32[] SP6; // 0x50
	private static readonly UInt32[] SP7; // 0x58
	private static readonly UInt32[] SP8; // 0x60

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x6548270 VA: 0x7598b60270
	public virtual Int32[] GetWorkingKey() { }
	// RVA: 0x6548278 VA: 0x7598b60278
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x65483c4 VA: 0x7598b603c4
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6548404 VA: 0x7598b60404
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x654840c VA: 0x7598b6040c
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x6548414 VA: 0x7598b60414
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x6548550 VA: 0x7598b60550
	public virtual Void Reset() { }
	// RVA: 0x65466f4 VA: 0x7598b5e6f4
	protected static Int32[] GenerateWorkingKey(Boolean encrypting, Byte[] key) { }
	// RVA: 0x6546e7c VA: 0x7598b5ee7c
	internal static Void DesFunc(Int32[] wKey, Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x654730c VA: 0x7598b5f30c
	public Void .ctor() { }
	// RVA: 0x6548554 VA: 0x7598b60554
	private static Void .cctor() { }
}
```
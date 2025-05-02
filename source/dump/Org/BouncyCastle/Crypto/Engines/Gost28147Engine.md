# Gost28147Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean forEncryption`


## Methods

- `Int32 Gost28147_mainStep(Int32, Int32)`

- `Void Gost28147Func(Int32[], Byte[], Int32, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class Gost28147Engine : IBlockCipher
{
	private const Int32 BlockSize; // 0x0
	private Int32[] workingKey; // 0x10
	private Boolean forEncryption; // 0x18
	private Byte[] S; // 0x20
	private static readonly Byte[] Sbox_Default; // 0x0
	private static readonly Byte[] ESbox_Test; // 0x8
	private static readonly Byte[] ESbox_A; // 0x10
	private static readonly Byte[] ESbox_B; // 0x18
	private static readonly Byte[] ESbox_C; // 0x20
	private static readonly Byte[] ESbox_D; // 0x28
	private static readonly Byte[] DSbox_Test; // 0x30
	private static readonly Byte[] DSbox_A; // 0x38
	private static readonly IDictionary sBoxes; // 0x40

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x6549254 VA: 0x7598b61254
	private static Void .cctor() { }
	// RVA: 0x6549658 VA: 0x7598b61658
	private static Void AddSBox(String sBoxName, Byte[] sBox) { }
	// RVA: 0x6549774 VA: 0x7598b61774
	public Void .ctor() { }
	// RVA: 0x65497e4 VA: 0x7598b617e4
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6549b80 VA: 0x7598b61b80
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6549bc0 VA: 0x7598b61bc0
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x6549bc8 VA: 0x7598b61bc8
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x6549bd0 VA: 0x7598b61bd0
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x6549f2c VA: 0x7598b61f2c
	public virtual Void Reset() { }
	// RVA: 0x6549a4c VA: 0x7598b61a4c
	private Int32[] generateWorkingKey(Boolean forEncryption, Byte[] userKey) { }
	// RVA: 0x6549fa4 VA: 0x7598b61fa4
	private Int32 Gost28147_mainStep(Int32 n1, Int32 key) { }
	// RVA: 0x6549ce8 VA: 0x7598b61ce8
	private Void Gost28147Func(Int32[] workingKey, Byte[] inBytes, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6549f30 VA: 0x7598b61f30
	private static Int32 bytesToint(Byte[] inBytes, Int32 inOff) { }
	// RVA: 0x654a0a0 VA: 0x7598b620a0
	private static Void intTobytes(Int32 num, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x654a120 VA: 0x7598b62120
	public static Byte[] GetSBox(String sBoxName) { }
}
```
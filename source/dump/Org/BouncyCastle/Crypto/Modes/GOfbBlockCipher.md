# GOfbBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Fields

- `Boolean firstStep`

- `Int32 N3`

- `Int32 N4`


## Properties

- `String AlgorithmName`

- `Boolean IsPartialBlockOkay`


## Methods

- `IBlockCipher GetUnderlyingCipher()`

- `Void Init(Boolean, ICipherParameters)`

- `String get_AlgorithmName()`

- `Boolean get_IsPartialBlockOkay()`

- `Int32 GetBlockSize()`

- `Int32 ProcessBlock(Byte[], Int32, Byte[], Int32)`

- `Void Reset()`

- `Int32 bytesToint(Byte[], Int32)`

- `Void intTobytes(Int32, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class GOfbBlockCipher : IBlockCipher
{
	private Byte[] IV; // 0x10
	private Byte[] ofbV; // 0x18
	private Byte[] ofbOutV; // 0x20
	private readonly Int32 blockSize; // 0x28
	private readonly IBlockCipher cipher; // 0x30
	private Boolean firstStep; // 0x38
	private Int32 N3; // 0x3c
	private Int32 N4; // 0x40
	private const Int32 C1; // 0x0
	private const Int32 C2; // 0x0

	public String AlgorithmName { get; }
	public Boolean IsPartialBlockOkay { get; }

	// RVA: 0x65273dc VA: 0x7598b3f3dc
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x652768c VA: 0x7598b3f68c
	public IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x6527694 VA: 0x7598b3f694
	public Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x652791c VA: 0x7598b3f91c
	public String get_AlgorithmName() { }
	// RVA: 0x65279dc VA: 0x7598b3f9dc
	public Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x65279e4 VA: 0x7598b3f9e4
	public Int32 GetBlockSize() { }
	// RVA: 0x65279ec VA: 0x7598b3f9ec
	public Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x6527858 VA: 0x7598b3f858
	public Void Reset() { }
	// RVA: 0x6527d24 VA: 0x7598b3fd24
	private Int32 bytesToint(Byte[] inBytes, Int32 inOff) { }
	// RVA: 0x6527d98 VA: 0x7598b3fd98
	private Void intTobytes(Int32 num, Byte[] outBytes, Int32 outOff) { }
}
```
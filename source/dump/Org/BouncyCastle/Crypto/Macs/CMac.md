# CMac

**Namespace:** `Org.BouncyCastle.Crypto.Macs`


## Fields

- `Int32 bufOff`

- `IBlockCipher cipher`

- `Int32 macSize`


## Properties

- `String AlgorithmName`


## Methods

- `String get_AlgorithmName()`

- `Void Init(ICipherParameters)`

- `Int32 GetMacSize()`

- `Void Update(Byte)`

- `Void BlockUpdate(Byte[], Int32, Int32)`

- `Int32 DoFinal(Byte[], Int32)`

- `Void Reset()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Macs
public class CMac : IMac
{
	private const Byte CONSTANT_128; // 0x0
	private const Byte CONSTANT_64; // 0x0
	private Byte[] ZEROES; // 0x10
	private Byte[] mac; // 0x18
	private Byte[] buf; // 0x20
	private Int32 bufOff; // 0x28
	private IBlockCipher cipher; // 0x30
	private Int32 macSize; // 0x38
	private Byte[] L; // 0x40
	private Byte[] Lu; // 0x48
	private Byte[] Lu2; // 0x50

	public String AlgorithmName { get; }

	// RVA: 0x65306c4 VA: 0x7598b486c4
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x6530778 VA: 0x7598b48778
	public Void .ctor(IBlockCipher cipher, Int32 macSizeInBits) { }
	// RVA: 0x6530c08 VA: 0x7598b48c08
	public String get_AlgorithmName() { }
	// RVA: 0x6530ca8 VA: 0x7598b48ca8
	private static Int32 ShiftLeft(Byte[] block, Byte[] output) { }
	// RVA: 0x6530d2c VA: 0x7598b48d2c
	private static Byte[] DoubleLu(Byte[] input) { }
	// RVA: 0x6530de0 VA: 0x7598b48de0
	public Void Init(ICipherParameters parameters) { }
	// RVA: 0x65310f0 VA: 0x7598b490f0
	public Int32 GetMacSize() { }
	// RVA: 0x65310f8 VA: 0x7598b490f8
	public Void Update(Byte input) { }
	// RVA: 0x6531210 VA: 0x7598b49210
	public Void BlockUpdate(Byte[] inBytes, Int32 inOff, Int32 len) { }
	// RVA: 0x65314a4 VA: 0x7598b494a4
	public Int32 DoFinal(Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6531030 VA: 0x7598b49030
	public Void Reset() { }
}
```
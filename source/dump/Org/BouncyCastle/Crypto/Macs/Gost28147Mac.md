# Gost28147Mac

**Namespace:** `Org.BouncyCastle.Crypto.Macs`


## Fields

- `Int32 bufOff`

- `Boolean firstStep`


## Properties

- `String AlgorithmName`


## Methods

- `Void Init(ICipherParameters)`

- `String get_AlgorithmName()`

- `Int32 GetMacSize()`

- `Int32 gost28147_mainStep(Int32, Int32)`

- `Void gost28147MacFunc(Int32[], Byte[], Int32, Byte[], Int32)`

- `Void Update(Byte)`

- `Void BlockUpdate(Byte[], Int32, Int32)`

- `Int32 DoFinal(Byte[], Int32)`

- `Void Reset()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Macs
public class Gost28147Mac : IMac
{
	private const Int32 blockSize; // 0x0
	private const Int32 macSize; // 0x0
	private Int32 bufOff; // 0x10
	private Byte[] buf; // 0x18
	private Byte[] mac; // 0x20
	private Boolean firstStep; // 0x28
	private Int32[] workingKey; // 0x30
	private Byte[] S; // 0x38

	public String AlgorithmName { get; }

	// RVA: 0x65316c4 VA: 0x7598b496c4
	public Void .ctor() { }
	// RVA: 0x653179c VA: 0x7598b4979c
	private static Int32[] generateWorkingKey(Byte[] userKey) { }
	// RVA: 0x653190c VA: 0x7598b4990c
	public Void Init(ICipherParameters parameters) { }
	// RVA: 0x6531b2c VA: 0x7598b49b2c
	public String get_AlgorithmName() { }
	// RVA: 0x6531b6c VA: 0x7598b49b6c
	public Int32 GetMacSize() { }
	// RVA: 0x6531b74 VA: 0x7598b49b74
	private Int32 gost28147_mainStep(Int32 n1, Int32 key) { }
	// RVA: 0x6531c70 VA: 0x7598b49c70
	private Void gost28147MacFunc(Int32[] workingKey, Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x6531898 VA: 0x7598b49898
	private static Int32 bytesToint(Byte[] input, Int32 inOff) { }
	// RVA: 0x6531d54 VA: 0x7598b49d54
	private static Void intTobytes(Int32 num, Byte[] output, Int32 outOff) { }
	// RVA: 0x6531dd4 VA: 0x7598b49dd4
	private static Byte[] CM5func(Byte[] buf, Int32 bufOff, Byte[] mac) { }
	// RVA: 0x6531eb8 VA: 0x7598b49eb8
	public Void Update(Byte input) { }
	// RVA: 0x6531fbc VA: 0x7598b49fbc
	public Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x65321b0 VA: 0x7598b4a1b0
	public Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6531af4 VA: 0x7598b49af4
	public Void Reset() { }
}
```
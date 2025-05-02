# HC128Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `UInt32 cnt`

- `Boolean initialised`

- `Int32 idx`


## Methods

- `UInt32 G1(UInt32, UInt32, UInt32)`

- `UInt32 G2(UInt32, UInt32, UInt32)`

- `UInt32 H1(UInt32)`

- `UInt32 H2(UInt32)`

- `UInt32 Step()`

- `Void Init()`

- `Byte GetByte()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class HC128Engine : IStreamCipher
{
	private UInt32[] p; // 0x10
	private UInt32[] q; // 0x18
	private UInt32 cnt; // 0x20
	private Byte[] key; // 0x28
	private Byte[] iv; // 0x30
	private Boolean initialised; // 0x38
	private Byte[] buf; // 0x40
	private Int32 idx; // 0x48

	public virtual String AlgorithmName { get; }

	// RVA: 0x654a2b4 VA: 0x7598b622b4
	private static UInt32 F1(UInt32 x) { }
	// RVA: 0x654a2cc VA: 0x7598b622cc
	private static UInt32 F2(UInt32 x) { }
	// RVA: 0x654a2dc VA: 0x7598b622dc
	private UInt32 G1(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x654a2f0 VA: 0x7598b622f0
	private UInt32 G2(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x654a304 VA: 0x7598b62304
	private static UInt32 RotateLeft(UInt32 x, Int32 bits) { }
	// RVA: 0x654a2c4 VA: 0x7598b622c4
	private static UInt32 RotateRight(UInt32 x, Int32 bits) { }
	// RVA: 0x654a310 VA: 0x7598b62310
	private UInt32 H1(UInt32 x) { }
	// RVA: 0x654a35c VA: 0x7598b6235c
	private UInt32 H2(UInt32 x) { }
	// RVA: 0x654a3a8 VA: 0x7598b623a8
	private static UInt32 Mod1024(UInt32 x) { }
	// RVA: 0x654a3b0 VA: 0x7598b623b0
	private static UInt32 Mod512(UInt32 x) { }
	// RVA: 0x654a3b8 VA: 0x7598b623b8
	private static UInt32 Dim(UInt32 x, UInt32 y) { }
	// RVA: 0x654a3c4 VA: 0x7598b623c4
	private UInt32 Step() { }
	// RVA: 0x654a56c VA: 0x7598b6256c
	private Void Init() { }
	// RVA: 0x654a870 VA: 0x7598b62870
	public virtual String get_AlgorithmName() { }
	// RVA: 0x654a8b0 VA: 0x7598b628b0
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x654aaa8 VA: 0x7598b62aa8
	private Byte GetByte() { }
	// RVA: 0x654ab08 VA: 0x7598b62b08
	public virtual Void ProcessBytes(Byte[] input, Int32 inOff, Int32 len, Byte[] output, Int32 outOff) { }
	// RVA: 0x654aca4 VA: 0x7598b62ca4
	public virtual Void Reset() { }
	// RVA: 0x654aca8 VA: 0x7598b62ca8
	public virtual Byte ReturnByte(Byte input) { }
	// RVA: 0x654acc0 VA: 0x7598b62cc0
	public Void .ctor() { }
}
```
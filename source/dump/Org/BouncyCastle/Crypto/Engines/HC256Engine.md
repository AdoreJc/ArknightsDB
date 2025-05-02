# HC256Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `UInt32 cnt`

- `Boolean initialised`

- `Int32 idx`


## Methods

- `UInt32 Step()`

- `Void Init()`

- `Byte GetByte()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class HC256Engine : IStreamCipher
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

	// RVA: 0x654ad78 VA: 0x7598b62d78
	private UInt32 Step() { }
	// RVA: 0x654aff4 VA: 0x7598b62ff4
	private Void Init() { }
	// RVA: 0x654b3a0 VA: 0x7598b633a0
	public virtual String get_AlgorithmName() { }
	// RVA: 0x654b3e0 VA: 0x7598b633e0
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x654b5d8 VA: 0x7598b635d8
	private Byte GetByte() { }
	// RVA: 0x654b638 VA: 0x7598b63638
	public virtual Void ProcessBytes(Byte[] input, Int32 inOff, Int32 len, Byte[] output, Int32 outOff) { }
	// RVA: 0x654b7d4 VA: 0x7598b637d4
	public virtual Void Reset() { }
	// RVA: 0x654b7d8 VA: 0x7598b637d8
	public virtual Byte ReturnByte(Byte input) { }
	// RVA: 0x654afec VA: 0x7598b62fec
	private static UInt32 RotateRight(UInt32 x, Int32 bits) { }
	// RVA: 0x654b7f0 VA: 0x7598b637f0
	public Void .ctor() { }
}
```
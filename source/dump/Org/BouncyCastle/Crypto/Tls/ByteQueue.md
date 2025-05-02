# ByteQueue

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `Int32 skipped`

- `Int32 available`


## Properties

- `Int32 Available`


## Methods

- `Void Read(Byte[], Int32, Int32, Int32)`

- `Void AddData(Byte[], Int32, Int32)`

- `Void RemoveData(Int32)`

- `Void RemoveData(Byte[], Int32, Int32, Int32)`

- `Int32 get_Available()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class ByteQueue
{
	private const Int32 DefaultCapacity; // 0x0
	private Byte[] databuf; // 0x10
	private Int32 skipped; // 0x18
	private Int32 available; // 0x1c

	public Int32 Available { get; }

	// RVA: 0x64db14c VA: 0x7598af314c
	public static Int32 NextTwoPow(Int32 i) { }
	// RVA: 0x64db168 VA: 0x7598af3168
	public Void .ctor() { }
	// RVA: 0x64db170 VA: 0x7598af3170
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x64db1e0 VA: 0x7598af31e0
	public Void Read(Byte[] buf, Int32 offset, Int32 len, Int32 skip) { }
	// RVA: 0x64db428 VA: 0x7598af3428
	public Void AddData(Byte[] data, Int32 offset, Int32 len) { }
	// RVA: 0x64db550 VA: 0x7598af3550
	public Void RemoveData(Int32 i) { }
	// RVA: 0x64db628 VA: 0x7598af3628
	public Void RemoveData(Byte[] buf, Int32 off, Int32 len, Int32 skip) { }
	// RVA: 0x64db654 VA: 0x7598af3654
	public Byte[] RemoveData(Int32 len, Int32 skip) { }
	// RVA: 0x64db6dc VA: 0x7598af36dc
	public Int32 get_Available() { }
}
```
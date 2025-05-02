# CriStructMemory

**Namespace:** `CriWare`


## Fields

- `GCHandle gch`


## Properties

- `IntPtr ptr`


## Methods

- `Void set_bytes(Byte[])`

- `IntPtr get_ptr()`

- `Void Dispose()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriStructMemory`1 : IDisposable
{
	private Byte[] <bytes>k__BackingField; // 0x0
	private GCHandle gch; // 0x0

	public Byte[] bytes { get; set; }
	public IntPtr ptr { get; }

	// RVA: 0x VA: 0x0
	public Byte[] get_bytes() { }
	// RVA: 0x VA: 0x0
	private Void set_bytes(Byte[] value) { }
	// RVA: 0x VA: 0x0
	public IntPtr get_ptr() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 num) { }
	// RVA: 0x VA: 0x0
	public Void Dispose() { }
}
```
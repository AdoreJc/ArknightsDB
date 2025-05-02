# CriAtomEx3dRegion

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`


## Properties

- `IntPtr nativeHandle`


## Methods

- `Void Dispose(Boolean)`

- `Boolean IsDestroyable()`

- `IntPtr get_nativeHandle()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomEx3dRegion : CriDisposable
{
	private IntPtr handle; // 0x20

	public IntPtr nativeHandle { get; }

	// RVA: 0x411700c VA: 0x759672f00c
	public Void .ctor() { }
	// RVA: 0x41230c8 VA: 0x759673b0c8
	public override Void Dispose() { }
	// RVA: 0x41230d0 VA: 0x759673b0d0
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x4123240 VA: 0x759673b240
	protected override Void Finalize() { }
	// RVA: 0x41232d8 VA: 0x759673b2d8
	public Boolean IsDestroyable() { }
	// RVA: 0x4123364 VA: 0x759673b364
	public IntPtr get_nativeHandle() { }
}
```
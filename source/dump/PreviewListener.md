# PreviewListener

**Namespace:** ` `


## Fields

- `Boolean disposed`


## Methods

- `Void Dispose()`

- `Void dispose()`

- `Void Set3dTransform(Single)`

- `Void Exile()`

- `Void ClearLastPos()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : 
private class PreviewListener : IDisposable
{
	public readonly CriAtomEx3dListener listener; // 0x10
	public readonly CriAtomListener transformObj; // 0x18
	private Nullable`1 lastPos; // 0x20
	private Boolean disposed; // 0x30


	// RVA: 0x4154f30 VA: 0x759676cf30
	public Void .ctor(CriAtomListener listenerObj) { }
	// RVA: 0x41558f4 VA: 0x759676d8f4
	protected override Void Finalize() { }
	// RVA: 0x4154ed0 VA: 0x759676ced0
	public Void Dispose() { }
	// RVA: 0x4155988 VA: 0x759676d988
	private Void dispose() { }
	// RVA: 0x4154fc8 VA: 0x759676cfc8
	public Void Set3dTransform(Single deltaTime) { }
	// RVA: 0x4155220 VA: 0x759676d220
	public Void Exile() { }
	// RVA: 0x41559c0 VA: 0x759676d9c0
	public Void ClearLastPos() { }
}
```
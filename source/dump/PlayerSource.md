# PlayerSource

**Namespace:** ` `


## Fields

- `Boolean disposed`


## Methods

- `Void Dispose()`

- `Void dispose()`

- `Void Set3dTransform(Vector3, Vector3, Vector3, Single)`

- `Void ClearLastPos()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : 
private class PlayerSource : IDisposable
{
	public readonly CriAtomExPlayer player; // 0x10
	public readonly CriAtomEx3dSource source3d; // 0x18
	private Nullable`1 lastPos; // 0x20
	private Boolean disposed; // 0x30


	// RVA: 0x4154c74 VA: 0x759676cc74
	public Void .ctor() { }
	// RVA: 0x4155814 VA: 0x759676d814
	protected override Void Finalize() { }
	// RVA: 0x41557b4 VA: 0x759676d7b4
	public Void Dispose() { }
	// RVA: 0x41558a8 VA: 0x759676d8a8
	private Void dispose() { }
	// RVA: 0x4154d60 VA: 0x759676cd60
	public Void Set3dTransform(Vector3 pos, Vector3 forward, Vector3 up, Single deltaTime) { }
	// RVA: 0x4155260 VA: 0x759676d260
	public Void ClearLastPos() { }
}
```
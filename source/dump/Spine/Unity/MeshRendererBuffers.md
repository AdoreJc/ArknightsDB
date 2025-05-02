# MeshRendererBuffers

**Namespace:** `Spine.Unity`


## Methods

- `Void Initialize()`

- `Boolean MaterialsChangedInLastUpdate()`

- `Void UpdateSharedMaterials(ExposedList`1)`

- `SmartMesh GetNextMesh()`

- `Void Clear()`

- `Void Dispose()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class MeshRendererBuffers : IDisposable
{
	private DoubleBuffered`1 doubleBufferedMesh; // 0x10
	internal readonly ExposedList`1 submeshMaterials; // 0x18
	internal Material[] sharedMaterials; // 0x20


	// RVA: 0x620ed80 VA: 0x7598826d80
	public Void Initialize() { }
	// RVA: 0x6211ff4 VA: 0x7598829ff4
	public Material[] GetUpdatedSharedMaterialsArray() { }
	// RVA: 0x6212094 VA: 0x759882a094
	public Boolean MaterialsChangedInLastUpdate() { }
	// RVA: 0x62117bc VA: 0x75988297bc
	public Void UpdateSharedMaterials(ExposedList`1 instructions) { }
	// RVA: 0x620f45c VA: 0x759882745c
	public SmartMesh GetNextMesh() { }
	// RVA: 0x621b15c VA: 0x759883315c
	public Void Clear() { }
	// RVA: 0x621b1e0 VA: 0x75988331e0
	public Void Dispose() { }
	// RVA: 0x620ecc8 VA: 0x7598826cc8
	public Void .ctor() { }
}
```
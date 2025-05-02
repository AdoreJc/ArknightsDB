# SkeletonPartsRenderer

**Namespace:** `Spine.Unity`


## Fields

- `MeshGenerator meshGenerator`

- `MeshRenderer meshRenderer`

- `MeshFilter meshFilter`

- `SkeletonPartsRendererDelegate OnMeshAndMaterialsUpdated`

- `MeshRendererBuffers buffers`

- `SkeletonRendererInstruction currentInstructions`


## Properties

- `MeshGenerator MeshGenerator`

- `MeshRenderer MeshRenderer`

- `MeshFilter MeshFilter`


## Methods

- `MeshGenerator get_MeshGenerator()`

- `MeshRenderer get_MeshRenderer()`

- `MeshFilter get_MeshFilter()`

- `Void add_OnMeshAndMaterialsUpdated(SkeletonPartsRendererDelegate)`

- `Void remove_OnMeshAndMaterialsUpdated(SkeletonPartsRendererDelegate)`

- `Void LazyIntialize()`

- `Void ClearMesh()`

- `Void RenderParts(ExposedList`1, Int32, Int32)`

- `Void SetPropertyBlock(MaterialPropertyBlock)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonPartsRenderer : MonoBehaviour
{
	private MeshGenerator meshGenerator; // 0x18
	private MeshRenderer meshRenderer; // 0x20
	private MeshFilter meshFilter; // 0x28
	private SkeletonPartsRendererDelegate OnMeshAndMaterialsUpdated; // 0x30
	private MeshRendererBuffers buffers; // 0x38
	private SkeletonRendererInstruction currentInstructions; // 0x40

	public MeshGenerator MeshGenerator { get; }
	public MeshRenderer MeshRenderer { get; }
	public MeshFilter MeshFilter { get; }

	// RVA: 0x620ea04 VA: 0x7598826a04
	public MeshGenerator get_MeshGenerator() { }
	// RVA: 0x620eb60 VA: 0x7598826b60
	public MeshRenderer get_MeshRenderer() { }
	// RVA: 0x620eb78 VA: 0x7598826b78
	public MeshFilter get_MeshFilter() { }
	// RVA: 0x620eb90 VA: 0x7598826b90
	public Void add_OnMeshAndMaterialsUpdated(SkeletonPartsRendererDelegate value) { }
	// RVA: 0x620ec2c VA: 0x7598826c2c
	public Void remove_OnMeshAndMaterialsUpdated(SkeletonPartsRendererDelegate value) { }
	// RVA: 0x620ea1c VA: 0x7598826a1c
	private Void LazyIntialize() { }
	// RVA: 0x620f1e8 VA: 0x75988271e8
	public Void ClearMesh() { }
	// RVA: 0x620f210 VA: 0x7598827210
	public Void RenderParts(ExposedList`1 instructions, Int32 startSubmesh, Int32 endSubmesh) { }
	// RVA: 0x6212480 VA: 0x759882a480
	public Void SetPropertyBlock(MaterialPropertyBlock block) { }
	// RVA: 0x62124b4 VA: 0x759882a4b4
	public static SkeletonPartsRenderer NewPartsRendererGameObject(Transform parent, String name, Int32 sortingOrder) { }
	// RVA: 0x62126a4 VA: 0x759882a6a4
	public Void .ctor() { }
}
```
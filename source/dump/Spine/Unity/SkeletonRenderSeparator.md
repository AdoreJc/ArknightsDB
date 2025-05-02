# SkeletonRenderSeparator

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonRenderer skeletonRenderer`

- `MeshRenderer mainMeshRenderer`

- `Boolean copyPropertyBlock`

- `Boolean copyMeshRendererFlags`

- `SkeletonRendererDelegate OnMeshAndMaterialsUpdated`

- `MaterialPropertyBlock copiedBlock`


## Properties

- `SkeletonRenderer SkeletonRenderer`


## Methods

- `SkeletonRenderer get_SkeletonRenderer()`

- `Void set_SkeletonRenderer(SkeletonRenderer)`

- `Void add_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate)`

- `Void remove_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate)`

- `SkeletonPartsRenderer AddPartsRenderer(Int32, String)`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void HandleRender(SkeletonRendererInstruction)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonRenderSeparator : MonoBehaviour
{
	public const Int32 DefaultSortingOrderIncrement; // 0x0
	protected SkeletonRenderer skeletonRenderer; // 0x18
	private MeshRenderer mainMeshRenderer; // 0x20
	public Boolean copyPropertyBlock; // 0x28
	public Boolean copyMeshRendererFlags; // 0x29
	public List`1 partsRenderers; // 0x30
	private SkeletonRendererDelegate OnMeshAndMaterialsUpdated; // 0x38
	private MaterialPropertyBlock copiedBlock; // 0x40

	public SkeletonRenderer SkeletonRenderer { get; set; }

	// RVA: 0x621297c VA: 0x759882a97c
	public SkeletonRenderer get_SkeletonRenderer() { }
	// RVA: 0x6212984 VA: 0x759882a984
	public Void set_SkeletonRenderer(SkeletonRenderer value) { }
	// RVA: 0x6212ab8 VA: 0x759882aab8
	public Void add_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate value) { }
	// RVA: 0x6212b54 VA: 0x759882ab54
	public Void remove_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate value) { }
	// RVA: 0x6212bf0 VA: 0x759882abf0
	public static SkeletonRenderSeparator AddToSkeletonRenderer(SkeletonRenderer skeletonRenderer, Int32 sortingLayerID, Int32 extraPartsRenderers, Int32 sortingOrderIncrement, Int32 baseSortingOrder, Boolean addMinimumPartsRenderers) { }
	// RVA: 0x6213190 VA: 0x759882b190
	public SkeletonPartsRenderer AddPartsRenderer(Int32 sortingOrderIncrement, String name) { }
	// RVA: 0x6212e68 VA: 0x759882ae68
	public Void OnEnable() { }
	// RVA: 0x6213360 VA: 0x759882b360
	public Void OnDisable() { }
	// RVA: 0x621357c VA: 0x759882b57c
	private Void HandleRender(SkeletonRendererInstruction instruction) { }
	// RVA: 0x6213890 VA: 0x759882b890
	public Void .ctor() { }
}
```
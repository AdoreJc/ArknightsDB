# SkeletonRenderer

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonDataAsset skeletonDataAsset`

- `String initialSkinName`

- `Boolean initialFlipX`

- `Boolean initialFlipY`

- `UpdateMode updateMode`

- `UpdateMode updateWhenInvisible`

- `Single zSpacing`

- `Boolean useClipping`

- `Boolean immutableTriangles`

- `Boolean pmaVertexColors`

- `Boolean clearStateOnDisable`

- `Boolean tintBlack`

- `Boolean singleSubmesh`

- `Boolean fixDrawOrder`

- `Boolean addNormals`

- `Boolean calculateTangents`

- `SpriteMaskInteraction maskInteraction`

- `SpriteMaskInteractionMaterials maskMaterials`

- `Boolean disableRenderingOnOverride`

- `InstructionDelegate generateMeshOverride`

- `MeshGeneratorDelegate OnPostProcessVertices`

- `MeshRenderer meshRenderer`

- `MeshFilter meshFilter`

- `Boolean valid`

- `Skeleton skeleton`

- `SkeletonRendererDelegate OnRebuild`

- `SkeletonRendererDelegate OnMeshAndMaterialsUpdated`

- `MaterialPropertyBlock reusedPropertyBlock`


## Properties

- `UpdateMode UpdateMode`

- `Skeleton Skeleton`

- `SkeletonDataAsset SkeletonDataAsset`


## Methods

- `Void TORAPPU_cacheFixedBoundsCenter(Boolean)`

- `UpdateMode get_UpdateMode()`

- `Void set_UpdateMode(UpdateMode)`

- `Void add_generateMeshOverride(InstructionDelegate)`

- `Void remove_generateMeshOverride(InstructionDelegate)`

- `Void add_GenerateMeshOverride(InstructionDelegate)`

- `Void remove_GenerateMeshOverride(InstructionDelegate)`

- `Void add_OnPostProcessVertices(MeshGeneratorDelegate)`

- `Void remove_OnPostProcessVertices(MeshGeneratorDelegate)`

- `Skeleton get_Skeleton()`

- `Void add_OnRebuild(SkeletonRendererDelegate)`

- `Void remove_OnRebuild(SkeletonRendererDelegate)`

- `Void add_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate)`

- `Void remove_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate)`

- `SkeletonDataAsset get_SkeletonDataAsset()`

- `Void SetMeshSettings(Settings)`

- `Void OnDisable()`

- `Void OnDestroy()`

- `Void EnsureMeshGeneratorCapacity(Int32)`

- `Void OnBecameVisible()`

- `Void OnBecameInvisible()`

- `Boolean Torappu_GetEnable()`

- `Void Torappu_OnBecameVisible()`

- `Void Torappu_OnBecameInvisible()`

- `Void FindAndApplySeparatorSlots(String, Boolean, Boolean)`

- `Void FindAndApplySeparatorSlots(Func`2, Boolean, Boolean)`

- `Void ReapplySeparatorSlotNames()`

- `Void AssignSpriteMaskMaterials()`

- `Boolean InitSpriteMaskMaterialsInsideMask()`

- `Boolean InitSpriteMaskMaterialsOutsideMask()`

- `Boolean InitSpriteMaskMaterialsForMaskType(CompareFunction, ref)`

- `Void SetMaterialSettingsToFixDrawOrder()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonRenderer : MonoBehaviour, ISkeletonComponent, IHasSkeletonDataAsset
{
	public Nullable`1 fixedBoundsCenter; // 0x18
	public SkeletonDataAsset skeletonDataAsset; // 0x28
	public String initialSkinName; // 0x30
	public Boolean initialFlipX; // 0x38
	public Boolean initialFlipY; // 0x39
	protected UpdateMode updateMode; // 0x3c
	public UpdateMode updateWhenInvisible; // 0x40
	protected String[] separatorSlotNames; // 0x48
	public readonly List`1 separatorSlots; // 0x50
	public Single zSpacing; // 0x58
	public Boolean useClipping; // 0x5c
	public Boolean immutableTriangles; // 0x5d
	public Boolean pmaVertexColors; // 0x5e
	public Boolean clearStateOnDisable; // 0x5f
	public Boolean tintBlack; // 0x60
	public Boolean singleSubmesh; // 0x61
	public Boolean fixDrawOrder; // 0x62
	public Boolean addNormals; // 0x63
	public Boolean calculateTangents; // 0x64
	public SpriteMaskInteraction maskInteraction; // 0x68
	public SpriteMaskInteractionMaterials maskMaterials; // 0x70
	public static readonly Int32 STENCIL_COMP_PARAM_ID; // 0x0
	public const CompareFunction STENCIL_COMP_MASKINTERACTION_NONE; // 0x0
	public const CompareFunction STENCIL_COMP_MASKINTERACTION_VISIBLE_INSIDE; // 0x0
	public const CompareFunction STENCIL_COMP_MASKINTERACTION_VISIBLE_OUTSIDE; // 0x0
	public Boolean disableRenderingOnOverride; // 0x78
	private InstructionDelegate generateMeshOverride; // 0x80
	private MeshGeneratorDelegate OnPostProcessVertices; // 0x88
	private readonly Dictionary`2 customMaterialOverride; // 0x90
	private readonly Dictionary`2 customSlotMaterials; // 0x98
	private readonly SkeletonRendererInstruction currentInstructions; // 0xa0
	private readonly MeshGenerator meshGenerator; // 0xa8
	private readonly MeshRendererBuffers rendererBuffers; // 0xb0
	private MeshRenderer meshRenderer; // 0xb8
	private MeshFilter meshFilter; // 0xc0
	public Boolean valid; // 0xc8
	public Skeleton skeleton; // 0xd0
	private SkeletonRendererDelegate OnRebuild; // 0xd8
	private SkeletonRendererDelegate OnMeshAndMaterialsUpdated; // 0xe0
	private MaterialPropertyBlock reusedPropertyBlock; // 0xe8
	public static readonly Int32 SUBMESH_DUMMY_PARAM_ID; // 0x4

	public UpdateMode UpdateMode { get; set; }
	public Dictionary`2 CustomMaterialOverride { get; }
	public Dictionary`2 CustomSlotMaterials { get; }
	public Skeleton Skeleton { get; }
	public SkeletonDataAsset SkeletonDataAsset { get; }

	// RVA: 0x6203d50 VA: 0x759881bd50
	protected Void TORAPPU_cacheFixedBoundsCenter(Boolean isInit) { }
	// RVA: 0x620aa20 VA: 0x7598822a20
	public UpdateMode get_UpdateMode() { }
	// RVA: 0x620aa28 VA: 0x7598822a28
	public Void set_UpdateMode(UpdateMode value) { }
	// RVA: 0x620aa30 VA: 0x7598822a30
	private Void add_generateMeshOverride(InstructionDelegate value) { }
	// RVA: 0x620aacc VA: 0x7598822acc
	private Void remove_generateMeshOverride(InstructionDelegate value) { }
	// RVA: 0x620ab68 VA: 0x7598822b68
	public Void add_GenerateMeshOverride(InstructionDelegate value) { }
	// RVA: 0x620ac24 VA: 0x7598822c24
	public Void remove_GenerateMeshOverride(InstructionDelegate value) { }
	// RVA: 0x620ace0 VA: 0x7598822ce0
	public Void add_OnPostProcessVertices(MeshGeneratorDelegate value) { }
	// RVA: 0x620ad7c VA: 0x7598822d7c
	public Void remove_OnPostProcessVertices(MeshGeneratorDelegate value) { }
	// RVA: 0x620ae18 VA: 0x7598822e18
	public Dictionary`2 get_CustomMaterialOverride() { }
	// RVA: 0x620ae20 VA: 0x7598822e20
	public Dictionary`2 get_CustomSlotMaterials() { }
	// RVA: 0x61fff5c VA: 0x7598817f5c
	public Skeleton get_Skeleton() { }
	// RVA: 0x61fc004 VA: 0x7598814004
	public Void add_OnRebuild(SkeletonRendererDelegate value) { }
	// RVA: 0x61fbf68 VA: 0x7598813f68
	public Void remove_OnRebuild(SkeletonRendererDelegate value) { }
	// RVA: 0x620ae28 VA: 0x7598822e28
	public Void add_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate value) { }
	// RVA: 0x620aec4 VA: 0x7598822ec4
	public Void remove_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate value) { }
	// RVA: 0x620af60 VA: 0x7598822f60
	public SkeletonDataAsset get_SkeletonDataAsset() { }
	// RVA: 0x VA: 0x0
	public static T NewSpineGameObject(SkeletonDataAsset skeletonDataAsset, Boolean quiet) { }
	// RVA: 0x VA: 0x0
	public static T AddSpineComponent(GameObject gameObject, SkeletonDataAsset skeletonDataAsset, Boolean quiet) { }
	// RVA: 0x620af68 VA: 0x7598822f68
	public Void SetMeshSettings(Settings settings) { }
	// RVA: 0x620afb8 VA: 0x7598822fb8
	public virtual Void Awake() { }
	// RVA: 0x620afe4 VA: 0x7598822fe4
	private Void OnDisable() { }
	// RVA: 0x620b004 VA: 0x7598823004
	private Void OnDestroy() { }
	// RVA: 0x6203014 VA: 0x759881b014
	public virtual Void ClearState() { }
	// RVA: 0x620b02c VA: 0x759882302c
	public Void EnsureMeshGeneratorCapacity(Int32 minimumVertexCount) { }
	// RVA: 0x6203210 VA: 0x759881b210
	public virtual Void Initialize(Boolean overwrite, Boolean quiet) { }
	// RVA: 0x6203744 VA: 0x759881b744
	public virtual Void LateUpdate() { }
	// RVA: 0x620b434 VA: 0x7598823434
	public Void OnBecameVisible() { }
	// RVA: 0x620b458 VA: 0x7598823458
	public Void OnBecameInvisible() { }
	// RVA: 0x620b464 VA: 0x7598823464
	public Boolean Torappu_GetEnable() { }
	// RVA: 0x620b4ec VA: 0x75988234ec
	public Void Torappu_OnBecameVisible() { }
	// RVA: 0x620b5d0 VA: 0x75988235d0
	public Void Torappu_OnBecameInvisible() { }
	// RVA: 0x620b69c VA: 0x759882369c
	public Void FindAndApplySeparatorSlots(String startsWith, Boolean clearExistingSeparators, Boolean updateStringArray) { }
	// RVA: 0x620b7a4 VA: 0x75988237a4
	public Void FindAndApplySeparatorSlots(Func`2 slotNamePredicate, Boolean clearExistingSeparators, Boolean updateStringArray) { }
	// RVA: 0x620bcac VA: 0x7598823cac
	public Void ReapplySeparatorSlotNames() { }
	// RVA: 0x620b054 VA: 0x7598823054
	private Void AssignSpriteMaskMaterials() { }
	// RVA: 0x620bdf8 VA: 0x7598823df8
	private Boolean InitSpriteMaskMaterialsInsideMask() { }
	// RVA: 0x620be20 VA: 0x7598823e20
	private Boolean InitSpriteMaskMaterialsOutsideMask() { }
	// RVA: 0x620be48 VA: 0x7598823e48
	private Boolean InitSpriteMaskMaterialsForMaskType(CompareFunction maskFunction, ref Material[] materialsToFill) { }
	// RVA: 0x620b238 VA: 0x7598823238
	private Void SetMaterialSettingsToFixDrawOrder() { }
	// RVA: 0x6203ee4 VA: 0x759881bee4
	public Void .ctor() { }
	// RVA: 0x620bfd8 VA: 0x7598823fd8
	private static Void .cctor() { }
}
```
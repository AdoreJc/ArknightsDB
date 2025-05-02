# SkeletonGraphic

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonDataAsset skeletonDataAsset`

- `String initialSkinName`

- `Boolean initialFlipX`

- `Boolean initialFlipY`

- `String startingAnimation`

- `Boolean startingLoop`

- `Single timeScale`

- `Boolean freeze`

- `UpdateMode updateMode`

- `UpdateMode updateWhenInvisible`

- `Boolean unscaledTime`

- `Boolean allowMultipleCanvasRenderers`

- `Int32 usedRenderersCount`

- `Boolean enableSeparatorSlots`

- `Boolean updateSeparatorPartLocation`

- `Boolean wasUpdatedAfterInit`

- `Texture baseTexture`

- `Texture overrideTexture`

- `Skeleton skeleton`

- `SkeletonRendererDelegate OnRebuild`

- `SkeletonRendererDelegate OnMeshAndMaterialsUpdated`

- `AnimationState state`

- `MeshGenerator meshGenerator`

- `SkeletonRendererInstruction currentInstructions`

- `Boolean reverseMesh`

- `UpdateBonesDelegate BeforeApply`

- `UpdateBonesDelegate UpdateLocal`

- `UpdateBonesDelegate UpdateWorld`

- `UpdateBonesDelegate UpdateComplete`

- `MeshGeneratorDelegate OnPostProcessVertices`


## Properties

- `SkeletonDataAsset SkeletonDataAsset`

- `UpdateMode UpdateMode`

- `Texture OverrideTexture`

- `Skeleton Skeleton`

- `SkeletonData SkeletonData`

- `Boolean IsValid`

- `AnimationState AnimationState`

- `MeshGenerator MeshGenerator`

- `Boolean ReverseMesh`


## Methods

- `SkeletonDataAsset get_SkeletonDataAsset()`

- `UpdateMode get_UpdateMode()`

- `Void set_UpdateMode(UpdateMode)`

- `Texture get_OverrideTexture()`

- `Void set_OverrideTexture(Texture)`

- `Void SyncRawImagesWithCanvasRenderers()`

- `Void UpdateAnimationStatus(Single)`

- `Void ApplyAnimation()`

- `Void LateUpdate()`

- `Void OnCullStateChanged(Boolean)`

- `Void OnBecameVisible()`

- `Void OnBecameInvisible()`

- `Void ReapplySeparatorSlotNames()`

- `Skeleton get_Skeleton()`

- `Void set_Skeleton(Skeleton)`

- `SkeletonData get_SkeletonData()`

- `Boolean get_IsValid()`

- `Void add_OnRebuild(SkeletonRendererDelegate)`

- `Void remove_OnRebuild(SkeletonRendererDelegate)`

- `Void add_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate)`

- `Void remove_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate)`

- `AnimationState get_AnimationState()`

- `MeshGenerator get_MeshGenerator()`

- `Void set_ReverseMesh(Boolean)`

- `Mesh GetLastMesh()`

- `Boolean MatchRectTransformWithBounds()`

- `Boolean MatchRectTransformSingleRenderer()`

- `Boolean MatchRectTransformMultipleRenderers()`

- `Void SetRectTransformBounds(Bounds)`

- `Void add_BeforeApply(UpdateBonesDelegate)`

- `Void remove_BeforeApply(UpdateBonesDelegate)`

- `Void add_UpdateLocal(UpdateBonesDelegate)`

- `Void remove_UpdateLocal(UpdateBonesDelegate)`

- `Void add_UpdateWorld(UpdateBonesDelegate)`

- `Void remove_UpdateWorld(UpdateBonesDelegate)`

- `Void add_UpdateComplete(UpdateBonesDelegate)`

- `Void remove_UpdateComplete(UpdateBonesDelegate)`

- `Void add_OnPostProcessVertices(MeshGeneratorDelegate)`

- `Void remove_OnPostProcessVertices(MeshGeneratorDelegate)`

- `Void Clear()`

- `Void TrimRenderers()`

- `Void Initialize(Boolean)`

- `Void UpdateMesh(Boolean)`

- `Boolean HasMultipleSubmeshInstructions()`

- `Void InitMeshBuffers()`

- `Void DisposeMeshBuffers()`

- `Void UpdateMeshSingleCanvasRenderer()`

- `Void UpdateMeshMultipleCanvasRenderers(SkeletonRendererInstruction, Boolean)`

- `Void EnsureCanvasRendererCount(Int32)`

- `Void DisableUnusedCanvasRenderers(Int32)`

- `Void EnsureMeshesCount(Int32)`

- `Void DestroyMeshes()`

- `Void EnsureSeparatorPartCount()`

- `Void UpdateSeparatorPartParents()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonGraphic : MaskableGraphic, ISkeletonComponent, IAnimationStateComponent, ISkeletonAnimation, IHasSkeletonDataAsset
{
	public SkeletonDataAsset skeletonDataAsset; // 0xe0
	public String initialSkinName; // 0xe8
	public Boolean initialFlipX; // 0xf0
	public Boolean initialFlipY; // 0xf1
	public String startingAnimation; // 0xf8
	public Boolean startingLoop; // 0x100
	public Single timeScale; // 0x104
	public Boolean freeze; // 0x108
	protected UpdateMode updateMode; // 0x10c
	public UpdateMode updateWhenInvisible; // 0x110
	public Boolean unscaledTime; // 0x114
	public Boolean allowMultipleCanvasRenderers; // 0x115
	public List`1 canvasRenderers; // 0x118
	protected List`1 rawImages; // 0x120
	protected Int32 usedRenderersCount; // 0x128
	public const String SeparatorPartGameObjectName; // 0x0
	protected String[] separatorSlotNames; // 0x130
	public readonly List`1 separatorSlots; // 0x138
	public Boolean enableSeparatorSlots; // 0x140
	protected List`1 separatorParts; // 0x148
	public Boolean updateSeparatorPartLocation; // 0x150
	private Boolean wasUpdatedAfterInit; // 0x151
	private Texture baseTexture; // 0x158
	private readonly Dictionary`2 customTextureOverride; // 0x160
	private readonly Dictionary`2 customMaterialOverride; // 0x168
	private Texture overrideTexture; // 0x170
	protected Skeleton skeleton; // 0x178
	private SkeletonRendererDelegate OnRebuild; // 0x180
	private SkeletonRendererDelegate OnMeshAndMaterialsUpdated; // 0x188
	protected AnimationState state; // 0x190
	protected MeshGenerator meshGenerator; // 0x198
	private DoubleBuffered`1 meshBuffers; // 0x1a0
	private SkeletonRendererInstruction currentInstructions; // 0x1a8
	private readonly ExposedList`1 meshes; // 0x1b0
	private Boolean reverseMesh; // 0x1b8
	private UpdateBonesDelegate BeforeApply; // 0x1c0
	private UpdateBonesDelegate UpdateLocal; // 0x1c8
	private UpdateBonesDelegate UpdateWorld; // 0x1d0
	private UpdateBonesDelegate UpdateComplete; // 0x1d8
	private MeshGeneratorDelegate OnPostProcessVertices; // 0x1e0

	public SkeletonDataAsset SkeletonDataAsset { get; }
	public UpdateMode UpdateMode { get; set; }
	public List`1 SeparatorParts { get; }
	public Dictionary`2 CustomTextureOverride { get; }
	public Dictionary`2 CustomMaterialOverride { get; }
	public Texture OverrideTexture { get; set; }
	public override Texture mainTexture { get; }
	public Skeleton Skeleton { get; set; }
	public SkeletonData SkeletonData { get; }
	public Boolean IsValid { get; }
	public AnimationState AnimationState { get; }
	public MeshGenerator MeshGenerator { get; }
	public Boolean ReverseMesh { set; }

	// RVA: 0x6204154 VA: 0x759881c154
	public SkeletonDataAsset get_SkeletonDataAsset() { }
	// RVA: 0x620415c VA: 0x759881c15c
	public UpdateMode get_UpdateMode() { }
	// RVA: 0x6204164 VA: 0x759881c164
	public Void set_UpdateMode(UpdateMode value) { }
	// RVA: 0x620416c VA: 0x759881c16c
	public List`1 get_SeparatorParts() { }
	// RVA: 0x6204174 VA: 0x759881c174
	public static SkeletonGraphic NewSkeletonGraphicGameObject(SkeletonDataAsset skeletonDataAsset, Transform parent, Material material) { }
	// RVA: 0x6204270 VA: 0x759881c270
	public static SkeletonGraphic AddSkeletonGraphicComponent(GameObject gameObject, SkeletonDataAsset skeletonDataAsset, Material material) { }
	// RVA: 0x6204350 VA: 0x759881c350
	public Dictionary`2 get_CustomTextureOverride() { }
	// RVA: 0x6204358 VA: 0x759881c358
	public Dictionary`2 get_CustomMaterialOverride() { }
	// RVA: 0x6204360 VA: 0x759881c360
	public Texture get_OverrideTexture() { }
	// RVA: 0x6204368 VA: 0x759881c368
	public Void set_OverrideTexture(Texture value) { }
	// RVA: 0x62043c4 VA: 0x759881c3c4
	public override Texture get_mainTexture() { }
	// RVA: 0x620443c VA: 0x759881c43c
	protected override Void Awake() { }
	// RVA: 0x6204828 VA: 0x759881c828
	protected override Void OnDestroy() { }
	// RVA: 0x6204904 VA: 0x759881c904
	public override Void Rebuild(CanvasUpdate update) { }
	// RVA: 0x6204a0c VA: 0x759881ca0c
	protected override Void OnDisable() { }
	// RVA: 0x6204b64 VA: 0x759881cb64
	public virtual Void Update() { }
	// RVA: 0x6204bb0 VA: 0x759881cbb0
	public virtual Void Update(Single deltaTime) { }
	// RVA: 0x6204528 VA: 0x759881c528
	protected Void SyncRawImagesWithCanvasRenderers() { }
	// RVA: 0x6204bfc VA: 0x759881cbfc
	protected Void UpdateAnimationStatus(Single deltaTime) { }
	// RVA: 0x6204c44 VA: 0x759881cc44
	protected Void ApplyAnimation() { }
	// RVA: 0x6204d18 VA: 0x759881cd18
	public Void LateUpdate() { }
	// RVA: 0x6204d6c VA: 0x759881cd6c
	protected Void OnCullStateChanged(Boolean culled) { }
	// RVA: 0x6204d90 VA: 0x759881cd90
	public Void OnBecameVisible() { }
	// RVA: 0x6204d84 VA: 0x759881cd84
	public Void OnBecameInvisible() { }
	// RVA: 0x6204d9c VA: 0x759881cd9c
	public Void ReapplySeparatorSlotNames() { }
	// RVA: 0x61fc8ec VA: 0x75988148ec
	public Skeleton get_Skeleton() { }
	// RVA: 0x6205140 VA: 0x759881d140
	public Void set_Skeleton(Skeleton value) { }
	// RVA: 0x6205150 VA: 0x759881d150
	public SkeletonData get_SkeletonData() { }
	// RVA: 0x61fc918 VA: 0x7598814918
	public Boolean get_IsValid() { }
	// RVA: 0x61feb0c VA: 0x7598816b0c
	public Void add_OnRebuild(SkeletonRendererDelegate value) { }
	// RVA: 0x61fea6c VA: 0x7598816a6c
	public Void remove_OnRebuild(SkeletonRendererDelegate value) { }
	// RVA: 0x6205168 VA: 0x759881d168
	public Void add_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate value) { }
	// RVA: 0x6205208 VA: 0x759881d208
	public Void remove_OnMeshAndMaterialsUpdated(SkeletonRendererDelegate value) { }
	// RVA: 0x62052a8 VA: 0x759881d2a8
	public AnimationState get_AnimationState() { }
	// RVA: 0x62052c4 VA: 0x759881d2c4
	public MeshGenerator get_MeshGenerator() { }
	// RVA: 0x62052cc VA: 0x759881d2cc
	public Void set_ReverseMesh(Boolean value) { }
	// RVA: 0x62052d8 VA: 0x759881d2d8
	public Mesh GetLastMesh() { }
	// RVA: 0x6205334 VA: 0x759881d334
	public Boolean MatchRectTransformWithBounds() { }
	// RVA: 0x6205364 VA: 0x759881d364
	protected Boolean MatchRectTransformSingleRenderer() { }
	// RVA: 0x6205480 VA: 0x759881d480
	protected Boolean MatchRectTransformMultipleRenderers() { }
	// RVA: 0x6205694 VA: 0x759881d694
	private Void SetRectTransformBounds(Bounds combinedBounds) { }
	// RVA: 0x6205734 VA: 0x759881d734
	public Void add_BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x62057d4 VA: 0x759881d7d4
	public Void remove_BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x6205874 VA: 0x759881d874
	public Void add_UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x6205914 VA: 0x759881d914
	public Void remove_UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x62059b4 VA: 0x759881d9b4
	public Void add_UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x6205a54 VA: 0x759881da54
	public Void remove_UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x6205af4 VA: 0x759881daf4
	public Void add_UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6205b94 VA: 0x759881db94
	public Void remove_UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6205c34 VA: 0x759881dc34
	public Void add_OnPostProcessVertices(MeshGeneratorDelegate value) { }
	// RVA: 0x6205cd4 VA: 0x759881dcd4
	public Void remove_OnPostProcessVertices(MeshGeneratorDelegate value) { }
	// RVA: 0x6204844 VA: 0x759881c844
	public Void Clear() { }
	// RVA: 0x6205f9c VA: 0x759881df9c
	public Void TrimRenderers() { }
	// RVA: 0x61febb4 VA: 0x7598816bb4
	public Void Initialize(Boolean overwrite) { }
	// RVA: 0x6204984 VA: 0x759881c984
	public Void UpdateMesh(Boolean keepRendererCount) { }
	// RVA: 0x6206f34 VA: 0x759881ef34
	public Boolean HasMultipleSubmeshInstructions() { }
	// RVA: 0x6206298 VA: 0x759881e298
	protected Void InitMeshBuffers() { }
	// RVA: 0x6205f04 VA: 0x759881df04
	protected Void DisposeMeshBuffers() { }
	// RVA: 0x620636c VA: 0x759881e36c
	protected Void UpdateMeshSingleCanvasRenderer() { }
	// RVA: 0x6206770 VA: 0x759881e770
	protected Void UpdateMeshMultipleCanvasRenderers(SkeletonRendererInstruction currentInstructions, Boolean keepRendererCount) { }
	// RVA: 0x6207060 VA: 0x759881f060
	protected Void EnsureCanvasRendererCount(Int32 targetCount) { }
	// RVA: 0x6206fa4 VA: 0x759881efa4
	protected Void DisableUnusedCanvasRenderers(Int32 usedCount) { }
	// RVA: 0x6207410 VA: 0x759881f410
	protected Void EnsureMeshesCount(Int32 targetCount) { }
	// RVA: 0x6205d74 VA: 0x759881dd74
	protected Void DestroyMeshes() { }
	// RVA: 0x62074c0 VA: 0x759881f4c0
	protected Void EnsureSeparatorPartCount() { }
	// RVA: 0x6204f34 VA: 0x759881cf34
	protected Void UpdateSeparatorPartParents() { }
	// RVA: 0x62077c8 VA: 0x759881f7c8
	public Void .ctor() { }
}
```
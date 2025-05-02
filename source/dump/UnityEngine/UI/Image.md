# Image

**Namespace:** `UnityEngine.UI`


## Fields

- `Sprite m_Sprite`

- `Rect m_RuntimeAtlasRect`

- `Rect m_RuntimeAtlasTextureRect`

- `Vector4 m_RuntimeAtlasBorder`

- `Single m_RuntimeAtlasPixelsPerUnit`

- `Boolean m_PackIntoRuntimeAtlas`

- `Int32 m_AtlasHandleId`

- `AtlasHandle m_atlasHandle`

- `Int32 m_panelLevel`

- `Action m_onEnableRuntimeAtlas`

- `Sprite m_OverrideSprite`

- `Type m_Type`

- `Boolean m_PreserveAspect`

- `Boolean m_FillCenter`

- `FillMethod m_FillMethod`

- `Single m_FillAmount`

- `Boolean m_FillClockwise`

- `Int32 m_FillOrigin`

- `Single m_AlphaHitTestMinimumThreshold`

- `Boolean m_Tracked`

- `Boolean m_UseSpriteMesh`

- `Single m_PixelsPerUnitMultiplier`

- `Single m_CachedReferencePixelsPerUnit`


## Properties

- `Rect runtimeAtlasRect`

- `Rect runtimeAtlasTextureRect`

- `Vector4 runtimeAtlasBorder`

- `Single runtimeAtlasPixelsPerUnit`

- `Int32 atlasHandleId`

- `AtlasHandle atlasHandle`

- `Int32 panelLevel`

- `Sprite sprite`

- `Boolean enableRuntimeAtlasRaw`

- `Sprite overrideSprite`

- `Sprite activeSprite`

- `Type type`

- `Boolean preserveAspect`

- `Boolean fillCenter`

- `FillMethod fillMethod`

- `Single fillAmount`

- `Boolean fillClockwise`

- `Int32 fillOrigin`

- `Single eventAlphaThreshold`

- `Single alphaHitTestMinimumThreshold`

- `Boolean useSpriteMesh`

- `Boolean hasBorder`

- `Single pixelsPerUnitMultiplier`

- `Single pixelsPerUnit`

- `Single multipliedPixelsPerUnit`


## Methods

- `Rect get_runtimeAtlasRect()`

- `Void set_runtimeAtlasRect(Rect)`

- `Rect get_runtimeAtlasTextureRect()`

- `Void set_runtimeAtlasTextureRect(Rect)`

- `Vector4 get_runtimeAtlasBorder()`

- `Void set_runtimeAtlasBorder(Vector4)`

- `Single get_runtimeAtlasPixelsPerUnit()`

- `Void set_runtimeAtlasPixelsPerUnit(Single)`

- `Int32 get_atlasHandleId()`

- `Void set_atlasHandleId(Int32)`

- `Int32 get_panelLevel()`

- `Sprite get_sprite()`

- `Void set_sprite(Sprite)`

- `Boolean get_enableRuntimeAtlasRaw()`

- `Void ReleaseSprite()`

- `Void RegisterOnEnableRuntimeAtlas(Action)`

- `Void UnregisterOnEnableRuntimeAtlas(Action)`

- `Void OnEnableRuntimeAtlas()`

- `Void DisableSpriteOptimizations()`

- `Sprite get_overrideSprite()`

- `Void set_overrideSprite(Sprite)`

- `Sprite get_activeSprite()`

- `Type get_type()`

- `Void set_type(Type)`

- `Boolean get_preserveAspect()`

- `Void set_preserveAspect(Boolean)`

- `Boolean get_fillCenter()`

- `Void set_fillCenter(Boolean)`

- `FillMethod get_fillMethod()`

- `Void set_fillMethod(FillMethod)`

- `Single get_fillAmount()`

- `Void set_fillAmount(Single)`

- `Boolean get_fillClockwise()`

- `Void set_fillClockwise(Boolean)`

- `Int32 get_fillOrigin()`

- `Void set_fillOrigin(Int32)`

- `Single get_eventAlphaThreshold()`

- `Void set_eventAlphaThreshold(Single)`

- `Single get_alphaHitTestMinimumThreshold()`

- `Void set_alphaHitTestMinimumThreshold(Single)`

- `Boolean get_useSpriteMesh()`

- `Void set_useSpriteMesh(Boolean)`

- `Boolean get_hasBorder()`

- `Single get_pixelsPerUnitMultiplier()`

- `Void set_pixelsPerUnitMultiplier(Single)`

- `Single get_pixelsPerUnit()`

- `Single get_multipliedPixelsPerUnit()`

- `Void PreserveSpriteAspectRatio(ref, Vector2)`

- `Vector4 GetDrawingDimensions(Boolean)`

- `Void TrackSprite()`

- `Void GenerateSimpleSprite(VertexHelper, Boolean)`

- `Void GenerateSprite(VertexHelper, Boolean)`

- `Void GenerateSlicedSprite(VertexHelper)`

- `Void GenerateTiledSprite(VertexHelper)`

- `Vector4 GetAdjustedBorders(Vector4, Rect)`

- `Void GenerateFilledSprite(VertexHelper, Boolean)`

- `Vector2 MapCoordinate(Vector2, Rect)`

- `Vector4 GetRuntimeAtlasSpritePadding()`

- `Vector4 GetRuntimeAtlasSpriteOuterUV()`

- `Vector4 GetRuntimeAtlasSpriteInnerUV()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Image : MaskableGraphic, ISerializationCallbackReceiver, ILayoutElement, ICanvasRaycastFilter
{
	protected static Material s_ETC1DefaultUI; // 0x0
	private Sprite m_Sprite; // 0xe0
	protected Rect m_RuntimeAtlasRect; // 0xe8
	protected Rect m_RuntimeAtlasTextureRect; // 0xf8
	protected Vector4 m_RuntimeAtlasBorder; // 0x108
	protected Single m_RuntimeAtlasPixelsPerUnit; // 0x118
	private Boolean m_PackIntoRuntimeAtlas; // 0x11c
	private Int32 m_AtlasHandleId; // 0x120
	private AtlasHandle m_atlasHandle; // 0x124
	private Int32 m_panelLevel; // 0x148
	private Action m_onEnableRuntimeAtlas; // 0x150
	private Sprite m_OverrideSprite; // 0x158
	private Type m_Type; // 0x160
	private Boolean m_PreserveAspect; // 0x164
	private Boolean m_FillCenter; // 0x165
	private FillMethod m_FillMethod; // 0x168
	private Single m_FillAmount; // 0x16c
	private Boolean m_FillClockwise; // 0x170
	private Int32 m_FillOrigin; // 0x174
	private Single m_AlphaHitTestMinimumThreshold; // 0x178
	private Boolean m_Tracked; // 0x17c
	private Boolean m_UseSpriteMesh; // 0x17d
	private Single m_PixelsPerUnitMultiplier; // 0x180
	private Single m_CachedReferencePixelsPerUnit; // 0x184
	private static ImageAspects s_aspects; // 0x8
	private static readonly Vector2[] s_VertScratch; // 0x10
	private static readonly Vector2[] s_UVScratch; // 0x18
	private static readonly Vector3[] s_Xy; // 0x20
	private static readonly Vector3[] s_Uv; // 0x28
	private static List`1 m_TrackedTexturelessImages; // 0x30
	private static Boolean s_Initialized; // 0x38

	public Rect runtimeAtlasRect { get; set; }
	public Rect runtimeAtlasTextureRect { get; set; }
	public Vector4 runtimeAtlasBorder { get; set; }
	public Single runtimeAtlasPixelsPerUnit { get; set; }
	public Int32 atlasHandleId { get; set; }
	public virtual Boolean packIntoRuntimeAtlas { get; }
	public AtlasHandle atlasHandle { get; }
	public Int32 panelLevel { get; }
	public Sprite sprite { get; set; }
	public Boolean enableRuntimeAtlasRaw { get; }
	public override Boolean enableRuntimeAtlas { get; set; }
	public Sprite overrideSprite { get; set; }
	private Sprite activeSprite { get; }
	public Type type { get; set; }
	public Boolean preserveAspect { get; set; }
	public Boolean fillCenter { get; set; }
	public FillMethod fillMethod { get; set; }
	public Single fillAmount { get; set; }
	public Boolean fillClockwise { get; set; }
	public Int32 fillOrigin { get; set; }
	public Single eventAlphaThreshold { get; set; }
	public Single alphaHitTestMinimumThreshold { get; set; }
	public Boolean useSpriteMesh { get; set; }
	public static Material defaultETC1GraphicMaterial { get; }
	public override Texture mainTexture { get; }
	public Boolean hasBorder { get; }
	public Single pixelsPerUnitMultiplier { get; set; }
	public Single pixelsPerUnit { get; }
	protected Single multipliedPixelsPerUnit { get; }
	public override Material material { get; set; }
	public virtual Single minWidth { get; }
	public virtual Single preferredWidth { get; }
	public virtual Single flexibleWidth { get; }
	public virtual Single minHeight { get; }
	public virtual Single preferredHeight { get; }
	public virtual Single flexibleHeight { get; }
	public virtual Int32 layoutPriority { get; }

	// RVA: 0x6923638 VA: 0x7598f3b638
	public Rect get_runtimeAtlasRect() { }
	// RVA: 0x6923644 VA: 0x7598f3b644
	public Void set_runtimeAtlasRect(Rect value) { }
	// RVA: 0x6923650 VA: 0x7598f3b650
	public Rect get_runtimeAtlasTextureRect() { }
	// RVA: 0x6923660 VA: 0x7598f3b660
	public Void set_runtimeAtlasTextureRect(Rect value) { }
	// RVA: 0x6923670 VA: 0x7598f3b670
	public Vector4 get_runtimeAtlasBorder() { }
	// RVA: 0x6923684 VA: 0x7598f3b684
	public Void set_runtimeAtlasBorder(Vector4 value) { }
	// RVA: 0x6923698 VA: 0x7598f3b698
	public Single get_runtimeAtlasPixelsPerUnit() { }
	// RVA: 0x69236a0 VA: 0x7598f3b6a0
	public Void set_runtimeAtlasPixelsPerUnit(Single value) { }
	// RVA: 0x69236a8 VA: 0x7598f3b6a8
	public Int32 get_atlasHandleId() { }
	// RVA: 0x69236b0 VA: 0x7598f3b6b0
	public Void set_atlasHandleId(Int32 value) { }
	// RVA: 0x69236b8 VA: 0x7598f3b6b8
	public virtual Boolean get_packIntoRuntimeAtlas() { }
	// RVA: 0x69236c0 VA: 0x7598f3b6c0
	public ref AtlasHandle get_atlasHandle() { }
	// RVA: 0x69236c8 VA: 0x7598f3b6c8
	public Int32 get_panelLevel() { }
	// RVA: 0x69236d0 VA: 0x7598f3b6d0
	public Sprite get_sprite() { }
	// RVA: 0x6915f20 VA: 0x7598f2df20
	public Void set_sprite(Sprite value) { }
	// RVA: 0x69237c4 VA: 0x7598f3b7c4
	public Boolean get_enableRuntimeAtlasRaw() { }
	// RVA: 0x69237cc VA: 0x7598f3b7cc
	public override Boolean get_enableRuntimeAtlas() { }
	// RVA: 0x6923844 VA: 0x7598f3b844
	public override Void set_enableRuntimeAtlas(Boolean value) { }
	// RVA: 0x692387c VA: 0x7598f3b87c
	public Void ReleaseSprite() { }
	// RVA: 0x6923888 VA: 0x7598f3b888
	public Void RegisterOnEnableRuntimeAtlas(Action callBack) { }
	// RVA: 0x692391c VA: 0x7598f3b91c
	public Void UnregisterOnEnableRuntimeAtlas(Action callBack) { }
	// RVA: 0x69239b0 VA: 0x7598f3b9b0
	public Void OnEnableRuntimeAtlas() { }
	// RVA: 0x69239cc VA: 0x7598f3b9cc
	public Void DisableSpriteOptimizations() { }
	// RVA: 0x69239d4 VA: 0x7598f3b9d4
	public Sprite get_overrideSprite() { }
	// RVA: 0x6923a50 VA: 0x7598f3ba50
	public Void set_overrideSprite(Sprite value) { }
	// RVA: 0x69239d8 VA: 0x7598f3b9d8
	private Sprite get_activeSprite() { }
	// RVA: 0x6923ad8 VA: 0x7598f3bad8
	public Type get_type() { }
	// RVA: 0x6916268 VA: 0x7598f2e268
	public Void set_type(Type value) { }
	// RVA: 0x6923ae0 VA: 0x7598f3bae0
	public Boolean get_preserveAspect() { }
	// RVA: 0x6923ae8 VA: 0x7598f3bae8
	public Void set_preserveAspect(Boolean value) { }
	// RVA: 0x6923b68 VA: 0x7598f3bb68
	public Boolean get_fillCenter() { }
	// RVA: 0x6923b70 VA: 0x7598f3bb70
	public Void set_fillCenter(Boolean value) { }
	// RVA: 0x6923bf0 VA: 0x7598f3bbf0
	public FillMethod get_fillMethod() { }
	// RVA: 0x6923bf8 VA: 0x7598f3bbf8
	public Void set_fillMethod(FillMethod value) { }
	// RVA: 0x6923c70 VA: 0x7598f3bc70
	public Single get_fillAmount() { }
	// RVA: 0x6923c78 VA: 0x7598f3bc78
	public Void set_fillAmount(Single value) { }
	// RVA: 0x6923d08 VA: 0x7598f3bd08
	public Boolean get_fillClockwise() { }
	// RVA: 0x6923d10 VA: 0x7598f3bd10
	public Void set_fillClockwise(Boolean value) { }
	// RVA: 0x6923d90 VA: 0x7598f3bd90
	public Int32 get_fillOrigin() { }
	// RVA: 0x6923d98 VA: 0x7598f3bd98
	public Void set_fillOrigin(Int32 value) { }
	// RVA: 0x6923e18 VA: 0x7598f3be18
	public Single get_eventAlphaThreshold() { }
	// RVA: 0x6923e28 VA: 0x7598f3be28
	public Void set_eventAlphaThreshold(Single value) { }
	// RVA: 0x6923e38 VA: 0x7598f3be38
	public Single get_alphaHitTestMinimumThreshold() { }
	// RVA: 0x6923e40 VA: 0x7598f3be40
	public Void set_alphaHitTestMinimumThreshold(Single value) { }
	// RVA: 0x6923e48 VA: 0x7598f3be48
	public Boolean get_useSpriteMesh() { }
	// RVA: 0x6923e50 VA: 0x7598f3be50
	public Void set_useSpriteMesh(Boolean value) { }
	// RVA: 0x6923ed0 VA: 0x7598f3bed0
	protected Void .ctor() { }
	// RVA: 0x6923f58 VA: 0x7598f3bf58
	public static Material get_defaultETC1GraphicMaterial() { }
	// RVA: 0x6924044 VA: 0x7598f3c044
	public override Texture get_mainTexture() { }
	// RVA: 0x69241bc VA: 0x7598f3c1bc
	public Boolean get_hasBorder() { }
	// RVA: 0x69242a0 VA: 0x7598f3c2a0
	public Single get_pixelsPerUnitMultiplier() { }
	// RVA: 0x69242a8 VA: 0x7598f3c2a8
	public Void set_pixelsPerUnitMultiplier(Single value) { }
	// RVA: 0x69242c8 VA: 0x7598f3c2c8
	public Single get_pixelsPerUnit() { }
	// RVA: 0x69243dc VA: 0x7598f3c3dc
	protected Single get_multipliedPixelsPerUnit() { }
	// RVA: 0x69243f8 VA: 0x7598f3c3f8
	public override Material get_material() { }
	// RVA: 0x6924524 VA: 0x7598f3c524
	public override Void set_material(Material value) { }
	// RVA: 0x6924528 VA: 0x7598f3c528
	public virtual Void OnBeforeSerialize() { }
	// RVA: 0x692452c VA: 0x7598f3c52c
	public virtual Void OnAfterDeserialize() { }
	// RVA: 0x692457c VA: 0x7598f3c57c
	private Void PreserveSpriteAspectRatio(ref Rect rect, Vector2 spriteSize) { }
	// RVA: 0x69246d4 VA: 0x7598f3c6d4
	private Vector4 GetDrawingDimensions(Boolean shouldPreserveAspect) { }
	// RVA: 0x6924bdc VA: 0x7598f3cbdc
	public override Void SetNativeSize() { }
	// RVA: 0x6924dc4 VA: 0x7598f3cdc4
	protected override Void OnPopulateMesh(VertexHelper toFill) { }
	// RVA: 0x69236d8 VA: 0x7598f3b6d8
	private Void TrackSprite() { }
	// RVA: 0x692a810 VA: 0x7598f42810
	public static Void BindAspects(ImageAspects aspects) { }
	// RVA: 0x692a870 VA: 0x7598f42870
	protected override Void Awake() { }
	// RVA: 0x692a8f4 VA: 0x7598f428f4
	protected override Void OnDestroy() { }
	// RVA: 0x692a974 VA: 0x7598f42974
	protected override Void OnEnable() { }
	// RVA: 0x692aa00 VA: 0x7598f42a00
	protected override Void OnDisable() { }
	// RVA: 0x692aaf4 VA: 0x7598f42af4
	protected override Void UpdateMaterial() { }
	// RVA: 0x692abe8 VA: 0x7598f42be8
	protected override Void OnCanvasHierarchyChanged() { }
	// RVA: 0x6924f00 VA: 0x7598f3cf00
	private Void GenerateSimpleSprite(VertexHelper vh, Boolean lPreserveAspect) { }
	// RVA: 0x6925a48 VA: 0x7598f3da48
	private Void GenerateSprite(VertexHelper vh, Boolean lPreserveAspect) { }
	// RVA: 0x6926038 VA: 0x7598f3e038
	private Void GenerateSlicedSprite(VertexHelper toFill) { }
	// RVA: 0x69268ec VA: 0x7598f3e8ec
	private Void GenerateTiledSprite(VertexHelper toFill) { }
	// RVA: 0x692b304 VA: 0x7598f43304
	private static Void AddQuad(VertexHelper vertexHelper, Vector3[] quadPositions, Color32 color, Vector3[] quadUVs) { }
	// RVA: 0x692b1b0 VA: 0x7598f431b0
	private static Void AddQuad(VertexHelper vertexHelper, Vector2 posMin, Vector2 posMax, Color32 color, Vector2 uvMin, Vector2 uvMax) { }
	// RVA: 0x692b050 VA: 0x7598f43050
	private Vector4 GetAdjustedBorders(Vector4 border, Rect adjustedRect) { }
	// RVA: 0x6929284 VA: 0x7598f41284
	private Void GenerateFilledSprite(VertexHelper toFill, Boolean preserveAspect) { }
	// RVA: 0x692b3e8 VA: 0x7598f433e8
	private static Boolean RadialCut(Vector3[] xy, Vector3[] uv, Single fill, Boolean invert, Int32 corner) { }
	// RVA: 0x692b508 VA: 0x7598f43508
	private static Void RadialCut(Vector3[] xy, Single cos, Single sin, Boolean invert, Int32 corner) { }
	// RVA: 0x692b8f4 VA: 0x7598f438f4
	public virtual Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x692b8f8 VA: 0x7598f438f8
	public virtual Void CalculateLayoutInputVertical() { }
	// RVA: 0x692b8fc VA: 0x7598f438fc
	public virtual Single get_minWidth() { }
	// RVA: 0x692b904 VA: 0x7598f43904
	public virtual Single get_preferredWidth() { }
	// RVA: 0x692ba34 VA: 0x7598f43a34
	public virtual Single get_flexibleWidth() { }
	// RVA: 0x692ba3c VA: 0x7598f43a3c
	public virtual Single get_minHeight() { }
	// RVA: 0x692ba44 VA: 0x7598f43a44
	public virtual Single get_preferredHeight() { }
	// RVA: 0x692bb74 VA: 0x7598f43b74
	public virtual Single get_flexibleHeight() { }
	// RVA: 0x692bb7c VA: 0x7598f43b7c
	public virtual Int32 get_layoutPriority() { }
	// RVA: 0x692bb84 VA: 0x7598f43b84
	public virtual Boolean IsRaycastLocationValid(Vector2 screenPoint, Camera eventCamera) { }
	// RVA: 0x692bf10 VA: 0x7598f43f10
	private Vector2 MapCoordinate(Vector2 local, Rect rect) { }
	// RVA: 0x692c250 VA: 0x7598f44250
	private static Void RebuildImage(SpriteAtlas spriteAtlas) { }
	// RVA: 0x692a6a8 VA: 0x7598f426a8
	private static Void TrackImage(Image g) { }
	// RVA: 0x692aa74 VA: 0x7598f42a74
	private static Void UnTrackImage(Image g) { }
	// RVA: 0x692c3f8 VA: 0x7598f443f8
	protected override Void OnDidApplyAnimationProperties() { }
	// RVA: 0x6924b30 VA: 0x7598f3cb30
	protected Vector4 GetRuntimeAtlasSpritePadding() { }
	// RVA: 0x692acf0 VA: 0x7598f42cf0
	protected Vector4 GetRuntimeAtlasSpriteOuterUV() { }
	// RVA: 0x692ae24 VA: 0x7598f42e24
	protected Vector4 GetRuntimeAtlasSpriteInnerUV() { }
	// RVA: 0x692c430 VA: 0x7598f44430
	private static Void .cctor() { }
}
```
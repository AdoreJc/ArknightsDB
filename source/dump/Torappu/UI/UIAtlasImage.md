# UIAtlasImage

**Namespace:** `Torappu.UI`


## Fields

- `UIAtlasObject _initAtlas`

- `String _initSpriteId`

- `Boolean _clipBorder`

- `MeshType _meshType`

- `Vector4 _sliceVec`

- `AtlasSprite m_runtimeSprite`

- `SpriteRenderData m_runtimeRD`


## Properties

- `Single pixelsPerUnit`

- `SpriteRenderData RuntimeRD`


## Methods

- `Void _SetToRuntimeSprite(SpriteRenderData)`

- `SpriteRenderData _InitRuntimeSprite()`

- `Single get_pixelsPerUnit()`

- `SpriteRenderData get_RuntimeRD()`

- `Void SetSprite(SpriteRenderData)`

- `Void ClearSprite()`

- `Void _SetToInitSprite()`

- `Void _GenerateSimpleSprite(VertexHelper)`

- `Boolean _GenerateSliceSprite(VertexHelper)`

- `Vector4 _GetDrawingDimensions()`

- `Void _AddQuad(VertexHelper, Vector2, Vector2, Color32, Vector2, Vector2)`

- `Void _AddQuadRotate(VertexHelper, Vector2, Vector2, Color32, Vector2, Vector2)`

- `Vector4 _GetAdjustedBorders(Vector4, Vector2)`

- `Material <>xLuaBaseProxy_get_material()`

- `Void <>xLuaBaseProxy_set_material(Material)`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`

- `Void <>xLuaBaseProxy_UpdateMaterial()`

- `Texture <>xLuaBaseProxy_get_mainTexture()`

- `Void <>xLuaBaseProxy_SetNativeSize()`

- `Void <>xLuaBaseProxy_OnEnable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAtlasImage : MaskableGraphic, IHotfixable
{
	private const Single FIXED_PIXELS_PER_UNIT; // 0x0
	private const Single UV_UNIT; // 0x0
	private const Int32 BORDER_PADDING; // 0x0
	private UIAtlasObject _initAtlas; // 0xe0
	private String _initSpriteId; // 0xe8
	private Boolean _clipBorder; // 0xf0
	private MeshType _meshType; // 0xf4
	private Vector4 _sliceVec; // 0xf8
	private AtlasSprite m_runtimeSprite; // 0x108
	private static readonly Vector2[] s_vertScratch; // 0x0
	private static readonly Vector2[] s_uvScratch; // 0x8
	private static Material s_defaultMat; // 0x10
	private static Material s_defaultETC1Mat; // 0x18
	private SpriteRenderData m_runtimeRD; // 0x110
	private static DelegateBridge __Hotfix0__SetToRuntimeSprite; // 0x20
	private static DelegateBridge __Hotfix0__InitRuntimeSprite; // 0x28
	private static DelegateBridge __Hotfix0_get_material; // 0x30
	private static DelegateBridge __Hotfix0_set_material; // 0x38
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x40
	private static DelegateBridge __Hotfix0_UpdateMaterial; // 0x48
	private static DelegateBridge __Hotfix0_get_mainTexture; // 0x50
	private static DelegateBridge __Hotfix0_SetNativeSize; // 0x58
	private static DelegateBridge __Hotfix0_get_pixelsPerUnit; // 0x60
	private static DelegateBridge __Hotfix0_get_RuntimeRD; // 0x68
	private static DelegateBridge __Hotfix0_OnEnable; // 0x70
	private static DelegateBridge __Hotfix0_SetSprite; // 0x78
	private static DelegateBridge __Hotfix0_ClearSprite; // 0x80
	private static DelegateBridge __Hotfix0__SetToInitSprite; // 0x88
	private static DelegateBridge __Hotfix0__GenerateSimpleSprite; // 0x90
	private static DelegateBridge __Hotfix0__GenerateSliceSprite; // 0x98
	private static DelegateBridge __Hotfix0__GetDrawingDimensions; // 0xa0
	private static DelegateBridge __Hotfix0__AddQuad; // 0xa8
	private static DelegateBridge __Hotfix0__AddQuadRotate; // 0xb0
	private static DelegateBridge __Hotfix0__GetAdjustedBorders; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public override Material material { get; set; }
	public override Texture mainTexture { get; }
	public Single pixelsPerUnit { get; }
	public SpriteRenderData RuntimeRD { get; }

	// RVA: 0x2109e14 VA: 0x7594721e14
	private Void _SetToRuntimeSprite(SpriteRenderData renderData) { }
	// RVA: 0x2109fb8 VA: 0x7594721fb8
	private SpriteRenderData _InitRuntimeSprite() { }
	// RVA: 0x210a380 VA: 0x7594722380
	public override Material get_material() { }
	// RVA: 0x210a544 VA: 0x7594722544
	public override Void set_material(Material value) { }
	// RVA: 0x210a5cc VA: 0x75947225cc
	protected override Void OnPopulateMesh(VertexHelper toFill) { }
	// RVA: 0x210b420 VA: 0x7594723420
	protected override Void UpdateMaterial() { }
	// RVA: 0x210b4bc VA: 0x75947234bc
	public override Texture get_mainTexture() { }
	// RVA: 0x210b534 VA: 0x7594723534
	public override Void SetNativeSize() { }
	// RVA: 0x210b6f4 VA: 0x75947236f4
	public Single get_pixelsPerUnit() { }
	// RVA: 0x210b7e8 VA: 0x75947237e8
	public SpriteRenderData get_RuntimeRD() { }
	// RVA: 0x210b894 VA: 0x7594723894
	protected override Void OnEnable() { }
	// RVA: 0x210ba60 VA: 0x7594723a60
	public Void SetSprite(SpriteRenderData renderData) { }
	// RVA: 0x210bbac VA: 0x7594723bac
	public Void ClearSprite() { }
	// RVA: 0x210b95c VA: 0x759472395c
	private Void _SetToInitSprite() { }
	// RVA: 0x210afe8 VA: 0x7594722fe8
	private Void _GenerateSimpleSprite(VertexHelper vh) { }
	// RVA: 0x210a6e4 VA: 0x75947226e4
	private Boolean _GenerateSliceSprite(VertexHelper vh) { }
	// RVA: 0x210bcd4 VA: 0x7594723cd4
	private Vector4 _GetDrawingDimensions() { }
	// RVA: 0x210bfc8 VA: 0x7594723fc8
	private Void _AddQuad(VertexHelper vh, Vector2 posMin, Vector2 posMax, Color32 color, Vector2 uvMin, Vector2 uvMax) { }
	// RVA: 0x210bdcc VA: 0x7594723dcc
	private Void _AddQuadRotate(VertexHelper vh, Vector2 posMin, Vector2 posMax, Color32 color, Vector2 uvMin, Vector2 uvMax) { }
	// RVA: 0x210c420 VA: 0x7594724420
	private Vector4 _GetAdjustedBorders(Vector4 border, Vector2 adjustedSize) { }
	// RVA: 0x210c660 VA: 0x7594724660
	public Void .ctor() { }
	// RVA: 0x210c714 VA: 0x7594724714
	private static Void .cctor() { }
	// RVA: 0x210c7d4 VA: 0x75947247d4
	private Material <>xLuaBaseProxy_get_material() { }
	// RVA: 0x210c7dc VA: 0x75947247dc
	private Void <>xLuaBaseProxy_set_material(Material P0) { }
	// RVA: 0x210c7e4 VA: 0x75947247e4
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
	// RVA: 0x210c7ec VA: 0x75947247ec
	private Void <>xLuaBaseProxy_UpdateMaterial() { }
	// RVA: 0x210c7f4 VA: 0x75947247f4
	private Texture <>xLuaBaseProxy_get_mainTexture() { }
	// RVA: 0x210c844 VA: 0x7594724844
	private Void <>xLuaBaseProxy_SetNativeSize() { }
	// RVA: 0x210c84c VA: 0x759472484c
	private Void <>xLuaBaseProxy_OnEnable() { }
}
```
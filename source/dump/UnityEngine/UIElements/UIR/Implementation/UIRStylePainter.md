# UIRStylePainter

**Namespace:** `UnityEngine.UIElements.UIR.Implementation`


## Fields

- `RenderChain m_Owner`

- `AtlasBase m_Atlas`

- `VectorImageManager m_VectorImageManager`

- `Entry m_CurrentEntry`

- `ClosingInfo m_ClosingInfo`

- `Int32 m_MaskDepth`

- `Int32 m_StencilRef`

- `BMPAlloc m_ClipRectID`

- `Int32 m_SVGBackgroundEntryIndex`

- `Int32 m_NextMeshWriteDataPoolItem`

- `Allocator m_AllocRawVertsIndicesDelegate`

- `Allocator m_AllocThroughDrawMeshDelegate`

- `Allocator m_AllocThroughDrawGradientsDelegate`

- `VisualElement <currentElement>k__BackingField`

- `Int32 <totalVertices>k__BackingField`

- `Int32 <totalIndices>k__BackingField`

- `Boolean <disposed>k__BackingField`


## Properties

- `MeshGenerationContext meshGenerationContext`

- `VisualElement currentElement`

- `ClosingInfo closingInfo`

- `Int32 totalVertices`

- `Int32 totalIndices`

- `Boolean disposed`

- `VisualElement visualElement`


## Methods

- `MeshWriteData GetPooledMeshWriteData()`

- `MeshWriteData AllocRawVertsIndices(UInt32, UInt32, ref)`

- `MeshWriteData AllocThroughDrawMesh(UInt32, UInt32, ref)`

- `MeshWriteData AllocThroughDrawGradients(UInt32, UInt32, ref)`

- `MeshGenerationContext get_meshGenerationContext()`

- `VisualElement get_currentElement()`

- `Void set_currentElement(VisualElement)`

- `ClosingInfo get_closingInfo()`

- `Int32 get_totalVertices()`

- `Void set_totalVertices(Int32)`

- `Int32 get_totalIndices()`

- `Void set_totalIndices(Int32)`

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `Void Dispose(Boolean)`

- `Void Begin(VisualElement)`

- `Void LandClipUnregisterMeshDrawCommand(RenderChainCommand)`

- `Void LandClipRegisterMesh(NativeSlice`1, NativeSlice`1, Int32)`

- `MeshWriteData AddGradientsEntry(Int32, Int32, TextureId, Material, MeshFlags)`

- `MeshWriteData DrawMesh(Int32, Int32, Texture, Material, MeshFlags)`

- `Void DrawText(TextParams, ITextHandle, Single)`

- `Void DrawRectangle(RectangleParams)`

- `Void DrawBorder(BorderParams)`

- `Void DrawImmediate(Action, Boolean)`

- `VisualElement get_visualElement()`

- `Void DrawVisualElementBackground()`

- `Void DrawVisualElementBorder()`

- `Void ApplyVisualElementClipping()`

- `Void DrawSprite(RectangleParams)`

- `Void ApplyInset(ref, Texture)`

- `Void DrawVectorImage(RectangleParams)`

- `Void ValidateMeshWriteData()`

- `Void GenerateStencilClipEntryForRoundedRectBackground()`

- `Void GenerateStencilClipEntryForSVGBackground()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR.Implementation
internal class UIRStylePainter : IStylePainter, IDisposable
{
	private RenderChain m_Owner; // 0x10
	private List`1 m_Entries; // 0x18
	private AtlasBase m_Atlas; // 0x20
	private VectorImageManager m_VectorImageManager; // 0x28
	private Entry m_CurrentEntry; // 0x30
	private ClosingInfo m_ClosingInfo; // 0x90
	private Int32 m_MaskDepth; // 0xc8
	private Int32 m_StencilRef; // 0xcc
	private BMPAlloc m_ClipRectID; // 0xd0
	private Int32 m_SVGBackgroundEntryIndex; // 0xd8
	private TempDataAlloc`1 m_VertsPool; // 0xe0
	private TempDataAlloc`1 m_IndicesPool; // 0x108
	private List`1 m_MeshWriteDataPool; // 0x130
	private Int32 m_NextMeshWriteDataPoolItem; // 0x138
	private Allocator m_AllocRawVertsIndicesDelegate; // 0x140
	private Allocator m_AllocThroughDrawMeshDelegate; // 0x148
	private Allocator m_AllocThroughDrawGradientsDelegate; // 0x150
	private readonly MeshGenerationContext <meshGenerationContext>k__BackingField; // 0x158
	private VisualElement <currentElement>k__BackingField; // 0x160
	private Int32 <totalVertices>k__BackingField; // 0x168
	private Int32 <totalIndices>k__BackingField; // 0x16c
	private Boolean <disposed>k__BackingField; // 0x170

	public MeshGenerationContext meshGenerationContext { get; }
	public VisualElement currentElement { get; set; }
	public List`1 entries { get; }
	public ClosingInfo closingInfo { get; }
	public Int32 totalVertices { get; set; }
	public Int32 totalIndices { get; set; }
	protected Boolean disposed { get; set; }
	public VisualElement visualElement { get; }

	// RVA: 0x696d720 VA: 0x7598f85720
	private MeshWriteData GetPooledMeshWriteData() { }
	// RVA: 0x696d848 VA: 0x7598f85848
	private MeshWriteData AllocRawVertsIndices(UInt32 vertexCount, UInt32 indexCount, ref AllocMeshData allocatorData) { }
	// RVA: 0x696d904 VA: 0x7598f85904
	private MeshWriteData AllocThroughDrawMesh(UInt32 vertexCount, UInt32 indexCount, ref AllocMeshData allocatorData) { }
	// RVA: 0x696de20 VA: 0x7598f85e20
	private MeshWriteData AllocThroughDrawGradients(UInt32 vertexCount, UInt32 indexCount, ref AllocMeshData allocatorData) { }
	// RVA: 0x696e188 VA: 0x7598f86188
	public Void .ctor(RenderChain renderChain) { }
	// RVA: 0x696e568 VA: 0x7598f86568
	public MeshGenerationContext get_meshGenerationContext() { }
	// RVA: 0x696e570 VA: 0x7598f86570
	public VisualElement get_currentElement() { }
	// RVA: 0x696e578 VA: 0x7598f86578
	private Void set_currentElement(VisualElement value) { }
	// RVA: 0x696e588 VA: 0x7598f86588
	public List`1 get_entries() { }
	// RVA: 0x696e590 VA: 0x7598f86590
	public ClosingInfo get_closingInfo() { }
	// RVA: 0x696e5ac VA: 0x7598f865ac
	public Int32 get_totalVertices() { }
	// RVA: 0x696e5b4 VA: 0x7598f865b4
	private Void set_totalVertices(Int32 value) { }
	// RVA: 0x696e5bc VA: 0x7598f865bc
	public Int32 get_totalIndices() { }
	// RVA: 0x696e5c4 VA: 0x7598f865c4
	private Void set_totalIndices(Int32 value) { }
	// RVA: 0x696e5cc VA: 0x7598f865cc
	protected Boolean get_disposed() { }
	// RVA: 0x696e5d4 VA: 0x7598f865d4
	private Void set_disposed(Boolean value) { }
	// RVA: 0x696e5e0 VA: 0x7598f865e0
	public Void Dispose() { }
	// RVA: 0x696e644 VA: 0x7598f86644
	protected Void Dispose(Boolean disposing) { }
	// RVA: 0x696e6c8 VA: 0x7598f866c8
	public Void Begin(VisualElement ve) { }
	// RVA: 0x696ec10 VA: 0x7598f86c10
	public Void LandClipUnregisterMeshDrawCommand(RenderChainCommand cmd) { }
	// RVA: 0x696ec8c VA: 0x7598f86c8c
	public Void LandClipRegisterMesh(NativeSlice`1 vertices, NativeSlice`1 indices, Int32 indexOffset) { }
	// RVA: 0x696de30 VA: 0x7598f85e30
	public MeshWriteData AddGradientsEntry(Int32 vertexCount, Int32 indexCount, TextureId texture, Material material, MeshFlags flags) { }
	// RVA: 0x696d918 VA: 0x7598f85918
	public MeshWriteData DrawMesh(Int32 vertexCount, Int32 indexCount, Texture texture, Material material, MeshFlags flags) { }
	// RVA: 0x696ed28 VA: 0x7598f86d28
	public Void DrawText(TextParams textParams, ITextHandle handle, Single pixelsPerPoint) { }
	// RVA: 0x696ee60 VA: 0x7598f86e60
	internal Void DrawTextNative(TextParams textParams, ITextHandle handle, Single pixelsPerPoint) { }
	// RVA: 0x696f2dc VA: 0x7598f872dc
	internal Void DrawTextCore(TextParams textParams, ITextHandle handle, Single pixelsPerPoint) { }
	// RVA: 0x696f954 VA: 0x7598f87954
	public Void DrawRectangle(RectangleParams rectParams) { }
	// RVA: 0x6970a60 VA: 0x7598f88a60
	public Void DrawBorder(BorderParams borderParams) { }
	// RVA: 0x6970b68 VA: 0x7598f88b68
	public Void DrawImmediate(Action callback, Boolean cullingEnabled) { }
	// RVA: 0x6970cf0 VA: 0x7598f88cf0
	public VisualElement get_visualElement() { }
	// RVA: 0x6970cf8 VA: 0x7598f88cf8
	public Void DrawVisualElementBackground() { }
	// RVA: 0x6971b30 VA: 0x7598f89b30
	public Void DrawVisualElementBorder() { }
	// RVA: 0x69724a4 VA: 0x7598f8a4a4
	public Void ApplyVisualElementClipping() { }
	// RVA: 0x69734c8 VA: 0x7598f8b4c8
	private UInt16[] AdjustSpriteWinding(Vector2[] vertices, UInt16[] indices) { }
	// RVA: 0x6970060 VA: 0x7598f88060
	public Void DrawSprite(RectangleParams rectParams) { }
	// RVA: 0x69706f4 VA: 0x7598f886f4
	private Void ApplyInset(ref RectangleParams rectParams, Texture tex) { }
	// RVA: 0x696fc24 VA: 0x7598f87c24
	public Void DrawVectorImage(RectangleParams rectParams) { }
	// RVA: 0x69737e8 VA: 0x7598f8b7e8
	internal Void Reset() { }
	// RVA: 0x69738dc VA: 0x7598f8b8dc
	private Void ValidateMeshWriteData() { }
	// RVA: 0x6972a70 VA: 0x7598f8aa70
	private Void GenerateStencilClipEntryForRoundedRectBackground() { }
	// RVA: 0x69726f0 VA: 0x7598f8a6f0
	private Void GenerateStencilClipEntryForSVGBackground() { }
}
```
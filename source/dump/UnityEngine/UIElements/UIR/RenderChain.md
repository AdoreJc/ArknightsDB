# RenderChain

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `RenderChainCommand m_FirstCommand`

- `DepthOrderedDirtyTracking m_DirtyTracker`

- `Shader m_DefaultShader`

- `Shader m_DefaultWorldSpaceShader`

- `Material m_DefaultMat`

- `Material m_DefaultWorldSpaceMat`

- `Boolean m_BlockDirtyRegistration`

- `Int32 m_StaticIndex`

- `Int32 m_ActiveRenderNodes`

- `Int32 m_CustomMaterialCommands`

- `ChainBuilderStats m_Stats`

- `UInt32 m_StatsElementsAdded`

- `UInt32 m_StatsElementsRemoved`

- `VisualElement m_FirstTextElement`

- `UIRTextUpdatePainter m_TextUpdatePainter`

- `Int32 m_TextElementCount`

- `Int32 m_DirtyTextStartIndex`

- `Int32 m_DirtyTextRemaining`

- `Boolean m_FontWasReset`

- `TextureRegistry m_TextureRegistry`

- `Boolean <disposed>k__BackingField`

- `BaseVisualElementPanel <panel>k__BackingField`

- `UIRenderDevice <device>k__BackingField`

- `AtlasBase <atlas>k__BackingField`

- `VectorImageManager <vectorImageManager>k__BackingField`

- `UIRStylePainter <painter>k__BackingField`

- `Boolean <drawStats>k__BackingField`

- `Boolean <drawInCameras>k__BackingField`


## Properties

- `Boolean disposed`


## Methods

- `Void Constructor(BaseVisualElementPanel, UIRenderDevice, AtlasBase, VectorImageManager)`

- `Void Destructor()`

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `Void Dispose(Boolean)`

- `Void ProcessChanges()`

- `Void Render()`

- `Void ProcessTextRegen(Boolean)`

- `Void UIEOnChildAdded(VisualElement)`

- `Void UIEOnChildrenReordered(VisualElement)`

- `Void UIEOnChildRemoving(VisualElement)`

- `Void StopTrackingGroupTransformElement(VisualElement)`

- `Void UIEOnRenderHintsChanged(VisualElement)`

- `Void UIEOnClippingChanged(VisualElement, Boolean)`

- `Void UIEOnOpacityChanged(VisualElement, Boolean)`

- `Void UIEOnColorChanged(VisualElement)`

- `Void UIEOnTransformOrSizeChanged(VisualElement, Boolean, Boolean)`

- `Void UIEOnVisualsChanged(VisualElement, Boolean)`

- `Void set_panel(BaseVisualElementPanel)`

- `Void set_device(UIRenderDevice)`

- `Void set_atlas(AtlasBase)`

- `Void set_vectorImageManager(VectorImageManager)`

- `Void set_painter(UIRStylePainter)`

- `Void set_drawInCameras(Boolean)`

- `Void OnFontReset(Font)`

- `Void AppendTexture(VisualElement, Texture, TextureId, Boolean)`

- `Void ResetTextures(VisualElement)`

- `Void DrawStats()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class RenderChain : IDisposable
{
	private RenderChainCommand m_FirstCommand; // 0x10
	private DepthOrderedDirtyTracking m_DirtyTracker; // 0x18
	private LinkedPool`1 m_CommandPool; // 0x40
	private BasicNodePool`1 m_TexturePool; // 0x48
	private List`1 m_RenderNodesData; // 0x50
	private Shader m_DefaultShader; // 0x58
	private Shader m_DefaultWorldSpaceShader; // 0x60
	private Material m_DefaultMat; // 0x68
	private Material m_DefaultWorldSpaceMat; // 0x70
	private Boolean m_BlockDirtyRegistration; // 0x78
	private Int32 m_StaticIndex; // 0x7c
	private Int32 m_ActiveRenderNodes; // 0x80
	private Int32 m_CustomMaterialCommands; // 0x84
	private ChainBuilderStats m_Stats; // 0x88
	private UInt32 m_StatsElementsAdded; // 0xe8
	private UInt32 m_StatsElementsRemoved; // 0xec
	private VisualElement m_FirstTextElement; // 0xf0
	private UIRTextUpdatePainter m_TextUpdatePainter; // 0xf8
	private Int32 m_TextElementCount; // 0x100
	private Int32 m_DirtyTextStartIndex; // 0x104
	private Int32 m_DirtyTextRemaining; // 0x108
	private Boolean m_FontWasReset; // 0x10c
	private Dictionary`2 m_LastGroupTransformElementScale; // 0x110
	private TextureRegistry m_TextureRegistry; // 0x118
	private static ProfilerMarker s_MarkerProcess; // 0x0
	private static ProfilerMarker s_MarkerClipProcessing; // 0x8
	private static ProfilerMarker s_MarkerOpacityProcessing; // 0x10
	private static ProfilerMarker s_MarkerColorsProcessing; // 0x18
	private static ProfilerMarker s_MarkerTransformProcessing; // 0x20
	private static ProfilerMarker s_MarkerVisualsProcessing; // 0x28
	private static ProfilerMarker s_MarkerTextRegen; // 0x30
	private Boolean <disposed>k__BackingField; // 0x120
	internal static Action OnPreRender; // 0x38
	private BaseVisualElementPanel <panel>k__BackingField; // 0x128
	private UIRenderDevice <device>k__BackingField; // 0x130
	private AtlasBase <atlas>k__BackingField; // 0x138
	private VectorImageManager <vectorImageManager>k__BackingField; // 0x140
	internal UIRVEShaderInfoAllocator shaderInfoAllocator; // 0x148
	private UIRStylePainter <painter>k__BackingField; // 0x218
	private Boolean <drawStats>k__BackingField; // 0x220
	private Boolean <drawInCameras>k__BackingField; // 0x221

	protected Boolean disposed { get; set; }
	internal BaseVisualElementPanel panel { get; set; }
	internal UIRenderDevice device { get; set; }
	internal AtlasBase atlas { get; set; }
	internal VectorImageManager vectorImageManager { get; set; }
	internal UIRStylePainter painter { get; set; }
	internal Boolean drawStats { get; set; }
	internal Boolean drawInCameras { get; set; }
	internal Shader defaultShader { set; }
	internal Shader defaultWorldSpaceShader { set; }

	// RVA: 0x6a318d4 VA: 0x75990498d4
	private static Void .cctor() { }
	// RVA: 0x6a31b94 VA: 0x7599049b94
	public Void .ctor(BaseVisualElementPanel panel) { }
	// RVA: 0x6a31f9c VA: 0x7599049f9c
	private Void Constructor(BaseVisualElementPanel panelObj, UIRenderDevice deviceObj, AtlasBase atlas, VectorImageManager vectorImageMan) { }
	// RVA: 0x6a32588 VA: 0x759904a588
	private Void Destructor() { }
	// RVA: 0x6a32a38 VA: 0x759904aa38
	protected Boolean get_disposed() { }
	// RVA: 0x6a32a40 VA: 0x759904aa40
	private Void set_disposed(Boolean value) { }
	// RVA: 0x6a32a4c VA: 0x759904aa4c
	public Void Dispose() { }
	// RVA: 0x6a32abc VA: 0x759904aabc
	protected Void Dispose(Boolean disposing) { }
	// RVA: 0x6a32ae8 VA: 0x759904aae8
	public Void ProcessChanges() { }
	// RVA: 0x6a33694 VA: 0x759904b694
	public Void Render() { }
	// RVA: 0x6a333f8 VA: 0x759904b3f8
	private Void ProcessTextRegen(Boolean timeSliced) { }
	// RVA: 0x6a3497c VA: 0x759904c97c
	public Void UIEOnChildAdded(VisualElement ve) { }
	// RVA: 0x6a34cf4 VA: 0x759904ccf4
	public Void UIEOnChildrenReordered(VisualElement ve) { }
	// RVA: 0x6a34eac VA: 0x759904ceac
	public Void UIEOnChildRemoving(VisualElement ve) { }
	// RVA: 0x6a34fac VA: 0x759904cfac
	public Void StopTrackingGroupTransformElement(VisualElement ve) { }
	// RVA: 0x6a35004 VA: 0x759904d004
	public Void UIEOnRenderHintsChanged(VisualElement ve) { }
	// RVA: 0x6a34b44 VA: 0x759904cb44
	public Void UIEOnClippingChanged(VisualElement ve, Boolean hierarchical) { }
	// RVA: 0x6a34bd4 VA: 0x759904cbd4
	public Void UIEOnOpacityChanged(VisualElement ve, Boolean hierarchical) { }
	// RVA: 0x6a352ac VA: 0x759904d2ac
	public Void UIEOnColorChanged(VisualElement ve) { }
	// RVA: 0x6a35330 VA: 0x759904d330
	public Void UIEOnTransformOrSizeChanged(VisualElement ve, Boolean transformChanged, Boolean clipRectSizeChanged) { }
	// RVA: 0x6a34c64 VA: 0x759904cc64
	public Void UIEOnVisualsChanged(VisualElement ve, Boolean hierarchical) { }
	// RVA: 0x6a353c4 VA: 0x759904d3c4
	internal BaseVisualElementPanel get_panel() { }
	// RVA: 0x6a353cc VA: 0x759904d3cc
	private Void set_panel(BaseVisualElementPanel value) { }
	// RVA: 0x6a353dc VA: 0x759904d3dc
	internal UIRenderDevice get_device() { }
	// RVA: 0x6a353e4 VA: 0x759904d3e4
	private Void set_device(UIRenderDevice value) { }
	// RVA: 0x6a353f4 VA: 0x759904d3f4
	internal AtlasBase get_atlas() { }
	// RVA: 0x6a353fc VA: 0x759904d3fc
	private Void set_atlas(AtlasBase value) { }
	// RVA: 0x6a3540c VA: 0x759904d40c
	internal VectorImageManager get_vectorImageManager() { }
	// RVA: 0x6a35414 VA: 0x759904d414
	private Void set_vectorImageManager(VectorImageManager value) { }
	// RVA: 0x6a35424 VA: 0x759904d424
	internal UIRStylePainter get_painter() { }
	// RVA: 0x6a3542c VA: 0x759904d42c
	private Void set_painter(UIRStylePainter value) { }
	// RVA: 0x6a3543c VA: 0x759904d43c
	internal Boolean get_drawStats() { }
	// RVA: 0x6a35444 VA: 0x759904d444
	internal Void set_drawStats(Boolean value) { }
	// RVA: 0x6a35450 VA: 0x759904d450
	internal Boolean get_drawInCameras() { }
	// RVA: 0x6a35458 VA: 0x759904d458
	private Void set_drawInCameras(Boolean value) { }
	// RVA: 0x6a35464 VA: 0x759904d464
	internal Void set_defaultShader(Shader value) { }
	// RVA: 0x6a3553c VA: 0x759904d53c
	internal Void set_defaultWorldSpaceShader(Shader value) { }
	// RVA: 0x6a339fc VA: 0x759904b9fc
	internal Material GetStandardMaterial() { }
	// RVA: 0x6a35614 VA: 0x759904d614
	internal Material GetStandardWorldSpaceMaterial() { }
	// RVA: 0x6a35720 VA: 0x759904d720
	internal Void EnsureFitsDepth(Int32 depth) { }
	// RVA: 0x6a3585c VA: 0x759904d85c
	internal Void ChildWillBeRemoved(VisualElement ve) { }
	// RVA: 0x6a35910 VA: 0x759904d910
	internal RenderChainCommand AllocCommand() { }
	// RVA: 0x6a35978 VA: 0x759904d978
	internal Void FreeCommand(RenderChainCommand cmd) { }
	// RVA: 0x6a35a28 VA: 0x759904da28
	internal Void OnRenderCommandAdded(RenderChainCommand command) { }
	// RVA: 0x6a35ac0 VA: 0x759904dac0
	internal Void OnRenderCommandsRemoved(RenderChainCommand firstCommand, RenderChainCommand lastCommand) { }
	// RVA: 0x6a35af0 VA: 0x759904daf0
	internal Void AddTextElement(VisualElement ve) { }
	// RVA: 0x6a35b5c VA: 0x759904db5c
	internal Void RemoveTextElement(VisualElement ve) { }
	// RVA: 0x6a35c00 VA: 0x759904dc00
	internal Void OnGroupTransformElementChangedTransform(VisualElement ve) { }
	// RVA: 0x6a35d2c VA: 0x759904dd2c
	private static RenderNodeData AccessRenderNodeData(IntPtr obj) { }
	// RVA: 0x6a35e80 VA: 0x759904de80
	private static Void OnRenderNodeExecute(IntPtr obj) { }
	// RVA: 0x6a35f28 VA: 0x759904df28
	private static Void OnRegisterIntermediateRenderers(Camera camera) { }
	// RVA: 0x6a36418 VA: 0x759904e418
	private static Void OnRegisterIntermediateRendererMat(BaseRuntimePanel rtp, RenderChain renderChain, ref RenderNodeData rnd, Camera camera, Int32 sameDistanceSortPriority) { }
	// RVA: 0x6a36790 VA: 0x759904e790
	internal Void RepaintTexturedElements() { }
	// RVA: 0x6a36870 VA: 0x759904e870
	private Void OnFontReset(Font font) { }
	// RVA: 0x6a3687c VA: 0x759904e87c
	public Void AppendTexture(VisualElement ve, Texture src, TextureId id, Boolean isAtlas) { }
	// RVA: 0x6a3291c VA: 0x759904a91c
	public Void ResetTextures(VisualElement ve) { }
	// RVA: 0x6a33b08 VA: 0x759904bb08
	private Void DrawStats() { }
	// RVA: 0x6a328d4 VA: 0x759904a8d4
	private static VisualElement GetFirstElementInPanel(VisualElement ve) { }
}
```
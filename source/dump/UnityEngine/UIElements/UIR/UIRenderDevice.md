# UIRenderDevice

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `IntPtr m_DefaultStencilState`

- `IntPtr m_VertexDecl`

- `Page m_FirstPage`

- `UInt32 m_NextPageVertexCount`

- `UInt32 m_LargeMeshVertexCount`

- `Single m_IndexToVertexCountRatio`

- `MaterialPropertyBlock m_StandardMatProps`

- `UInt32 m_FrameIndex`

- `UInt32 m_NextUpdateID`

- `DrawStatistics m_DrawStats`

- `Boolean <breakBatches>k__BackingField`

- `Boolean <disposed>k__BackingField`


## Properties

- `Boolean fullyCreated`

- `Boolean disposed`


## Methods

- `Void InitVertexDeclaration()`

- `Void CompleteCreation()`

- `Boolean get_fullyCreated()`

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `MeshHandle Allocate(UInt32, UInt32, out, out, out)`

- `Void Update(MeshHandle, UInt32, out)`

- `Void Update(MeshHandle, UInt32, UInt32, out, out, out)`

- `Void UpdateCopyBackIndices(MeshHandle, Boolean)`

- `Boolean TryAllocFromPage(Page, UInt32, UInt32, ref, ref, Boolean)`

- `Void Allocate(MeshHandle, UInt32, UInt32, out, out, Boolean)`

- `Void UpdateAfterGPUUsedData(MeshHandle, UInt32, UInt32, out, out, out, out, Boolean)`

- `Void Free(MeshHandle)`

- `Void OnFrameRenderingBegin()`

- `Void ApplyDrawCommandState(RenderChainCommand, Int32, Material, Boolean, Boolean, ref)`

- `Void ApplyBatchState(ref, Boolean)`

- `Void EvaluateChain(RenderChainCommand, Material, Material, Texture, Texture, Single, NativeSlice`1, NativeSlice`1, MaterialPropertyBlock, Boolean, ref)`

- `Void UpdateFenceValue()`

- `Void KickRanges(DrawBufferRange*, ref, ref, Int32, Page)`

- `Void DrawRanges(GPUBuffer`1, GPUBuffer`1, NativeSlice`1)`

- `Void WaitOnCpuFence(UInt32)`

- `Void AdvanceFrame()`

- `Void PruneUnusedPages()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class UIRenderDevice : IDisposable
{
	private readonly Boolean m_MockDevice; // 0x10
	private IntPtr m_DefaultStencilState; // 0x18
	private IntPtr m_VertexDecl; // 0x20
	private Page m_FirstPage; // 0x28
	private UInt32 m_NextPageVertexCount; // 0x30
	private UInt32 m_LargeMeshVertexCount; // 0x34
	private Single m_IndexToVertexCountRatio; // 0x38
	private List`1 m_DeferredFrees; // 0x40
	private List`1 m_Updates; // 0x48
	private UInt32[] m_Fences; // 0x50
	private MaterialPropertyBlock m_StandardMatProps; // 0x58
	private UInt32 m_FrameIndex; // 0x60
	private UInt32 m_NextUpdateID; // 0x64
	private DrawStatistics m_DrawStats; // 0x68
	private readonly LinkedPool`1 m_MeshHandles; // 0x90
	private readonly DrawParams m_DrawParams; // 0x98
	private readonly TextureSlotManager m_TextureSlotManager; // 0xa0
	private static LinkedList`1 m_DeviceFreeQueue; // 0x0
	private static Int32 m_ActiveDeviceCount; // 0x8
	private static Boolean m_SubscribedToNotifications; // 0xc
	private static Boolean m_SynchronousFree; // 0xd
	private static readonly Int32 s_FontTexPropID; // 0x10
	private static readonly Int32 s_FontTexSDFScaleID; // 0x14
	private static readonly Int32 s_GradientSettingsTexID; // 0x18
	private static readonly Int32 s_ShaderInfoTexID; // 0x1c
	private static readonly Int32 s_TransformsPropID; // 0x20
	private static readonly Int32 s_ClipRectsPropID; // 0x24
	private static readonly Int32 s_ClipSpaceParamsID; // 0x28
	private static ProfilerMarker s_MarkerAllocate; // 0x30
	private static ProfilerMarker s_MarkerFree; // 0x38
	private static ProfilerMarker s_MarkerAdvanceFrame; // 0x40
	private static ProfilerMarker s_MarkerFence; // 0x48
	private static ProfilerMarker s_MarkerBeforeDraw; // 0x50
	private static Nullable`1 s_VertexTexturingIsAvailable; // 0x58
	private static Nullable`1 s_ShaderModelIs35; // 0x5a
	private readonly UInt32 <maxVerticesPerPage>k__BackingField; // 0xa8
	private Boolean <breakBatches>k__BackingField; // 0xac
	private static Texture2D s_DefaultShaderInfoTexFloat; // 0x60
	private static Texture2D s_DefaultShaderInfoTexARGB8; // 0x68
	private Boolean <disposed>k__BackingField; // 0xad

	internal UInt32 maxVerticesPerPage { get; }
	internal Boolean breakBatches { get; set; }
	internal static Texture2D defaultShaderInfoTexFloat { get; }
	internal static Texture2D defaultShaderInfoTexARGB8 { get; }
	internal static Boolean vertexTexturingIsAvailable { get; }
	internal static Boolean shaderModelIs35 { get; }
	private Boolean fullyCreated { get; }
	protected Boolean disposed { get; set; }

	// RVA: 0x695d668 VA: 0x7598f75668
	internal UInt32 get_maxVerticesPerPage() { }
	// RVA: 0x695d670 VA: 0x7598f75670
	internal Boolean get_breakBatches() { }
	// RVA: 0x695d678 VA: 0x7598f75678
	internal Void set_breakBatches(Boolean value) { }
	// RVA: 0x695d684 VA: 0x7598f75684
	private static Void .cctor() { }
	// RVA: 0x695da4c VA: 0x7598f75a4c
	public Void .ctor(UInt32 initialVertexCapacity, UInt32 initialIndexCapacity) { }
	// RVA: 0x695da54 VA: 0x7598f75a54
	protected Void .ctor(UInt32 initialVertexCapacity, UInt32 initialIndexCapacity, Boolean mockDevice) { }
	// RVA: 0x695b298 VA: 0x7598f73298
	internal static Texture2D get_defaultShaderInfoTexFloat() { }
	// RVA: 0x695afb8 VA: 0x7598f72fb8
	internal static Texture2D get_defaultShaderInfoTexARGB8() { }
	// RVA: 0x695b910 VA: 0x7598f73910
	internal static Boolean get_vertexTexturingIsAvailable() { }
	// RVA: 0x695878c VA: 0x7598f7078c
	internal static Boolean get_shaderModelIs35() { }
	// RVA: 0x695e1ec VA: 0x7598f761ec
	private Void InitVertexDeclaration() { }
	// RVA: 0x695e454 VA: 0x7598f76454
	private Void CompleteCreation() { }
	// RVA: 0x695e61c VA: 0x7598f7661c
	private Boolean get_fullyCreated() { }
	// RVA: 0x695e62c VA: 0x7598f7662c
	protected Boolean get_disposed() { }
	// RVA: 0x695e634 VA: 0x7598f76634
	private Void set_disposed(Boolean value) { }
	// RVA: 0x695e640 VA: 0x7598f76640
	public Void Dispose() { }
	// RVA: 0x695e6ac VA: 0x7598f766ac
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x695ec38 VA: 0x7598f76c38
	public MeshHandle Allocate(UInt32 vertexCount, UInt32 indexCount, out NativeSlice`1 vertexData, out NativeSlice`1 indexData, out UInt16 indexOffset) { }
	// RVA: 0x695f40c VA: 0x7598f7740c
	public Void Update(MeshHandle mesh, UInt32 vertexCount, out NativeSlice`1 vertexData) { }
	// RVA: 0x695fd74 VA: 0x7598f77d74
	public Void Update(MeshHandle mesh, UInt32 vertexCount, UInt32 indexCount, out NativeSlice`1 vertexData, out NativeSlice`1 indexData, out UInt16 indexOffset) { }
	// RVA: 0x695ff0c VA: 0x7598f77f0c
	private Void UpdateCopyBackIndices(MeshHandle mesh, Boolean copyBackIndices) { }
	// RVA: 0x6960028 VA: 0x7598f78028
	internal List`1 ActiveUpdatesForMeshHandle(MeshHandle mesh) { }
	// RVA: 0x696009c VA: 0x7598f7809c
	private Boolean TryAllocFromPage(Page page, UInt32 vertexCount, UInt32 indexCount, ref Alloc va, ref Alloc ia, Boolean shortLived) { }
	// RVA: 0x695ecf8 VA: 0x7598f76cf8
	private Void Allocate(MeshHandle meshHandle, UInt32 vertexCount, UInt32 indexCount, out NativeSlice`1 vertexData, out NativeSlice`1 indexData, Boolean shortLived) { }
	// RVA: 0x695f5d4 VA: 0x7598f775d4
	private Void UpdateAfterGPUUsedData(MeshHandle mesh, UInt32 vertexCount, UInt32 indexCount, out NativeSlice`1 vertexData, out NativeSlice`1 indexData, out UInt16 indexOffset, out AllocToUpdate allocToUpdate, Boolean copyBackIndices) { }
	// RVA: 0x6960520 VA: 0x7598f78520
	public Void Free(MeshHandle mesh) { }
	// RVA: 0x6960db4 VA: 0x7598f78db4
	private static Vector4 GetClipSpaceParams() { }
	// RVA: 0x6960e7c VA: 0x7598f78e7c
	public Void OnFrameRenderingBegin() { }
	// RVA: 0x VA: 0x0
	private static NativeSlice`1 PtrToSlice(Void* p, Int32 count) { }
	// RVA: 0x6961a08 VA: 0x7598f79a08
	private Void ApplyDrawCommandState(RenderChainCommand cmd, Int32 textureSlot, Material newMat, Boolean newMatDiffers, Boolean newFontDiffers, ref EvaluationState st) { }
	// RVA: 0x6961c44 VA: 0x7598f79c44
	private Void ApplyBatchState(ref EvaluationState st, Boolean allowMaterialChange) { }
	// RVA: 0x6961dc4 VA: 0x7598f79dc4
	public Void EvaluateChain(RenderChainCommand head, Material initialMat, Material defaultMat, Texture gradientSettings, Texture shaderInfo, Single pixelsPerPoint, NativeSlice`1 transforms, NativeSlice`1 clipRects, MaterialPropertyBlock stateMatProps, Boolean allowMaterialChange, ref Exception immediateException) { }
	// RVA: 0x6964110 VA: 0x7598f7c110
	private Void UpdateFenceValue() { }
	// RVA: 0x69631ac VA: 0x7598f7b1ac
	private Void KickRanges(DrawBufferRange* ranges, ref Int32 rangesReady, ref Int32 rangesStart, Int32 rangesCount, Page curPage) { }
	// RVA: 0x VA: 0x0
	private Void DrawRanges(GPUBuffer`1 ib, GPUBuffer`1 vb, NativeSlice`1 ranges) { }
	// RVA: 0x69641dc VA: 0x7598f7c1dc
	private Void WaitOnCpuFence(UInt32 fence) { }
	// RVA: 0x6960f80 VA: 0x7598f78f80
	public Void AdvanceFrame() { }
	// RVA: 0x69642b0 VA: 0x7598f7c2b0
	private Void PruneUnusedPages() { }
	// RVA: 0x696444c VA: 0x7598f7c44c
	internal static Void PrepareForGfxDeviceRecreate() { }
	// RVA: 0x69645f4 VA: 0x7598f7c5f4
	internal static Void WrapUpGfxDeviceRecreate() { }
	// RVA: 0x6964654 VA: 0x7598f7c654
	internal static Void FlushAllPendingDeviceDisposes() { }
	// RVA: 0x69646cc VA: 0x7598f7c6cc
	internal DrawStatistics GatherDrawStatistics() { }
	// RVA: 0x695e850 VA: 0x7598f76850
	private static Void ProcessDeviceFreeQueue() { }
	// RVA: 0x69646e4 VA: 0x7598f7c6e4
	private static Void OnEngineUpdateGlobal() { }
	// RVA: 0x6964730 VA: 0x7598f7c730
	private static Void OnFlushPendingResources() { }
}
```
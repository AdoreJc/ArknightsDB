# Utility

**Namespace:** `UnityEngine.UIElements.UIR`


## Dump
```C#
// Dll : UnityEngine.UIElementsNativeModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class Utility
{
	private static Action`1 GraphicsResourcesRecreate; // 0x0
	private static Action EngineUpdate; // 0x8
	private static Action FlushPendingResources; // 0x10
	private static Action`1 RegisterIntermediateRenderers; // 0x18
	private static Action`1 RenderNodeAdd; // 0x20
	private static Action`1 RenderNodeExecute; // 0x28
	private static Action`1 RenderNodeCleanup; // 0x30
	private static ProfilerMarker s_MarkerRaiseEngineUpdate; // 0x38


	// RVA: 0x VA: 0x0
	public static Void SetVectorArray(MaterialPropertyBlock props, Int32 name, NativeSlice`1 vector4s) { }
	// RVA: 0x6a431dc VA: 0x759905b1dc
	public static Void add_GraphicsResourcesRecreate(Action`1 value) { }
	// RVA: 0x6a432cc VA: 0x759905b2cc
	public static Void remove_GraphicsResourcesRecreate(Action`1 value) { }
	// RVA: 0x6a433bc VA: 0x759905b3bc
	public static Void add_EngineUpdate(Action value) { }
	// RVA: 0x6a43498 VA: 0x759905b498
	public static Void remove_EngineUpdate(Action value) { }
	// RVA: 0x6a43574 VA: 0x759905b574
	public static Void add_FlushPendingResources(Action value) { }
	// RVA: 0x6a43650 VA: 0x759905b650
	public static Void remove_FlushPendingResources(Action value) { }
	// RVA: 0x6a4372c VA: 0x759905b72c
	public static Void add_RegisterIntermediateRenderers(Action`1 value) { }
	// RVA: 0x6a43820 VA: 0x759905b820
	public static Void remove_RegisterIntermediateRenderers(Action`1 value) { }
	// RVA: 0x6a43914 VA: 0x759905b914
	public static Void add_RenderNodeExecute(Action`1 value) { }
	// RVA: 0x6a43a08 VA: 0x759905ba08
	public static Void remove_RenderNodeExecute(Action`1 value) { }
	// RVA: 0x6a43afc VA: 0x759905bafc
	internal static Void RaiseGraphicsResourcesRecreate(Boolean recreate) { }
	// RVA: 0x6a43b78 VA: 0x759905bb78
	internal static Void RaiseEngineUpdate() { }
	// RVA: 0x6a43c34 VA: 0x759905bc34
	internal static Void RaiseFlushPendingResources() { }
	// RVA: 0x6a43ca8 VA: 0x759905bca8
	internal static Void RaiseRegisterIntermediateRenderers(Camera camera) { }
	// RVA: 0x6a43d24 VA: 0x759905bd24
	internal static Void RaiseRenderNodeAdd(IntPtr userData) { }
	// RVA: 0x6a43da0 VA: 0x759905bda0
	internal static Void RaiseRenderNodeExecute(IntPtr userData) { }
	// RVA: 0x6a43e1c VA: 0x759905be1c
	internal static Void RaiseRenderNodeCleanup(IntPtr userData) { }
	// RVA: 0x6a43e98 VA: 0x759905be98
	private static IntPtr AllocateBuffer(Int32 elementCount, Int32 elementStride, Boolean vertexBuffer) { }
	// RVA: 0x6a43eec VA: 0x759905beec
	private static Void FreeBuffer(IntPtr buffer) { }
	// RVA: 0x6a43f28 VA: 0x759905bf28
	private static Void UpdateBufferRanges(IntPtr buffer, IntPtr ranges, Int32 rangeCount, Int32 writeRangeStart, Int32 writeRangeEnd) { }
	// RVA: 0x6a43f94 VA: 0x759905bf94
	private static Void SetVectorArray(MaterialPropertyBlock props, Int32 name, IntPtr vector4s, Int32 count) { }
	// RVA: 0x6a43ff0 VA: 0x759905bff0
	public static IntPtr GetVertexDeclaration(VertexAttributeDescriptor[] vertexAttributes) { }
	// RVA: 0x6a4402c VA: 0x759905c02c
	public static Void RegisterIntermediateRenderer(Camera camera, Material material, Matrix4x4 transform, Bounds aabb, Int32 renderLayer, Int32 shadowCasting, Boolean receiveShadows, Int32 sameDistanceSortPriority, UInt64 sceneCullingMask, Int32 rendererCallbackFlags, IntPtr userData, Int32 userDataSize) { }
	// RVA: 0x6a441d8 VA: 0x759905c1d8
	public static Void DrawRanges(IntPtr ib, IntPtr* vertexStreams, Int32 streamCount, IntPtr ranges, Int32 rangeCount, IntPtr vertexDecl) { }
	// RVA: 0x6a4424c VA: 0x759905c24c
	public static Void SetPropertyBlock(MaterialPropertyBlock props) { }
	// RVA: 0x6a44288 VA: 0x759905c288
	public static Void SetScissorRect(RectInt scissorRect) { }
	// RVA: 0x6a44344 VA: 0x759905c344
	public static Void DisableScissor() { }
	// RVA: 0x6a4436c VA: 0x759905c36c
	public static IntPtr CreateStencilState(StencilState stencilState) { }
	// RVA: 0x6a4442c VA: 0x759905c42c
	public static Void SetStencilState(IntPtr stencilState, Int32 stencilRef) { }
	// RVA: 0x6a44470 VA: 0x759905c470
	public static Boolean HasMappedBufferRange() { }
	// RVA: 0x6a44498 VA: 0x759905c498
	public static UInt32 InsertCPUFence() { }
	// RVA: 0x6a444c0 VA: 0x759905c4c0
	public static Boolean CPUFencePassed(UInt32 fence) { }
	// RVA: 0x6a444fc VA: 0x759905c4fc
	public static Void WaitForCPUFencePassed(UInt32 fence) { }
	// RVA: 0x6a44538 VA: 0x759905c538
	public static Void SyncRenderThread() { }
	// RVA: 0x6a44560 VA: 0x759905c560
	public static RectInt GetActiveViewport() { }
	// RVA: 0x6a44620 VA: 0x759905c620
	public static Void ProfileDrawChainBegin() { }
	// RVA: 0x6a44648 VA: 0x759905c648
	public static Void ProfileDrawChainEnd() { }
	// RVA: 0x6a44670 VA: 0x759905c670
	public static Void NotifyOfUIREvents(Boolean subscribe) { }
	// RVA: 0x6a446ac VA: 0x759905c6ac
	public static Matrix4x4 GetUnityProjectionMatrix() { }
	// RVA: 0x6a44784 VA: 0x759905c784
	private static Void .cctor() { }
	// RVA: 0x6a44118 VA: 0x759905c118
	private static Void RegisterIntermediateRenderer_Injected(Camera camera, Material material, ref Matrix4x4 transform, ref Bounds aabb, Int32 renderLayer, Int32 shadowCasting, Boolean receiveShadows, Int32 sameDistanceSortPriority, UInt64 sceneCullingMask, Int32 rendererCallbackFlags, IntPtr userData, Int32 userDataSize) { }
	// RVA: 0x6a44308 VA: 0x759905c308
	private static Void SetScissorRect_Injected(ref RectInt scissorRect) { }
	// RVA: 0x6a443f0 VA: 0x759905c3f0
	private static IntPtr CreateStencilState_Injected(ref StencilState stencilState) { }
	// RVA: 0x6a445e4 VA: 0x759905c5e4
	private static Void GetActiveViewport_Injected(out RectInt ret) { }
	// RVA: 0x6a44748 VA: 0x759905c748
	private static Void GetUnityProjectionMatrix_Injected(out Matrix4x4 ret) { }
}
```
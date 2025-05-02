# CommandBuffer

**Namespace:** `UnityEngine.Rendering`


## Properties

- `String name`

- `Int32 sizeInBytes`


## Methods

- `Void Internal_SetSinglePassStereo(SinglePassStereoMode)`

- `Void ReleaseBuffer()`

- `Void SetComputeVectorParam(ComputeShader, Int32, Vector4)`

- `Void Internal_SetComputeFloats(ComputeShader, Int32, Single[])`

- `Void Internal_SetComputeTextureParam(ComputeShader, Int32, Int32, ref, Int32, RenderTextureSubElement)`

- `Void Internal_SetComputeBufferParam(ComputeShader, Int32, Int32, ComputeBuffer)`

- `Void Internal_DispatchCompute(ComputeShader, Int32, Int32, Int32, Int32)`

- `Void set_name(String)`

- `Int32 get_sizeInBytes()`

- `Void Clear()`

- `Void Internal_DrawMesh(Mesh, Matrix4x4, Material, Int32, Int32, MaterialPropertyBlock)`

- `Void Internal_DrawRenderer(Renderer, Material, Int32, Int32)`

- `Void SetViewport(Rect)`

- `Void CopyTexture_Internal(ref, Int32, Int32, Int32, Int32, Int32, Int32, ref, Int32, Int32, Int32, Int32, Int32)`

- `Void Blit_Texture(Texture, ref, Material, Int32, Vector2, Vector2, Int32, Int32)`

- `Void Blit_Identifier(ref, ref, Material, Int32, Vector2, Vector2, Int32, Int32)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, GraphicsFormat, Int32, Boolean, RenderTextureMemoryless, Boolean)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, GraphicsFormat, Int32, Boolean, RenderTextureMemoryless)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, GraphicsFormat, Int32)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, GraphicsFormat)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, RenderTextureFormat, RenderTextureReadWrite, Int32, Boolean, RenderTextureMemoryless, Boolean)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, RenderTextureFormat, RenderTextureReadWrite, Int32, Boolean, RenderTextureMemoryless)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, RenderTextureFormat, RenderTextureReadWrite, Int32, Boolean)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, RenderTextureFormat, RenderTextureReadWrite, Int32)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, RenderTextureFormat, RenderTextureReadWrite)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode, RenderTextureFormat)`

- `Void GetTemporaryRT(Int32, Int32, Int32, Int32, FilterMode)`

- `Void GetTemporaryRTWithDescriptor(Int32, RenderTextureDescriptor, FilterMode)`

- `Void GetTemporaryRT(Int32, RenderTextureDescriptor, FilterMode)`

- `Void ReleaseTemporaryRT(Int32)`

- `Void ClearRenderTarget(RTClearFlags, Color, Single, UInt32)`

- `Void ClearRenderTarget(Boolean, Boolean, Color)`

- `Void SetGlobalFloat(Int32, Single)`

- `Void SetGlobalVector(Int32, Vector4)`

- `Void EnableShaderKeyword(String)`

- `Void DisableShaderKeyword(String)`

- `Boolean ValidateAgainstExecutionFlags(CommandBufferExecutionFlags, CommandBufferExecutionFlags)`

- `Void SetGlobalTexture_Impl(Int32, ref, RenderTextureSubElement)`

- `Void BeginSample(String)`

- `Void EndSample(String)`

- `Void SetRenderTarget(RenderTargetIdentifier)`

- `Void SetRenderTarget(RenderTargetIdentifier, RenderBufferLoadAction, RenderBufferStoreAction)`

- `Void SetRenderTarget(RenderTargetIdentifier, Int32, CubemapFace, Int32)`

- `Void SetRenderTarget(RenderTargetIdentifier, RenderBufferLoadAction, RenderBufferStoreAction, RenderTargetIdentifier, RenderBufferLoadAction, RenderBufferStoreAction)`

- `Void SetRenderTarget(RenderTargetIdentifier[], RenderTargetIdentifier)`

- `Void SetRenderTargetSingle_Internal(RenderTargetIdentifier, RenderBufferLoadAction, RenderBufferStoreAction, RenderBufferLoadAction, RenderBufferStoreAction)`

- `Void SetRenderTargetColorDepth_Internal(RenderTargetIdentifier, RenderTargetIdentifier, RenderBufferLoadAction, RenderBufferStoreAction, RenderBufferLoadAction, RenderBufferStoreAction, RenderTargetFlags)`

- `Void SetRenderTargetMulti_Internal(RenderTargetIdentifier[], RenderTargetIdentifier, RenderBufferLoadAction[], RenderBufferStoreAction[], RenderBufferLoadAction, RenderBufferStoreAction, RenderTargetFlags)`

- `Void Dispose()`

- `Void Dispose(Boolean)`

- `Void SetComputeVectorParam(ComputeShader, String, Vector4)`

- `Void SetComputeFloatParams(ComputeShader, String, Single[])`

- `Void SetComputeTextureParam(ComputeShader, Int32, String, RenderTargetIdentifier)`

- `Void SetComputeBufferParam(ComputeShader, Int32, String, ComputeBuffer)`

- `Void DispatchCompute(ComputeShader, Int32, Int32, Int32, Int32)`

- `Void DrawMesh(Mesh, Matrix4x4, Material, Int32, Int32, MaterialPropertyBlock)`

- `Void DrawMesh(Mesh, Matrix4x4, Material, Int32, Int32)`

- `Void DrawRenderer(Renderer, Material, Int32, Int32)`

- `Void DrawRenderer(Renderer, Material, Int32)`

- `Void DrawRenderer(Renderer, Material)`

- `Void CopyTexture(RenderTargetIdentifier, RenderTargetIdentifier)`

- `Void CopyTexture(RenderTargetIdentifier, Int32, Int32, RenderTargetIdentifier, Int32, Int32)`

- `Void CopyTexture(RenderTargetIdentifier, Int32, Int32, Int32, Int32, Int32, Int32, RenderTargetIdentifier, Int32, Int32, Int32, Int32)`

- `Void Blit(Texture, RenderTargetIdentifier)`

- `Void Blit(Texture, RenderTargetIdentifier, Material, Int32)`

- `Void Blit(RenderTargetIdentifier, RenderTargetIdentifier)`

- `Void Blit(RenderTargetIdentifier, RenderTargetIdentifier, Material)`

- `Void Blit(RenderTargetIdentifier, RenderTargetIdentifier, Material, Int32)`

- `Void SetGlobalVector(String, Vector4)`

- `Void SetGlobalTexture(String, RenderTargetIdentifier)`

- `Void SetGlobalTexture(Int32, RenderTargetIdentifier)`

- `Void SetGlobalTexture(Int32, RenderTargetIdentifier, RenderTextureSubElement)`

- `Void SetSinglePassStereo(SinglePassStereoMode)`

- `Void SetComputeVectorParam_Injected(ComputeShader, Int32, ref)`

- `Void Internal_DrawMesh_Injected(Mesh, ref, Material, Int32, Int32, MaterialPropertyBlock)`

- `Void SetViewport_Injected(ref)`

- `Void Blit_Texture_Injected(Texture, ref, Material, Int32, ref, ref, Int32, Int32)`

- `Void Blit_Identifier_Injected(ref, ref, Material, Int32, ref, ref, Int32, Int32)`

- `Void GetTemporaryRTWithDescriptor_Injected(Int32, ref, FilterMode)`

- `Void ClearRenderTarget_Injected(RTClearFlags, ref, Single, UInt32)`

- `Void SetGlobalVector_Injected(Int32, ref)`

- `Void SetRenderTargetSingle_Internal_Injected(ref, RenderBufferLoadAction, RenderBufferStoreAction, RenderBufferLoadAction, RenderBufferStoreAction)`

- `Void SetRenderTargetColorDepth_Internal_Injected(ref, ref, RenderBufferLoadAction, RenderBufferStoreAction, RenderBufferLoadAction, RenderBufferStoreAction, RenderTargetFlags)`

- `Void SetRenderTargetMulti_Internal_Injected(RenderTargetIdentifier[], ref, RenderBufferLoadAction[], RenderBufferStoreAction[], RenderBufferLoadAction, RenderBufferStoreAction, RenderTargetFlags)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Rendering
public class CommandBuffer : IDisposable
{
	internal IntPtr m_Ptr; // 0x10

	public String name { set; }
	public Int32 sizeInBytes { get; }

	// RVA: 0x689d6ac VA: 0x7598eb56ac
	private Void Internal_SetSinglePassStereo(SinglePassStereoMode mode) { }
	// RVA: 0x689d6f0 VA: 0x7598eb56f0
	private static IntPtr InitBuffer() { }
	// RVA: 0x689d718 VA: 0x7598eb5718
	private Void ReleaseBuffer() { }
	// RVA: 0x689d754 VA: 0x7598eb5754
	public Void SetComputeVectorParam(ComputeShader computeShader, Int32 nameID, Vector4 val) { }
	// RVA: 0x689d81c VA: 0x7598eb581c
	private Void Internal_SetComputeFloats(ComputeShader computeShader, Int32 nameID, Single[] values) { }
	// RVA: 0x689d878 VA: 0x7598eb5878
	private Void Internal_SetComputeTextureParam(ComputeShader computeShader, Int32 kernelIndex, Int32 nameID, ref RenderTargetIdentifier rt, Int32 mipLevel, RenderTextureSubElement element) { }
	// RVA: 0x689d8fc VA: 0x7598eb58fc
	private Void Internal_SetComputeBufferParam(ComputeShader computeShader, Int32 kernelIndex, Int32 nameID, ComputeBuffer buffer) { }
	// RVA: 0x689d968 VA: 0x7598eb5968
	private Void Internal_DispatchCompute(ComputeShader computeShader, Int32 kernelIndex, Int32 threadGroupsX, Int32 threadGroupsY, Int32 threadGroupsZ) { }
	// RVA: 0x689d9dc VA: 0x7598eb59dc
	public Void set_name(String value) { }
	// RVA: 0x689da20 VA: 0x7598eb5a20
	public Int32 get_sizeInBytes() { }
	// RVA: 0x689da5c VA: 0x7598eb5a5c
	public Void Clear() { }
	// RVA: 0x689da98 VA: 0x7598eb5a98
	private Void Internal_DrawMesh(Mesh mesh, Matrix4x4 matrix, Material material, Int32 submeshIndex, Int32 shaderPass, MaterialPropertyBlock properties) { }
	// RVA: 0x689dba0 VA: 0x7598eb5ba0
	private Void Internal_DrawRenderer(Renderer renderer, Material material, Int32 submeshIndex, Int32 shaderPass) { }
	// RVA: 0x689dc0c VA: 0x7598eb5c0c
	public Void SetViewport(Rect pixelRect) { }
	// RVA: 0x689dca4 VA: 0x7598eb5ca4
	private Void CopyTexture_Internal(ref RenderTargetIdentifier src, Int32 srcElement, Int32 srcMip, Int32 srcX, Int32 srcY, Int32 srcWidth, Int32 srcHeight, ref RenderTargetIdentifier dst, Int32 dstElement, Int32 dstMip, Int32 dstX, Int32 dstY, Int32 mode) { }
	// RVA: 0x689dd6c VA: 0x7598eb5d6c
	private Void Blit_Texture(Texture source, ref RenderTargetIdentifier dest, Material mat, Int32 pass, Vector2 scale, Vector2 offset, Int32 sourceDepthSlice, Int32 destDepthSlice) { }
	// RVA: 0x689dea8 VA: 0x7598eb5ea8
	private Void Blit_Identifier(ref RenderTargetIdentifier source, ref RenderTargetIdentifier dest, Material mat, Int32 pass, Vector2 scale, Vector2 offset, Int32 sourceDepthSlice, Int32 destDepthSlice) { }
	// RVA: 0x689dfe4 VA: 0x7598eb5fe4
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, GraphicsFormat format, Int32 antiAliasing, Boolean enableRandomWrite, RenderTextureMemoryless memorylessMode, Boolean useDynamicScale) { }
	// RVA: 0x689e0a0 VA: 0x7598eb60a0
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, GraphicsFormat format, Int32 antiAliasing, Boolean enableRandomWrite, RenderTextureMemoryless memorylessMode) { }
	// RVA: 0x689e14c VA: 0x7598eb614c
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, GraphicsFormat format, Int32 antiAliasing) { }
	// RVA: 0x689e1f0 VA: 0x7598eb61f0
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, GraphicsFormat format) { }
	// RVA: 0x689e290 VA: 0x7598eb6290
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, RenderTextureFormat format, RenderTextureReadWrite readWrite, Int32 antiAliasing, Boolean enableRandomWrite, RenderTextureMemoryless memorylessMode, Boolean useDynamicScale) { }
	// RVA: 0x689e394 VA: 0x7598eb6394
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, RenderTextureFormat format, RenderTextureReadWrite readWrite, Int32 antiAliasing, Boolean enableRandomWrite, RenderTextureMemoryless memorylessMode) { }
	// RVA: 0x689e3cc VA: 0x7598eb63cc
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, RenderTextureFormat format, RenderTextureReadWrite readWrite, Int32 antiAliasing, Boolean enableRandomWrite) { }
	// RVA: 0x689e400 VA: 0x7598eb6400
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, RenderTextureFormat format, RenderTextureReadWrite readWrite, Int32 antiAliasing) { }
	// RVA: 0x689e42c VA: 0x7598eb642c
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, RenderTextureFormat format, RenderTextureReadWrite readWrite) { }
	// RVA: 0x689e458 VA: 0x7598eb6458
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter, RenderTextureFormat format) { }
	// RVA: 0x689e544 VA: 0x7598eb6544
	public Void GetTemporaryRT(Int32 nameID, Int32 width, Int32 height, Int32 depthBuffer, FilterMode filter) { }
	// RVA: 0x689e60c VA: 0x7598eb660c
	private Void GetTemporaryRTWithDescriptor(Int32 nameID, RenderTextureDescriptor desc, FilterMode filter) { }
	// RVA: 0x689e6c4 VA: 0x7598eb66c4
	public Void GetTemporaryRT(Int32 nameID, RenderTextureDescriptor desc, FilterMode filter) { }
	// RVA: 0x689e740 VA: 0x7598eb6740
	public Void ReleaseTemporaryRT(Int32 nameID) { }
	// RVA: 0x689e784 VA: 0x7598eb6784
	public Void ClearRenderTarget(RTClearFlags clearFlags, Color backgroundColor, Single depth, UInt32 stencil) { }
	// RVA: 0x689e86c VA: 0x7598eb686c
	public Void ClearRenderTarget(Boolean clearDepth, Boolean clearColor, Color backgroundColor) { }
	// RVA: 0x689e96c VA: 0x7598eb696c
	public Void SetGlobalFloat(Int32 nameID, Single value) { }
	// RVA: 0x689e9c0 VA: 0x7598eb69c0
	public Void SetGlobalVector(Int32 nameID, Vector4 value) { }
	// RVA: 0x689ea70 VA: 0x7598eb6a70
	public Void EnableShaderKeyword(String keyword) { }
	// RVA: 0x689eab4 VA: 0x7598eb6ab4
	public Void DisableShaderKeyword(String keyword) { }
	// RVA: 0x689e918 VA: 0x7598eb6918
	private Boolean ValidateAgainstExecutionFlags(CommandBufferExecutionFlags requiredFlags, CommandBufferExecutionFlags invalidFlags) { }
	// RVA: 0x689eaf8 VA: 0x7598eb6af8
	private Void SetGlobalTexture_Impl(Int32 nameID, ref RenderTargetIdentifier rt, RenderTextureSubElement element) { }
	// RVA: 0x689eb54 VA: 0x7598eb6b54
	public Void BeginSample(String name) { }
	// RVA: 0x689eb98 VA: 0x7598eb6b98
	public Void EndSample(String name) { }
	// RVA: 0x689ebdc VA: 0x7598eb6bdc
	public Void SetRenderTarget(RenderTargetIdentifier rt) { }
	// RVA: 0x689ecf0 VA: 0x7598eb6cf0
	public Void SetRenderTarget(RenderTargetIdentifier rt, RenderBufferLoadAction loadAction, RenderBufferStoreAction storeAction) { }
	// RVA: 0x689edf4 VA: 0x7598eb6df4
	public Void SetRenderTarget(RenderTargetIdentifier rt, Int32 mipLevel, CubemapFace cubemapFace, Int32 depthSlice) { }
	// RVA: 0x689ef6c VA: 0x7598eb6f6c
	public Void SetRenderTarget(RenderTargetIdentifier color, RenderBufferLoadAction colorLoadAction, RenderBufferStoreAction colorStoreAction, RenderTargetIdentifier depth, RenderBufferLoadAction depthLoadAction, RenderBufferStoreAction depthStoreAction) { }
	// RVA: 0x689f138 VA: 0x7598eb7138
	public Void SetRenderTarget(RenderTargetIdentifier[] colors, RenderTargetIdentifier depth) { }
	// RVA: 0x689ec7c VA: 0x7598eb6c7c
	private Void SetRenderTargetSingle_Internal(RenderTargetIdentifier rt, RenderBufferLoadAction colorLoadAction, RenderBufferStoreAction colorStoreAction, RenderBufferLoadAction depthLoadAction, RenderBufferStoreAction depthStoreAction) { }
	// RVA: 0x689f0ac VA: 0x7598eb70ac
	private Void SetRenderTargetColorDepth_Internal(RenderTargetIdentifier color, RenderTargetIdentifier depth, RenderBufferLoadAction colorLoadAction, RenderBufferStoreAction colorStoreAction, RenderBufferLoadAction depthLoadAction, RenderBufferStoreAction depthStoreAction, RenderTargetFlags flags) { }
	// RVA: 0x689f310 VA: 0x7598eb7310
	private Void SetRenderTargetMulti_Internal(RenderTargetIdentifier[] colors, RenderTargetIdentifier depth, RenderBufferLoadAction[] colorLoadActions, RenderBufferStoreAction[] colorStoreActions, RenderBufferLoadAction depthLoadAction, RenderBufferStoreAction depthStoreAction, RenderTargetFlags flags) { }
	// RVA: 0x689f528 VA: 0x7598eb7528
	protected override Void Finalize() { }
	// RVA: 0x689f638 VA: 0x7598eb7638
	public Void Dispose() { }
	// RVA: 0x689f5c0 VA: 0x7598eb75c0
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x689f69c VA: 0x7598eb769c
	public Void .ctor() { }
	// RVA: 0x689f6e4 VA: 0x7598eb76e4
	public Void SetComputeVectorParam(ComputeShader computeShader, String name, Vector4 val) { }
	// RVA: 0x689f748 VA: 0x7598eb7748
	public Void SetComputeFloatParams(ComputeShader computeShader, String name, Single[] values) { }
	// RVA: 0x689f7b0 VA: 0x7598eb77b0
	public Void SetComputeTextureParam(ComputeShader computeShader, Int32 kernelIndex, String name, RenderTargetIdentifier rt) { }
	// RVA: 0x689f830 VA: 0x7598eb7830
	public Void SetComputeBufferParam(ComputeShader computeShader, Int32 kernelIndex, String name, ComputeBuffer buffer) { }
	// RVA: 0x689f8a8 VA: 0x7598eb78a8
	public Void DispatchCompute(ComputeShader computeShader, Int32 kernelIndex, Int32 threadGroupsX, Int32 threadGroupsY, Int32 threadGroupsZ) { }
	// RVA: 0x689f91c VA: 0x7598eb791c
	public Void DrawMesh(Mesh mesh, Matrix4x4 matrix, Material material, Int32 submeshIndex, Int32 shaderPass, MaterialPropertyBlock properties) { }
	// RVA: 0x689fb98 VA: 0x7598eb7b98
	public Void DrawMesh(Mesh mesh, Matrix4x4 matrix, Material material, Int32 submeshIndex, Int32 shaderPass) { }
	// RVA: 0x689fbc8 VA: 0x7598eb7bc8
	public Void DrawRenderer(Renderer renderer, Material material, Int32 submeshIndex, Int32 shaderPass) { }
	// RVA: 0x689fdd4 VA: 0x7598eb7dd4
	public Void DrawRenderer(Renderer renderer, Material material, Int32 submeshIndex) { }
	// RVA: 0x689fddc VA: 0x7598eb7ddc
	public Void DrawRenderer(Renderer renderer, Material material) { }
	// RVA: 0x689fde8 VA: 0x7598eb7de8
	public Void CopyTexture(RenderTargetIdentifier src, RenderTargetIdentifier dst) { }
	// RVA: 0x689fe7c VA: 0x7598eb7e7c
	public Void CopyTexture(RenderTargetIdentifier src, Int32 srcElement, Int32 srcMip, RenderTargetIdentifier dst, Int32 dstElement, Int32 dstMip) { }
	// RVA: 0x689ff30 VA: 0x7598eb7f30
	public Void CopyTexture(RenderTargetIdentifier src, Int32 srcElement, Int32 srcMip, Int32 srcX, Int32 srcY, Int32 srcWidth, Int32 srcHeight, RenderTargetIdentifier dst, Int32 dstElement, Int32 dstMip, Int32 dstX, Int32 dstY) { }
	// RVA: 0x689fff4 VA: 0x7598eb7ff4
	public Void Blit(Texture source, RenderTargetIdentifier dest) { }
	// RVA: 0x68a0080 VA: 0x7598eb8080
	public Void Blit(Texture source, RenderTargetIdentifier dest, Material mat, Int32 pass) { }
	// RVA: 0x68a011c VA: 0x7598eb811c
	public Void Blit(RenderTargetIdentifier source, RenderTargetIdentifier dest) { }
	// RVA: 0x68a01a8 VA: 0x7598eb81a8
	public Void Blit(RenderTargetIdentifier source, RenderTargetIdentifier dest, Material mat) { }
	// RVA: 0x68a0238 VA: 0x7598eb8238
	public Void Blit(RenderTargetIdentifier source, RenderTargetIdentifier dest, Material mat, Int32 pass) { }
	// RVA: 0x68a02d4 VA: 0x7598eb82d4
	public Void SetGlobalVector(String name, Vector4 value) { }
	// RVA: 0x68a0328 VA: 0x7598eb8328
	public Void SetGlobalTexture(String name, RenderTargetIdentifier value) { }
	// RVA: 0x68a03fc VA: 0x7598eb83fc
	public Void SetGlobalTexture(Int32 nameID, RenderTargetIdentifier value) { }
	// RVA: 0x68a03a0 VA: 0x7598eb83a0
	public Void SetGlobalTexture(Int32 nameID, RenderTargetIdentifier value, RenderTextureSubElement element) { }
	// RVA: 0x68a0454 VA: 0x7598eb8454
	public Void SetSinglePassStereo(SinglePassStereoMode mode) { }
	// RVA: 0x689d7c0 VA: 0x7598eb57c0
	private Void SetComputeVectorParam_Injected(ComputeShader computeShader, Int32 nameID, ref Vector4 val) { }
	// RVA: 0x689db1c VA: 0x7598eb5b1c
	private Void Internal_DrawMesh_Injected(Mesh mesh, ref Matrix4x4 matrix, Material material, Int32 submeshIndex, Int32 shaderPass, MaterialPropertyBlock properties) { }
	// RVA: 0x689dc60 VA: 0x7598eb5c60
	private Void SetViewport_Injected(ref Rect pixelRect) { }
	// RVA: 0x689de0c VA: 0x7598eb5e0c
	private Void Blit_Texture_Injected(Texture source, ref RenderTargetIdentifier dest, Material mat, Int32 pass, ref Vector2 scale, ref Vector2 offset, Int32 sourceDepthSlice, Int32 destDepthSlice) { }
	// RVA: 0x689df48 VA: 0x7598eb5f48
	private Void Blit_Identifier_Injected(ref RenderTargetIdentifier source, ref RenderTargetIdentifier dest, Material mat, Int32 pass, ref Vector2 scale, ref Vector2 offset, Int32 sourceDepthSlice, Int32 destDepthSlice) { }
	// RVA: 0x689e668 VA: 0x7598eb6668
	private Void GetTemporaryRTWithDescriptor_Injected(Int32 nameID, ref RenderTextureDescriptor desc, FilterMode filter) { }
	// RVA: 0x689e800 VA: 0x7598eb6800
	private Void ClearRenderTarget_Injected(RTClearFlags clearFlags, ref Color backgroundColor, Single depth, UInt32 stencil) { }
	// RVA: 0x689ea1c VA: 0x7598eb6a1c
	private Void SetGlobalVector_Injected(Int32 nameID, ref Vector4 value) { }
	// RVA: 0x689f39c VA: 0x7598eb739c
	private Void SetRenderTargetSingle_Internal_Injected(ref RenderTargetIdentifier rt, RenderBufferLoadAction colorLoadAction, RenderBufferStoreAction colorStoreAction, RenderBufferLoadAction depthLoadAction, RenderBufferStoreAction depthStoreAction) { }
	// RVA: 0x689f410 VA: 0x7598eb7410
	private Void SetRenderTargetColorDepth_Internal_Injected(ref RenderTargetIdentifier color, ref RenderTargetIdentifier depth, RenderBufferLoadAction colorLoadAction, RenderBufferStoreAction colorStoreAction, RenderBufferLoadAction depthLoadAction, RenderBufferStoreAction depthStoreAction, RenderTargetFlags flags) { }
	// RVA: 0x689f49c VA: 0x7598eb749c
	private Void SetRenderTargetMulti_Internal_Injected(RenderTargetIdentifier[] colors, ref RenderTargetIdentifier depth, RenderBufferLoadAction[] colorLoadActions, RenderBufferStoreAction[] colorStoreActions, RenderBufferLoadAction depthLoadAction, RenderBufferStoreAction depthStoreAction, RenderTargetFlags flags) { }
}
```
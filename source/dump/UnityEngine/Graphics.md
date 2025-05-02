# Graphics

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Graphics
{
	internal static readonly Int32 kMaxDrawMeshInstanceCount; // 0x0
	internal static Dictionary`2 s_RenderInstancedDataLayouts; // 0x8

	public static GraphicsTier activeTier { set; }

	// RVA: 0x685db30 VA: 0x7598e75b30
	private static Int32 Internal_GetMaxDrawMeshInstanceCount() { }
	// RVA: 0x685db58 VA: 0x7598e75b58
	public static Void set_activeTier(GraphicsTier value) { }
	// RVA: 0x685db94 VA: 0x7598e75b94
	private static Void Internal_SetNullRT() { }
	// RVA: 0x685dbbc VA: 0x7598e75bbc
	private static Void Internal_SetRTSimple(RenderBuffer color, RenderBuffer depth, Int32 mip, CubemapFace face, Int32 depthSlice) { }
	// RVA: 0x685dcd0 VA: 0x7598e75cd0
	private static Void Internal_SetMRTSimple(RenderBuffer[] color, RenderBuffer depth, Int32 mip, CubemapFace face, Int32 depthSlice) { }
	// RVA: 0x685ddec VA: 0x7598e75dec
	private static Void Internal_SetRandomWriteTargetBuffer(Int32 index, ComputeBuffer uav, Boolean preserveCounterValue) { }
	// RVA: 0x685de40 VA: 0x7598e75e40
	public static Void ClearRandomWriteTargets() { }
	// RVA: 0x685de68 VA: 0x7598e75e68
	private static Void CopyTexture_Region(Texture src, Int32 srcElement, Int32 srcMip, Int32 srcX, Int32 srcY, Int32 srcWidth, Int32 srcHeight, Texture dst, Int32 dstElement, Int32 dstMip, Int32 dstX, Int32 dstY) { }
	// RVA: 0x685df28 VA: 0x7598e75f28
	private static Void Internal_DrawMeshNow2(Mesh mesh, Int32 subsetIndex, Matrix4x4 matrix) { }
	// RVA: 0x685e008 VA: 0x7598e76008
	internal static Void Internal_DrawTexture(ref Internal_DrawTextureArguments args) { }
	// RVA: 0x685e044 VA: 0x7598e76044
	private static Void Internal_DrawMesh(Mesh mesh, Int32 submeshIndex, Matrix4x4 matrix, Material material, Int32 layer, Camera camera, MaterialPropertyBlock properties, ShadowCastingMode castShadows, Boolean receiveShadows, Transform probeAnchor, LightProbeUsage lightProbeUsage, LightProbeProxyVolume lightProbeProxyVolume) { }
	// RVA: 0x685e1f4 VA: 0x7598e761f4
	private static Void Internal_DrawProceduralIndirectNow(MeshTopology topology, ComputeBuffer bufferWithArgs, Int32 argsOffset) { }
	// RVA: 0x685e248 VA: 0x7598e76248
	private static Void Internal_BlitMaterial5(Texture source, RenderTexture dest, Material mat, Int32 pass, Boolean setRT) { }
	// RVA: 0x685e2b4 VA: 0x7598e762b4
	private static Void Internal_BlitMultiTap4(Texture source, RenderTexture dest, Material mat, Vector2[] offsets) { }
	// RVA: 0x685e310 VA: 0x7598e76310
	private static Void Blit2(Texture source, RenderTexture dest) { }
	// RVA: 0x685e354 VA: 0x7598e76354
	public static Void ExecuteCommandBuffer(CommandBuffer buffer) { }
	// RVA: 0x685e390 VA: 0x7598e76390
	internal static Void SetRenderTargetImpl(RenderBuffer colorBuffer, RenderBuffer depthBuffer, Int32 mipLevel, CubemapFace face, Int32 depthSlice) { }
	// RVA: 0x685e42c VA: 0x7598e7642c
	internal static Void SetRenderTargetImpl(RenderTexture rt, Int32 mipLevel, CubemapFace face, Int32 depthSlice) { }
	// RVA: 0x685e558 VA: 0x7598e76558
	internal static Void SetRenderTargetImpl(RenderBuffer[] colorBuffers, RenderBuffer depthBuffer, Int32 mipLevel, CubemapFace face, Int32 depthSlice) { }
	// RVA: 0x685e5ec VA: 0x7598e765ec
	public static Void SetRenderTarget(RenderTexture rt, Int32 mipLevel, CubemapFace face, Int32 depthSlice) { }
	// RVA: 0x685e668 VA: 0x7598e76668
	public static Void SetRenderTarget(RenderBuffer[] colorBuffers, RenderBuffer depthBuffer) { }
	// RVA: 0x685e6e0 VA: 0x7598e766e0
	public static Void SetRandomWriteTarget(Int32 index, ComputeBuffer uav, Boolean preserveCounterValue) { }
	// RVA: 0x685e8c8 VA: 0x7598e768c8
	public static Void CopyTexture(Texture src, Int32 srcElement, Int32 srcMip, Int32 srcX, Int32 srcY, Int32 srcWidth, Int32 srcHeight, Texture dst, Int32 dstElement, Int32 dstMip, Int32 dstX, Int32 dstY) { }
	// RVA: 0x685e9b4 VA: 0x7598e769b4
	private static Void DrawTextureImpl(Rect screenRect, Texture texture, Rect sourceRect, Int32 leftBorder, Int32 rightBorder, Int32 topBorder, Int32 bottomBorder, Color color, Material mat, Int32 pass) { }
	// RVA: 0x685eb50 VA: 0x7598e76b50
	public static Void DrawTexture(Rect screenRect, Texture texture, Rect sourceRect, Int32 leftBorder, Int32 rightBorder, Int32 topBorder, Int32 bottomBorder, Color color, Material mat, Int32 pass) { }
	// RVA: 0x685eca4 VA: 0x7598e76ca4
	public static Void DrawTexture(Rect screenRect, Texture texture, Rect sourceRect, Int32 leftBorder, Int32 rightBorder, Int32 topBorder, Int32 bottomBorder, Material mat, Int32 pass) { }
	// RVA: 0x685edbc VA: 0x7598e76dbc
	public static Void DrawMeshNow(Mesh mesh, Matrix4x4 matrix, Int32 materialIndex) { }
	// RVA: 0x685eee0 VA: 0x7598e76ee0
	public static Void DrawMeshNow(Mesh mesh, Matrix4x4 matrix) { }
	// RVA: 0x685ef7c VA: 0x7598e76f7c
	public static Void DrawMesh(Mesh mesh, Matrix4x4 matrix, Material material, Int32 layer, Camera camera, Int32 submeshIndex, MaterialPropertyBlock properties, ShadowCastingMode castShadows, Boolean receiveShadows, Transform probeAnchor, LightProbeUsage lightProbeUsage, LightProbeProxyVolume lightProbeProxyVolume) { }
	// RVA: 0x685f120 VA: 0x7598e77120
	public static Void DrawProceduralIndirectNow(MeshTopology topology, ComputeBuffer bufferWithArgs, Int32 argsOffset) { }
	// RVA: 0x685f1fc VA: 0x7598e771fc
	public static Void Blit(Texture source, RenderTexture dest) { }
	// RVA: 0x685f280 VA: 0x7598e77280
	public static Void Blit(Texture source, RenderTexture dest, Material mat, Int32 pass) { }
	// RVA: 0x685f320 VA: 0x7598e77320
	public static Void Blit(Texture source, RenderTexture dest, Material mat) { }
	// RVA: 0x685f390 VA: 0x7598e77390
	public static Void BlitMultiTap(Texture source, RenderTexture dest, Material mat, Vector2[] offsets) { }
	// RVA: 0x685f494 VA: 0x7598e77494
	public static Void DrawMesh(Mesh mesh, Matrix4x4 matrix, Material material, Int32 layer) { }
	// RVA: 0x685f568 VA: 0x7598e77568
	public static Void DrawTexture(Rect screenRect, Texture texture, Rect sourceRect, Int32 leftBorder, Int32 rightBorder, Int32 topBorder, Int32 bottomBorder, Color color, Material mat) { }
	// RVA: 0x685f6b8 VA: 0x7598e776b8
	public static Void DrawTexture(Rect screenRect, Texture texture, Rect sourceRect, Int32 leftBorder, Int32 rightBorder, Int32 topBorder, Int32 bottomBorder) { }
	// RVA: 0x685f7a4 VA: 0x7598e777a4
	public static Void SetRenderTarget(RenderTexture rt) { }
	// RVA: 0x685f804 VA: 0x7598e77804
	public static Void SetRandomWriteTarget(Int32 index, ComputeBuffer uav) { }
	// RVA: 0x685f86c VA: 0x7598e7786c
	private static Void .cctor() { }
	// RVA: 0x685dc64 VA: 0x7598e75c64
	private static Void Internal_SetRTSimple_Injected(ref RenderBuffer color, ref RenderBuffer depth, Int32 mip, CubemapFace face, Int32 depthSlice) { }
	// RVA: 0x685dd80 VA: 0x7598e75d80
	private static Void Internal_SetMRTSimple_Injected(RenderBuffer[] color, ref RenderBuffer depth, Int32 mip, CubemapFace face, Int32 depthSlice) { }
	// RVA: 0x685dfb4 VA: 0x7598e75fb4
	private static Void Internal_DrawMeshNow2_Injected(Mesh mesh, Int32 subsetIndex, ref Matrix4x4 matrix) { }
	// RVA: 0x685e134 VA: 0x7598e76134
	private static Void Internal_DrawMesh_Injected(Mesh mesh, Int32 submeshIndex, ref Matrix4x4 matrix, Material material, Int32 layer, Camera camera, MaterialPropertyBlock properties, ShadowCastingMode castShadows, Boolean receiveShadows, Transform probeAnchor, LightProbeUsage lightProbeUsage, LightProbeProxyVolume lightProbeProxyVolume) { }
}
```
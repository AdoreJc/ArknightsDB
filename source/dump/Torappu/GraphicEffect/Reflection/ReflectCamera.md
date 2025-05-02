# ReflectCamera

**Namespace:** `Torappu.GraphicEffect.Reflection`


## Fields

- `Camera temp_mainCamera`

- `Vector3 temp_normal`

- `MeshRenderer temp_boundObj`

- `MeshRenderer temp_plane`

- `RenderTexture temp_rt`

- `ReflectIdx temp_reflectIdx`

- `Single temp_reflectFadeHeight`

- `HGReflectionShaderProfile m_shaderProfile`

- `ReflectCameraHolder m_holder`

- `CropMode _cropMode`

- `CommandBuffer m_opaqueCB`

- `CommandBuffer m_transparentCB`

- `MeshRenderer m_boundObj`

- `MeshRenderer m_planeRenderer`

- `Single m_planeParamDistance`

- `Vector3 m_planeParamNormal`

- `Vector4 m_shaderPlaneVector`

- `Vector3 m_reflectBoundsCenter`

- `Single m_reflectFadeHeight`

- `Material m_planeMat`

- `Material m_planeReflectMat`

- `RenderTexture m_reflectionRT`

- `Int32 m_reflectionRTWdith`

- `Int32 m_reflectionRTHeight`

- `Camera m_mainCamera`

- `CachedReflectMaterial m_cachedReflectMat`

- `ReflectCropManager m_reflectCropManager`

- `Boolean m_commandBufferInUse`

- `Boolean m_needRefresh`


## Properties

- `Boolean ready`

- `ReflectCameraHolder holder`

- `Boolean CropSuccess`

- `Boolean UseCrop`


## Methods

- `Boolean get_ready()`

- `ReflectCameraHolder get_holder()`

- `Boolean get_CropSuccess()`

- `Boolean get_UseCrop()`

- `Void Initialize(HGReflectionShaderProfile)`

- `Void SetHolder(ReflectCameraHolder)`

- `Void CreateRenderTarget(Int32, Int32)`

- `Void SetBounds(MeshRenderer)`

- `Void RegisterReflectIdx()`

- `Void SetPlane(Vector3, MeshRenderer)`

- `Void SetCamera(Camera)`

- `Void SetReflectFadeHeight(Single)`

- `Void BuildShaderMapping(HGReflectionShaderProfile)`

- `Void ReleaseShaderMapping()`

- `Void ApplyReflectRT()`

- `Camera GetCamera()`

- `Void RegisterReflectObject(MeshRenderer)`

- `Void UnregisterReflectObject(MeshRenderer)`

- `Void CleanupReflectObject()`

- `Void CalculateCachedParams()`

- `Void RefreshOpaqueCommandBuffer()`

- `Void RefreshTransparentCommandBuffer()`

- `Void CreateCommandBuffer()`

- `Void RemoveCommandBuffer()`

- `Void DisableReflection()`

- `Void EnableReflection()`

- `Void AddCommandBufferSoft()`

- `Void RemoveCommandBufferSoft()`

- `Void Awake()`

- `Void EnableCamera(Boolean)`

- `Void _ReleaseActiveCamera()`

- `Void _EnableCandidateCamera()`

- `Void RefreshCamera()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void CleanUp()`

- `Void LateUpdate()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.GraphicEffect.Reflection
public class ReflectCamera : MonoBehaviour, IHotfixable
{
	public Camera temp_mainCamera; // 0x18
	public Vector3 temp_normal; // 0x20
	public MeshRenderer temp_boundObj; // 0x30
	public MeshRenderer temp_plane; // 0x38
	public RenderTexture temp_rt; // 0x40
	public List`1 temp_reflectObjs; // 0x48
	public ReflectIdx temp_reflectIdx; // 0x50
	public Single temp_reflectFadeHeight; // 0x54
	private HGReflectionShaderProfile m_shaderProfile; // 0x58
	private ReflectCameraHolder m_holder; // 0x60
	public CropMode _cropMode; // 0x68
	private CommandBuffer m_opaqueCB; // 0x70
	private CommandBuffer m_transparentCB; // 0x78
	private MeshRenderer m_boundObj; // 0x80
	private MeshRenderer m_planeRenderer; // 0x88
	private Single m_planeParamDistance; // 0x90
	private Vector3 m_planeParamNormal; // 0x94
	private Vector4 m_shaderPlaneVector; // 0xa0
	private Vector3 m_reflectBoundsCenter; // 0xb0
	private Single m_reflectFadeHeight; // 0xbc
	private Material m_planeMat; // 0xc0
	private Material m_planeReflectMat; // 0xc8
	private RenderTexture m_reflectionRT; // 0xd0
	private Int32 m_reflectionRTWdith; // 0xd8
	private Int32 m_reflectionRTHeight; // 0xdc
	private Camera m_mainCamera; // 0xe0
	private List`1 m_OpaqueRenderers; // 0xe8
	private List`1 m_transparentRenderers; // 0xf0
	private CachedReflectMaterial m_cachedReflectMat; // 0xf8
	private static Boolean s_initializeShaderMapping; // 0x0
	private static Int32 s_resRefCount; // 0x4
	private static Dictionary`2 s_renderReplaceMapping; // 0x8
	private static ReflectIdx s_reflectUVCropState; // 0x10
	private static ListDict`2 s_activeCameras; // 0x18
	private static HashSet`1 s_candidateCameras; // 0x20
	private ReflectCropManager m_reflectCropManager; // 0x100
	private static readonly Single BOUNDS_PROTECT_MARGIN; // 0x28
	private static readonly Single UV_MARGIN_LOW; // 0x2c
	private static readonly Single UV_MARGIN_HIGH; // 0x30
	private static readonly Single UV_LENGTH; // 0x34
	private static readonly Vector2 DEFAULT_RT_SIZE; // 0x38
	private static readonly Int32 PROP_HG_PLANE_PARAM; // 0x40
	private static readonly Int32 PROP_HG_CROP_UV; // 0x44
	private static readonly Int32 PROP_HG_MAIN_CAMERA_VP; // 0x48
	private static readonly Int32 PROP_HG_FADE_HEIGHT; // 0x4c
	private static readonly Int32 PROP_HG_REFLECT_TEX; // 0x50
	private static readonly String KEYWORD_HG_CROPUV_SURFACE; // 0x58
	private Boolean m_commandBufferInUse; // 0x108
	private Boolean m_needRefresh; // 0x109
	private static DelegateBridge __Hotfix0_get_ready; // 0x60
	private static DelegateBridge __Hotfix0_get_holder; // 0x68
	private static DelegateBridge __Hotfix0_get_CropSuccess; // 0x70
	private static DelegateBridge __Hotfix0_get_UseCrop; // 0x78
	private static DelegateBridge __Hotfix0_Initialize; // 0x80
	private static DelegateBridge __Hotfix0_SetHolder; // 0x88
	private static DelegateBridge __Hotfix0_CreateRenderTarget; // 0x90
	private static DelegateBridge __Hotfix0_SetBounds; // 0x98
	private static DelegateBridge __Hotfix0_RegisterReflectIdx; // 0xa0
	private static DelegateBridge __Hotfix0_SetPlane; // 0xa8
	private static DelegateBridge __Hotfix0_SetCamera; // 0xb0
	private static DelegateBridge __Hotfix0_SetReflectFadeHeight; // 0xb8
	private static DelegateBridge __Hotfix0_BuildShaderMapping; // 0xc0
	private static DelegateBridge __Hotfix0_ReleaseShaderMapping; // 0xc8
	private static DelegateBridge __Hotfix0_ApplyReflectRT; // 0xd0
	private static DelegateBridge __Hotfix0_GetCamera; // 0xd8
	private static DelegateBridge __Hotfix0_RegisterReflectObject; // 0xe0
	private static DelegateBridge __Hotfix0_UnregisterReflectObject; // 0xe8
	private static DelegateBridge __Hotfix0_CleanupReflectObject; // 0xf0
	private static DelegateBridge __Hotfix0_CalculateCachedParams; // 0xf8
	private static DelegateBridge __Hotfix0_RefreshOpaqueCommandBuffer; // 0x100
	private static DelegateBridge __Hotfix0_RefreshTransparentCommandBuffer; // 0x108
	private static DelegateBridge __Hotfix0_CreateCommandBuffer; // 0x110
	private static DelegateBridge __Hotfix0_RemoveCommandBuffer; // 0x118
	private static DelegateBridge __Hotfix0_DisableReflection; // 0x120
	private static DelegateBridge __Hotfix0_EnableReflection; // 0x128
	private static DelegateBridge __Hotfix0_AddCommandBufferSoft; // 0x130
	private static DelegateBridge __Hotfix0_RemoveCommandBufferSoft; // 0x138
	private static DelegateBridge __Hotfix0_Awake; // 0x140
	private static DelegateBridge __Hotfix0_EnableCamera; // 0x148
	private static DelegateBridge __Hotfix0__ReleaseActiveCamera; // 0x150
	private static DelegateBridge __Hotfix0__EnableCandidateCamera; // 0x158
	private static DelegateBridge __Hotfix0_RefreshCamera; // 0x160
	private static DelegateBridge __Hotfix0_OnEnable; // 0x168
	private static DelegateBridge __Hotfix0_OnDisable; // 0x170
	private static DelegateBridge __Hotfix0_CleanUp; // 0x178
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x180
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x188
	private static DelegateBridge __Hotfix0_GetReflectMat; // 0x190
	private static DelegateBridge _c__Hotfix0_ctor; // 0x198

	private Boolean ready { get; }
	public ReflectCameraHolder holder { get; }
	public Boolean CropSuccess { get; }
	private Boolean UseCrop { get; }

	// RVA: 0x35bbd9c VA: 0x7595bd3d9c
	private Boolean get_ready() { }
	// RVA: 0x35bbed4 VA: 0x7595bd3ed4
	public ReflectCameraHolder get_holder() { }
	// RVA: 0x35bbf4c VA: 0x7595bd3f4c
	public Boolean get_CropSuccess() { }
	// RVA: 0x35bbfe8 VA: 0x7595bd3fe8
	private Boolean get_UseCrop() { }
	// RVA: 0x35bc0ac VA: 0x7595bd40ac
	public Void Initialize(HGReflectionShaderProfile shaderProfile) { }
	// RVA: 0x35bc360 VA: 0x7595bd4360
	public Void SetHolder(ReflectCameraHolder holder) { }
	// RVA: 0x35bc3f4 VA: 0x7595bd43f4
	public Void CreateRenderTarget(Int32 width, Int32 height) { }
	// RVA: 0x35bc66c VA: 0x7595bd466c
	public Void SetBounds(MeshRenderer bounds) { }
	// RVA: 0x35bc700 VA: 0x7595bd4700
	public Void RegisterReflectIdx() { }
	// RVA: 0x35bcae8 VA: 0x7595bd4ae8
	public Void SetPlane(Vector3 upDir, MeshRenderer planeRenderer) { }
	// RVA: 0x35bcd6c VA: 0x7595bd4d6c
	public Void SetCamera(Camera camera) { }
	// RVA: 0x35bcfb4 VA: 0x7595bd4fb4
	public Void SetReflectFadeHeight(Single reflectFadeHeight) { }
	// RVA: 0x35bc13c VA: 0x7595bd413c
	private Void BuildShaderMapping(HGReflectionShaderProfile shaderProfile) { }
	// RVA: 0x35bd040 VA: 0x7595bd5040
	private Void ReleaseShaderMapping() { }
	// RVA: 0x35bc520 VA: 0x7595bd4520
	private Void ApplyReflectRT() { }
	// RVA: 0x35bd100 VA: 0x7595bd5100
	public Camera GetCamera() { }
	// RVA: 0x35bd178 VA: 0x7595bd5178
	public Void RegisterReflectObject(MeshRenderer renderer) { }
	// RVA: 0x35bd734 VA: 0x7595bd5734
	public Void UnregisterReflectObject(MeshRenderer renderer) { }
	// RVA: 0x35bdc04 VA: 0x7595bd5c04
	public Void CleanupReflectObject() { }
	// RVA: 0x35bdde4 VA: 0x7595bd5de4
	private Void CalculateCachedParams() { }
	// RVA: 0x35be108 VA: 0x7595bd6108
	private Void RefreshOpaqueCommandBuffer() { }
	// RVA: 0x35be67c VA: 0x7595bd667c
	private Void RefreshTransparentCommandBuffer() { }
	// RVA: 0x35bea18 VA: 0x7595bd6a18
	private Void CreateCommandBuffer() { }
	// RVA: 0x35bce7c VA: 0x7595bd4e7c
	private Void RemoveCommandBuffer() { }
	// RVA: 0x35beb50 VA: 0x7595bd6b50
	public Void DisableReflection() { }
	// RVA: 0x35bec3c VA: 0x7595bd6c3c
	public Void EnableReflection() { }
	// RVA: 0x35bed28 VA: 0x7595bd6d28
	public Void AddCommandBufferSoft() { }
	// RVA: 0x35bee28 VA: 0x7595bd6e28
	public Void RemoveCommandBufferSoft() { }
	// RVA: 0x35beedc VA: 0x7595bd6edc
	private Void Awake() { }
	// RVA: 0x35bef7c VA: 0x7595bd6f7c
	public Void EnableCamera(Boolean forceActive) { }
	// RVA: 0x35bf08c VA: 0x7595bd708c
	private Void _ReleaseActiveCamera() { }
	// RVA: 0x35bf234 VA: 0x7595bd7234
	private Void _EnableCandidateCamera() { }
	// RVA: 0x35bf438 VA: 0x7595bd7438
	public Void RefreshCamera() { }
	// RVA: 0x35bf4b4 VA: 0x7595bd74b4
	private Void OnEnable() { }
	// RVA: 0x35bf53c VA: 0x7595bd753c
	private Void OnDisable() { }
	// RVA: 0x35bf678 VA: 0x7595bd7678
	public Void CleanUp() { }
	// RVA: 0x35bf74c VA: 0x7595bd774c
	private Void LateUpdate() { }
	// RVA: 0x35c0304 VA: 0x7595bd8304
	private Void OnDestroy() { }
	// RVA: 0x35bdfb0 VA: 0x7595bd5fb0
	private static Matrix4x4 GetReflectMat(Vector3 normDir, Single distance) { }
	// RVA: 0x35c0564 VA: 0x7595bd8564
	public Void .ctor() { }
	// RVA: 0x35c0874 VA: 0x7595bd8874
	private static Void .cctor() { }
}
```
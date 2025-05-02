# HGSceneWaterEffect

**Namespace:** `Torappu.Rendering`


## Fields

- `WaterEffectProfile _waterProfile`

- `Shader _depthShader`

- `Boolean _gradingEffectStrict`

- `Animation _waterAnimationTrap`

- `Transform _waterSurfaceTransform`

- `Camera m_camera`

- `Camera m_reflCamera`

- `CommandBuffer m_depthCB`

- `Material m_depthMat`

- `RenderTexture m_depthRT`

- `RenderTexture m_reflRT`

- `CommandBuffer m_distortCB`

- `Boolean m_initializeSuccess`

- `Boolean m_cameraCommandBufferActive`

- `Int32 m_refCntDelay`

- `Int32 m_refCntDown`

- `Vector3 m_oldPos`


## Properties

- `Boolean ReflEnabled`

- `Boolean DepthEnabled`

- `Boolean IntersectEnable`

- `Boolean DistortEnabled`

- `Boolean GradingSimple`

- `Int32 DepthDownScaler`

- `Int32 ReflectionDownScaler`

- `Animator WaterAnimator`


## Methods

- `Boolean get_ReflEnabled()`

- `Boolean get_DepthEnabled()`

- `Boolean get_IntersectEnable()`

- `Boolean get_DistortEnabled()`

- `Boolean get_GradingSimple()`

- `Int32 get_DepthDownScaler()`

- `Int32 get_ReflectionDownScaler()`

- `Animator get_WaterAnimator()`

- `Void Awake()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`

- `Void Update()`

- `Void _InitializeWater()`

- `RenderTextureFormat _GetDepthRTFormat()`

- `Void _AddWaterCommandBuffer()`

- `Void _RemoveWaterCommandBuffer()`

- `Void _InitReflection()`

- `Void _UpdateReflectCamera()`

- `Camera _CreateReflCamera(Camera)`

- `Void _CalculateReflectionMatrix(ref, Vector4)`

- `Vector4 _CameraSpacePlane(Camera, Vector3, Vector3, Single, Single)`

- `Void <>xLuaBaseProxy_OnCameraChanged(Camera, Camera)`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Animation <>xLuaBaseProxy_GetSceneWaterAnimator()`

- `Shader <>xLuaBaseProxy_GetReplaceSpineShader()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class HGSceneWaterEffect : BaseSceneEffect
{
	public WaterEffectProfile _waterProfile; // 0x18
	public Shader _depthShader; // 0x20
	private List`1 _underwaterOpaqueList; // 0x28
	private List`1 _reflObjectList; // 0x30
	private List`1 _waterMeshList; // 0x38
	private Boolean _gradingEffectStrict; // 0x40
	private Animation _waterAnimationTrap; // 0x48
	private Transform _waterSurfaceTransform; // 0x50
	private Camera m_camera; // 0x58
	private Camera m_reflCamera; // 0x60
	private CommandBuffer m_depthCB; // 0x68
	private Material m_depthMat; // 0x70
	private RenderTexture m_depthRT; // 0x78
	private RenderTexture m_reflRT; // 0x80
	private CommandBuffer m_distortCB; // 0x88
	private Boolean m_initializeSuccess; // 0x90
	private Boolean m_cameraCommandBufferActive; // 0x91
	private const String CB_NAME_DEPTH; // 0x0
	private const String RT_NAME_DEPTH; // 0x0
	private const String RT_NAME_REFL; // 0x0
	private Int32 m_refCntDelay; // 0x94
	private Int32 m_refCntDown; // 0x98
	private Vector3 m_oldPos; // 0x9c
	private static DelegateBridge __Hotfix0_get_ReflEnabled; // 0x0
	private static DelegateBridge __Hotfix0_get_DepthEnabled; // 0x8
	private static DelegateBridge __Hotfix0_get_IntersectEnable; // 0x10
	private static DelegateBridge __Hotfix0_get_DistortEnabled; // 0x18
	private static DelegateBridge __Hotfix0_get_GradingSimple; // 0x20
	private static DelegateBridge __Hotfix0_get_DepthDownScaler; // 0x28
	private static DelegateBridge __Hotfix0_get_ReflectionDownScaler; // 0x30
	private static DelegateBridge __Hotfix0_get_WaterAnimator; // 0x38
	private static DelegateBridge __Hotfix0_Awake; // 0x40
	private static DelegateBridge __Hotfix0_OnEnable; // 0x48
	private static DelegateBridge __Hotfix0_OnDisable; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge __Hotfix0_Update; // 0x60
	private static DelegateBridge __Hotfix0__InitializeWater; // 0x68
	private static DelegateBridge __Hotfix0__GetDepthRTFormat; // 0x70
	private static DelegateBridge __Hotfix0__AddWaterCommandBuffer; // 0x78
	private static DelegateBridge __Hotfix0__RemoveWaterCommandBuffer; // 0x80
	private static DelegateBridge __Hotfix0_OnCameraChanged; // 0x88
	private static DelegateBridge __Hotfix0_OnFinish; // 0x90
	private static DelegateBridge __Hotfix0_GetSceneWaterAnimator; // 0x98
	private static DelegateBridge __Hotfix0_GetReplaceSpineShader; // 0xa0
	private static DelegateBridge __Hotfix0__InitReflection; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateReflectCamera; // 0xb0
	private static DelegateBridge __Hotfix0__CreateReflCamera; // 0xb8
	private static DelegateBridge __Hotfix0__CalculateReflectionMatrix; // 0xc0
	private static DelegateBridge __Hotfix0__CameraSpacePlane; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	private Boolean ReflEnabled { get; }
	private Boolean DepthEnabled { get; }
	private Boolean IntersectEnable { get; }
	private Boolean DistortEnabled { get; }
	private Boolean GradingSimple { get; }
	private Int32 DepthDownScaler { get; }
	private Int32 ReflectionDownScaler { get; }
	private Animator WaterAnimator { get; }

	// RVA: 0x3f0aebc VA: 0x7596522ebc
	private Boolean get_ReflEnabled() { }
	// RVA: 0x3f0af7c VA: 0x7596522f7c
	private Boolean get_DepthEnabled() { }
	// RVA: 0x3f0b004 VA: 0x7596523004
	private Boolean get_IntersectEnable() { }
	// RVA: 0x3f0b118 VA: 0x7596523118
	private Boolean get_DistortEnabled() { }
	// RVA: 0x3f0b234 VA: 0x7596523234
	private Boolean get_GradingSimple() { }
	// RVA: 0x3f0b2cc VA: 0x75965232cc
	private Int32 get_DepthDownScaler() { }
	// RVA: 0x3f0b38c VA: 0x759652338c
	private Int32 get_ReflectionDownScaler() { }
	// RVA: 0x3f0b42c VA: 0x759652342c
	private Animator get_WaterAnimator() { }
	// RVA: 0x3f0b500 VA: 0x7596523500
	private Void Awake() { }
	// RVA: 0x3f0b66c VA: 0x759652366c
	private Void OnEnable() { }
	// RVA: 0x3f0c028 VA: 0x7596524028
	private Void OnDisable() { }
	// RVA: 0x3f0c2b8 VA: 0x75965242b8
	private Void OnDestroy() { }
	// RVA: 0x3f0c518 VA: 0x7596524518
	private Void Update() { }
	// RVA: 0x3f0b784 VA: 0x7596523784
	private Void _InitializeWater() { }
	// RVA: 0x3f0cb14 VA: 0x7596524b14
	private RenderTextureFormat _GetDepthRTFormat() { }
	// RVA: 0x3f0be6c VA: 0x7596523e6c
	private Void _AddWaterCommandBuffer() { }
	// RVA: 0x3f0c11c VA: 0x759652411c
	private Void _RemoveWaterCommandBuffer() { }
	// RVA: 0x3f0cf60 VA: 0x7596524f60
	public override Void OnCameraChanged(Camera old, Camera current) { }
	// RVA: 0x3f0d2a4 VA: 0x75965252a4
	public override Void OnFinish() { }
	// RVA: 0x3f0d3a0 VA: 0x75965253a0
	public override Animation GetSceneWaterAnimator() { }
	// RVA: 0x3f0d408 VA: 0x7596525408
	public override Shader GetReplaceSpineShader() { }
	// RVA: 0x3f0cb90 VA: 0x7596524b90
	private Void _InitReflection() { }
	// RVA: 0x3f0c654 VA: 0x7596524654
	private Void _UpdateReflectCamera() { }
	// RVA: 0x3f0d4c0 VA: 0x75965254c0
	private Camera _CreateReflCamera(Camera sceneCamera) { }
	// RVA: 0x3f0d8f8 VA: 0x75965258f8
	private Void _CalculateReflectionMatrix(ref Matrix4x4 reflectionMat, Vector4 plane) { }
	// RVA: 0x3f0da38 VA: 0x7596525a38
	private Vector4 _CameraSpacePlane(Camera cam, Vector3 pos, Vector3 normal, Single sideSign, Single clipPlaneOffset) { }
	// RVA: 0x3f0dc78 VA: 0x7596525c78
	public Void .ctor() { }
	// RVA: 0x3f0ddd8 VA: 0x7596525dd8
	private Void <>xLuaBaseProxy_OnCameraChanged(Camera P0, Camera P1) { }
	// RVA: 0x3f0dde0 VA: 0x7596525de0
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x3f0dde8 VA: 0x7596525de8
	private Animation <>xLuaBaseProxy_GetSceneWaterAnimator() { }
	// RVA: 0x3f0ddf0 VA: 0x7596525df0
	private Shader <>xLuaBaseProxy_GetReplaceSpineShader() { }
}
```
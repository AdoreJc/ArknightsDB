# SceneCustomReflection

**Namespace:** `Torappu.Rendering`


## Fields

- `GameObject reflectPlane`

- `RenderTexture reflectRT`

- `Shader replaceShader`

- `Material reflectMat`

- `Int32 downScale`

- `Single refPlaneOffset`

- `Int32 reflectRoughness`

- `Single reflectIntensity`

- `Boolean isUpdate`

- `Camera m_camera`

- `Camera m_reflCamera`

- `Vector3 m_oldPos`

- `Boolean m_inited`


## Methods

- `Void Start()`

- `Void Update()`

- `Void OnDestroy()`

- `Void OnDisable()`

- `Void OnEnable()`

- `Camera _CreateReflCamera(Camera)`

- `Void InitReflection()`

- `Void _UpdateReflectCamera()`

- `Void _CalculateReflectionMatrix(ref, Vector4)`

- `Vector4 _CameraSpacePlane(Camera, Vector3, Vector3, Single, Single)`

- `Void _InitCamera(Camera)`

- `Void _ClearCurrentCamera()`

- `Void <>xLuaBaseProxy_OnCameraChanged(Camera, Camera)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class SceneCustomReflection : BaseSceneEffect
{
	public GameObject reflectPlane; // 0x18
	private RenderTexture reflectRT; // 0x20
	public Shader replaceShader; // 0x28
	public Material reflectMat; // 0x30
	public Int32 downScale; // 0x38
	public Single refPlaneOffset; // 0x3c
	public Int32 reflectRoughness; // 0x40
	public Single reflectIntensity; // 0x44
	public Boolean isUpdate; // 0x48
	private Camera m_camera; // 0x50
	private Camera m_reflCamera; // 0x58
	private Vector3 m_oldPos; // 0x60
	private Boolean m_inited; // 0x6c
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_OnDisable; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0__CreateReflCamera; // 0x28
	private static DelegateBridge __Hotfix0_InitReflection; // 0x30
	private static DelegateBridge __Hotfix0__UpdateReflectCamera; // 0x38
	private static DelegateBridge __Hotfix0__CalculateReflectionMatrix; // 0x40
	private static DelegateBridge __Hotfix0__CameraSpacePlane; // 0x48
	private static DelegateBridge __Hotfix0_OnCameraChanged; // 0x50
	private static DelegateBridge __Hotfix0__InitCamera; // 0x58
	private static DelegateBridge __Hotfix0__ClearCurrentCamera; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x3f02920 VA: 0x759651a920
	private Void Start() { }
	// RVA: 0x3f0317c VA: 0x759651b17c
	private Void Update() { }
	// RVA: 0x3f03284 VA: 0x759651b284
	private Void OnDestroy() { }
	// RVA: 0x3f034d8 VA: 0x759651b4d8
	private Void OnDisable() { }
	// RVA: 0x3f035b0 VA: 0x759651b5b0
	private Void OnEnable() { }
	// RVA: 0x3f03688 VA: 0x759651b688
	private Camera _CreateReflCamera(Camera sceneCamera) { }
	// RVA: 0x3f02990 VA: 0x759651a990
	private Void InitReflection() { }
	// RVA: 0x3f02cdc VA: 0x759651acdc
	private Void _UpdateReflectCamera() { }
	// RVA: 0x3f03aec VA: 0x759651baec
	private Void _CalculateReflectionMatrix(ref Matrix4x4 reflectionMat, Vector4 plane) { }
	// RVA: 0x3f03c2c VA: 0x759651bc2c
	private Vector4 _CameraSpacePlane(Camera cam, Vector3 pos, Vector3 normal, Single sideSign, Single clipPlaneOffset) { }
	// RVA: 0x3f03e6c VA: 0x759651be6c
	public override Void OnCameraChanged(Camera old, Camera current) { }
	// RVA: 0x3f03f88 VA: 0x759651bf88
	private Void _InitCamera(Camera camera) { }
	// RVA: 0x3f03420 VA: 0x759651b420
	private Void _ClearCurrentCamera() { }
	// RVA: 0x3f0405c VA: 0x759651c05c
	public Void .ctor() { }
	// RVA: 0x3f04118 VA: 0x759651c118
	private Void <>xLuaBaseProxy_OnCameraChanged(Camera P0, Camera P1) { }
}
```
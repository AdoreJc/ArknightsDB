# Water

**Namespace:** `UnityStandardAssets.Water`


## Fields

- `WaterMode waterMode`

- `Boolean disablePixelLights`

- `Int32 textureSize`

- `Single clipPlaneOffset`

- `LayerMask reflectLayers`

- `LayerMask refractLayers`

- `RenderTexture m_ReflectionTexture`

- `RenderTexture m_RefractionTexture`

- `WaterMode m_HardwareWaterSupport`

- `Int32 m_OldReflectionTextureSize`

- `Int32 m_OldRefractionTextureSize`


## Methods

- `Void OnWillRenderObject()`

- `Void OnDisable()`

- `Void Update()`

- `Void UpdateCameraModes(Camera, Camera)`

- `Void CreateWaterObjects(Camera, out, out)`

- `WaterMode GetWaterMode()`

- `WaterMode FindHardwareWaterSupport()`

- `Vector4 CameraSpacePlane(Camera, Vector3, Vector3, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : UnityStandardAssets.Water
public class Water : MonoBehaviour
{
	public WaterMode waterMode; // 0x18
	public Boolean disablePixelLights; // 0x1c
	public Int32 textureSize; // 0x20
	public Single clipPlaneOffset; // 0x24
	public LayerMask reflectLayers; // 0x28
	public LayerMask refractLayers; // 0x2c
	private Dictionary`2 m_ReflectionCameras; // 0x30
	private Dictionary`2 m_RefractionCameras; // 0x38
	private RenderTexture m_ReflectionTexture; // 0x40
	private RenderTexture m_RefractionTexture; // 0x48
	private WaterMode m_HardwareWaterSupport; // 0x50
	private Int32 m_OldReflectionTextureSize; // 0x54
	private Int32 m_OldRefractionTextureSize; // 0x58
	private static Boolean s_InsideWater; // 0x0


	// RVA: 0x3dcf320 VA: 0x75963e7320
	public Void OnWillRenderObject() { }
	// RVA: 0x3dd0c54 VA: 0x75963e8c54
	private Void OnDisable() { }
	// RVA: 0x3dd0fbc VA: 0x75963e8fbc
	private Void Update() { }
	// RVA: 0x3dd07d4 VA: 0x75963e87d4
	private Void UpdateCameraModes(Camera src, Camera dest) { }
	// RVA: 0x3dcfe68 VA: 0x75963e7e68
	private Void CreateWaterObjects(Camera currentCamera, out Camera reflectionCamera, out Camera refractionCamera) { }
	// RVA: 0x3dcfe54 VA: 0x75963e7e54
	private WaterMode GetWaterMode() { }
	// RVA: 0x3dcfcf4 VA: 0x75963e7cf4
	private WaterMode FindHardwareWaterSupport() { }
	// RVA: 0x3dd0aa4 VA: 0x75963e8aa4
	private Vector4 CameraSpacePlane(Camera cam, Vector3 pos, Vector3 normal, Single sideSign) { }
	// RVA: 0x3dd0a10 VA: 0x75963e8a10
	private static Void CalculateReflectionMatrix(ref Matrix4x4 reflectionMat, Vector4 plane) { }
	// RVA: 0x3dd1268 VA: 0x75963e9268
	public Void .ctor() { }
}
```
# MirrorReflection

**Namespace:** ` `


## Fields

- `Boolean m_DisablePixelLights`

- `Int32 m_TextureSize`

- `Single m_ClipPlaneOffset`

- `LayerMask m_ReflectLayers`

- `Hashtable m_ReflectionCameras`

- `RenderTexture m_ReflectionTexture`

- `Int32 m_OldReflectionTextureSize`


## Methods

- `Void OnWillRenderObject()`

- `Void OnDisable()`

- `Void UpdateCameraModes(Camera, Camera)`

- `Void CreateMirrorObjects(Camera, out)`

- `Vector4 CameraSpacePlane(Camera, Vector3, Vector3, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MirrorReflection : MonoBehaviour
{
	public Boolean m_DisablePixelLights; // 0x18
	public Int32 m_TextureSize; // 0x1c
	public Single m_ClipPlaneOffset; // 0x20
	public LayerMask m_ReflectLayers; // 0x24
	private Hashtable m_ReflectionCameras; // 0x28
	private RenderTexture m_ReflectionTexture; // 0x30
	private Int32 m_OldReflectionTextureSize; // 0x38
	private static Boolean s_InsideRendering; // 0x0


	// RVA: 0x1b26ebc VA: 0x759413eebc
	public Void OnWillRenderObject() { }
	// RVA: 0x1b27e94 VA: 0x759413fe94
	private Void OnDisable() { }
	// RVA: 0x1b27964 VA: 0x759413f964
	private Void UpdateCameraModes(Camera src, Camera dest) { }
	// RVA: 0x1b27414 VA: 0x759413f414
	private Void CreateMirrorObjects(Camera currentCamera, out Camera reflectionCamera) { }
	// RVA: 0x1b28264 VA: 0x7594140264
	private static Single sgn(Single a) { }
	// RVA: 0x1b27ce4 VA: 0x759413fce4
	private Vector4 CameraSpacePlane(Camera cam, Vector3 pos, Vector3 normal, Single sideSign) { }
	// RVA: 0x1b27c50 VA: 0x759413fc50
	private static Void CalculateReflectionMatrix(ref Matrix4x4 reflectionMat, Vector4 plane) { }
	// RVA: 0x1b28284 VA: 0x7594140284
	public Void .ctor() { }
}
```
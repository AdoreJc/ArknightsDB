# SceneDepth

**Namespace:** `Torappu.Rendering`


## Fields

- `Camera m_camera`

- `Boolean m_inited`


## Methods

- `Void _InitCamera(Camera)`

- `Void _ClearCurrentCamera()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void <>xLuaBaseProxy_OnCameraChanged(Camera, Camera)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class SceneDepth : BaseSceneEffect
{
	private Camera m_camera; // 0x18
	private Boolean m_inited; // 0x20
	private static DelegateBridge __Hotfix0_OnCameraChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitCamera; // 0x8
	private static DelegateBridge __Hotfix0__ClearCurrentCamera; // 0x10
	private static DelegateBridge __Hotfix0_OnEnable; // 0x18
	private static DelegateBridge __Hotfix0_OnDisable; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3f0411c VA: 0x759651c11c
	public override Void OnCameraChanged(Camera old, Camera current) { }
	// RVA: 0x3f04308 VA: 0x759651c308
	private Void _InitCamera(Camera camera) { }
	// RVA: 0x3f04238 VA: 0x759651c238
	private Void _ClearCurrentCamera() { }
	// RVA: 0x3f043f4 VA: 0x759651c3f4
	private Void OnEnable() { }
	// RVA: 0x3f04458 VA: 0x759651c458
	private Void OnDisable() { }
	// RVA: 0x3f044c0 VA: 0x759651c4c0
	public Void .ctor() { }
	// RVA: 0x3f0452c VA: 0x759651c52c
	private Void <>xLuaBaseProxy_OnCameraChanged(Camera P0, Camera P1) { }
}
```
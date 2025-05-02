# ReflectCameraHolder

**Namespace:** `Torappu.GraphicEffect.Reflection`


## Fields

- `ReflectCamera m_camera`

- `Camera m_mainCamera`

- `HGReflectionShaderProfile m_shaderProfile`

- `Boolean m_forceActive`

- `Boolean m_enabledByFloorMat`

- `Single m_floorReflectFadeHeight`

- `MeshRenderer m_floorReflectBound`

- `MeshRenderer m_floorRenderer`


## Properties

- `Boolean holded`


## Methods

- `Boolean get_holded()`

- `Void HoldCamera(ReflectCamera, Boolean)`

- `ReflectCamera ReleaseCamera()`

- `Void RegisterReflectObject(MeshRenderer)`

- `Void UnregisterReflectObject(MeshRenderer)`

- `Void Setup(Camera, Renderer, MeshRenderer, Single)`

- `Void _ApplyReflect()`

- `Void SetFloorRenderer(Renderer)`

- `Void _ApplyReflectFloor()`

- `Boolean _CheckReflectable(Material)`

- `Void EnableCamera()`

- `Void RefreshCameraEnable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.GraphicEffect.Reflection
public class ReflectCameraHolder : IHotfixable
{
	protected ReflectCamera m_camera; // 0x10
	private Camera m_mainCamera; // 0x18
	private HGReflectionShaderProfile m_shaderProfile; // 0x20
	private Boolean m_forceActive; // 0x28
	private Boolean m_enabledByFloorMat; // 0x29
	private Single m_floorReflectFadeHeight; // 0x2c
	private MeshRenderer m_floorReflectBound; // 0x30
	private MeshRenderer m_floorRenderer; // 0x38
	private HashSet`1 m_renderers; // 0x40
	private static DelegateBridge __Hotfix0_get_holded; // 0x0
	private static DelegateBridge __Hotfix0_get_reflectEnable; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_HoldCamera; // 0x18
	private static DelegateBridge __Hotfix0_ReleaseCamera; // 0x20
	private static DelegateBridge __Hotfix0_RegisterReflectObject; // 0x28
	private static DelegateBridge __Hotfix0_UnregisterReflectObject; // 0x30
	private static DelegateBridge __Hotfix0_Setup; // 0x38
	private static DelegateBridge __Hotfix0__ApplyReflect; // 0x40
	private static DelegateBridge __Hotfix0_SetFloorRenderer; // 0x48
	private static DelegateBridge __Hotfix0__ApplyReflectFloor; // 0x50
	private static DelegateBridge __Hotfix0__CheckReflectable; // 0x58
	private static DelegateBridge __Hotfix0_EnableCamera; // 0x60
	private static DelegateBridge __Hotfix0_RefreshCameraEnable; // 0x68

	public Boolean holded { get; }
	public virtual Boolean reflectEnable { get; }

	// RVA: 0x35c0bec VA: 0x7595bd8bec
	public Boolean get_holded() { }
	// RVA: 0x35c0c84 VA: 0x7595bd8c84
	public virtual Boolean get_reflectEnable() { }
	// RVA: 0x35c0cec VA: 0x7595bd8cec
	public Void .ctor(HGReflectionShaderProfile shaderProfile) { }
	// RVA: 0x35c0dd4 VA: 0x7595bd8dd4
	public Void HoldCamera(ReflectCamera camera, Boolean forceActive) { }
	// RVA: 0x35c110c VA: 0x7595bd910c
	public ReflectCamera ReleaseCamera() { }
	// RVA: 0x35c11f4 VA: 0x7595bd91f4
	public Void RegisterReflectObject(MeshRenderer renderer) { }
	// RVA: 0x35c12ec VA: 0x7595bd92ec
	public Void UnregisterReflectObject(MeshRenderer renderer) { }
	// RVA: 0x35c13e4 VA: 0x7595bd93e4
	public Void Setup(Camera mainCamera, Renderer floorRenderer, MeshRenderer bound, Single floorReflectFadeHeight) { }
	// RVA: 0x35c0e70 VA: 0x7595bd8e70
	private Void _ApplyReflect() { }
	// RVA: 0x35c1784 VA: 0x7595bd9784
	public Void SetFloorRenderer(Renderer floorRenderer) { }
	// RVA: 0x35c1548 VA: 0x7595bd9548
	private Void _ApplyReflectFloor() { }
	// RVA: 0x35c189c VA: 0x7595bd989c
	private Boolean _CheckReflectable(Material mat) { }
	// RVA: 0x35bf3c4 VA: 0x7595bd73c4
	public Void EnableCamera() { }
	// RVA: 0x35c1678 VA: 0x7595bd9678
	protected Void RefreshCameraEnable() { }
}
```
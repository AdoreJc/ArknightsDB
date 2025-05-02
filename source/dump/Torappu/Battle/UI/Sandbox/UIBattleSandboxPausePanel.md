# UIBattleSandboxPausePanel

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `RectTransform _camView`

- `Color _tileLowLandColor`

- `Color _tileHighlandColor`

- `UIBattleSandboxMapView _mapView`

- `RectTransform _camViewOffset`

- `RectTransform _mapViewRoot`

- `SandboxCameraPlugin <cameraPlugin>k__BackingField`

- `UIBattleSandboxMapView m_mapView`

- `Vector2 m_constOffset`


## Properties

- `SandboxCameraPlugin cameraPlugin`


## Methods

- `SandboxCameraPlugin get_cameraPlugin()`

- `Void set_cameraPlugin(SandboxCameraPlugin)`

- `Void ProcessLevelData(LevelData)`

- `Void OnUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxPausePanel : MonoBehaviour, IHotfixable
{
	private RectTransform _camView; // 0x18
	private Color _tileLowLandColor; // 0x20
	private Color _tileHighlandColor; // 0x30
	public UIBattleSandboxMapView _mapView; // 0x40
	private RectTransform _camViewOffset; // 0x48
	private RectTransform _mapViewRoot; // 0x50
	private SandboxCameraPlugin <cameraPlugin>k__BackingField; // 0x58
	private UIBattleSandboxMapView m_mapView; // 0x60
	private Vector2 m_constOffset; // 0x68
	private static DelegateBridge __Hotfix0_get_cameraPlugin; // 0x0
	private static DelegateBridge __Hotfix0_set_cameraPlugin; // 0x8
	private static DelegateBridge __Hotfix0_ProcessLevelData; // 0x10
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private SandboxCameraPlugin cameraPlugin { get; set; }

	// RVA: 0x209c850 VA: 0x75946b4850
	private SandboxCameraPlugin get_cameraPlugin() { }
	// RVA: 0x209c8b8 VA: 0x75946b48b8
	private Void set_cameraPlugin(SandboxCameraPlugin value) { }
	// RVA: 0x209c93c VA: 0x75946b493c
	public Void ProcessLevelData(LevelData data) { }
	// RVA: 0x209caf4 VA: 0x75946b4af4
	public Void OnUpdate() { }
	// RVA: 0x209cd94 VA: 0x75946b4d94
	public Void .ctor() { }
}
```
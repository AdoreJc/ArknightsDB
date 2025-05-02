# MapGraphic

**Namespace:** `Torappu.Battle`


## Fields

- `MapSettings _mapSettings`

- `LightmapSettings _lightmapSettings`

- `EffectSettings _effectSettings`

- `Boolean m_isCameraConfigInited`

- `CameraConfig m_cameraConfig`


## Properties

- `MapSettings mapSettings`

- `LightmapSettings lightmapSettings`

- `EffectSettings effectSettings`


## Methods

- `MapSettings get_mapSettings()`

- `LightmapSettings get_lightmapSettings()`

- `EffectSettings get_effectSettings()`

- `CameraConfig GetCameraConfig()`

- `Boolean AttachToMap()`

- `Single GetTileHeight(HeightType)`

- `Vector3 GetCameraView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MapGraphic : MonoBehaviour, IHotfixable
{
	public const String KEY_CAMERA_FOCUS; // 0x0
	public const String KEY_CAMERA_OFFSET; // 0x0
	private MapSettings _mapSettings; // 0x18
	private LightmapSettings _lightmapSettings; // 0x20
	private EffectSettings _effectSettings; // 0x28
	private TileGraphic[] _graphics; // 0x30
	private Boolean m_isCameraConfigInited; // 0x38
	private CameraConfig m_cameraConfig; // 0x40
	private static DelegateBridge __Hotfix0_get_mapSettings; // 0x0
	private static DelegateBridge __Hotfix0_get_lightmapSettings; // 0x8
	private static DelegateBridge __Hotfix0_get_effectSettings; // 0x10
	private static DelegateBridge __Hotfix0_get_graphics; // 0x18
	private static DelegateBridge __Hotfix0_GetCameraConfig; // 0x20
	private static DelegateBridge __Hotfix0_AttachToMap; // 0x28
	private static DelegateBridge __Hotfix0_GetTileHeight; // 0x30
	private static DelegateBridge __Hotfix0_GetCameraView; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public MapSettings mapSettings { get; }
	public LightmapSettings lightmapSettings { get; }
	public EffectSettings effectSettings { get; }
	public TileGraphic[] graphics { get; }

	// RVA: 0x406ea38 VA: 0x7596686a38
	public MapSettings get_mapSettings() { }
	// RVA: 0x40792a8 VA: 0x75966912a8
	public LightmapSettings get_lightmapSettings() { }
	// RVA: 0x4079310 VA: 0x7596691310
	public EffectSettings get_effectSettings() { }
	// RVA: 0x40755a4 VA: 0x759668d5a4
	public TileGraphic[] get_graphics() { }
	// RVA: 0x406ebe8 VA: 0x7596686be8
	public CameraConfig GetCameraConfig() { }
	// RVA: 0x4072d74 VA: 0x759668ad74
	public Boolean AttachToMap() { }
	// RVA: 0x4073a48 VA: 0x759668ba48
	public Single GetTileHeight(HeightType heightType) { }
	// RVA: 0x4073bfc VA: 0x759668bbfc
	public Vector3 GetCameraView() { }
	// RVA: 0x4079378 VA: 0x7596691378
	public Void .ctor() { }
}
```
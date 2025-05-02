# StageZoneMapLoader

**Namespace:** `Torappu.UI.Stage`


## Methods

- `StageZoneMap LoadLegacyZoneMap(ZoneViewModel, Transform)`

- `StageMainZoneMap LoadZoneMap(ZoneViewModel, Transform)`

- `StageCustomZoneMap LoadCustomZoneMapPrefab(ZoneViewModel)`

- `MapType _LoadMap(ZoneViewModel, Transform)`

- `GameObject _LoadMapPrefab(ZoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneMapLoader : PageAssetPool`1
{
	private static DelegateBridge __Hotfix0_LoadLegacyZoneMap; // 0x0
	private static DelegateBridge __Hotfix0_LoadZoneMap; // 0x8
	private static DelegateBridge __Hotfix0_LoadCustomZoneMapPrefab; // 0x10
	private static DelegateBridge __Hotfix0__LoadMap; // 0x18
	private static DelegateBridge __Hotfix0__LoadMapPrefab; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2fafed4 VA: 0x75955c7ed4
	public StageZoneMap LoadLegacyZoneMap(ZoneViewModel viewModel, Transform parent) { }
	// RVA: 0x2fb00bc VA: 0x75955c80bc
	public StageMainZoneMap LoadZoneMap(ZoneViewModel viewModel, Transform parent) { }
	// RVA: 0x2fb0160 VA: 0x75955c8160
	public StageCustomZoneMap LoadCustomZoneMapPrefab(ZoneViewModel viewModel) { }
	// RVA: 0x VA: 0x0
	private MapType _LoadMap(ZoneViewModel viewModel, Transform parent) { }
	// RVA: 0x2fb02b4 VA: 0x75955c82b4
	private GameObject _LoadMapPrefab(ZoneViewModel viewModel) { }
	// RVA: 0x2fb03b0 VA: 0x75955c83b0
	public Void .ctor() { }
}
```
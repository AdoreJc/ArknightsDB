# HomeCharRotationViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Boolean showRotationList`

- `String appliedPresetInstId`

- `String displayPresetInstId`

- `String displaySkinId`

- `Int32 skinMaxNumInPreset`

- `Int32 enterSeqNum`

- `Boolean modifiedPreviewIllust`


## Properties

- `HomeCharRotationPresetItemModel displayPresetModel`


## Methods

- `HomeCharRotationPresetItemModel get_displayPresetModel()`

- `Void LoadData()`

- `Void RefreshData(String, SelectSkinStrategy)`

- `Void _SetDisplayPreset(String, SelectSkinStrategy)`

- `Void SetShowRotationList(Boolean)`

- `Void ChangePresetList(Int64)`

- `Void ChangeSkinList(Int64)`

- `Void SetSelectedSkinId(String)`

- `Void SetDisplaySkinId(String)`

- `HomeCharRotationPresetSkinItemViewModel GetSkinModel(String)`

- `Int32 GetSkinIndex(String)`

- `InputParams GenerateChangeSkinParams()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationViewModel : IHotfixable
{
	public ListDict`2 presets; // 0x10
	public Boolean showRotationList; // 0x18
	public String appliedPresetInstId; // 0x20
	public String displayPresetInstId; // 0x28
	public String displaySkinId; // 0x30
	public Int32 skinMaxNumInPreset; // 0x38
	public Int32 enterSeqNum; // 0x3c
	public Boolean modifiedPreviewIllust; // 0x40
	private static DelegateBridge __Hotfix0_get_displayPresetModel; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshData; // 0x10
	private static DelegateBridge __Hotfix0__SetDisplayPreset; // 0x18
	private static DelegateBridge __Hotfix0_SetShowRotationList; // 0x20
	private static DelegateBridge __Hotfix0_ChangePresetList; // 0x28
	private static DelegateBridge __Hotfix0_ChangeSkinList; // 0x30
	private static DelegateBridge __Hotfix0_SetSelectedSkinId; // 0x38
	private static DelegateBridge __Hotfix0_SetDisplaySkinId; // 0x40
	private static DelegateBridge __Hotfix0_GetSkinModel; // 0x48
	private static DelegateBridge __Hotfix0_GetSkinIndex; // 0x50
	private static DelegateBridge __Hotfix0_GenerateChangeSkinParams; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public HomeCharRotationPresetItemModel displayPresetModel { get; }

	// RVA: 0x280ca24 VA: 0x7594e24a24
	public HomeCharRotationPresetItemModel get_displayPresetModel() { }
	// RVA: 0x280caac VA: 0x7594e24aac
	public Void LoadData() { }
	// RVA: 0x280cba4 VA: 0x7594e24ba4
	public Void RefreshData(String selectPresetInstId, SelectSkinStrategy selectSkinStrategy) { }
	// RVA: 0x280cfcc VA: 0x7594e24fcc
	private Void _SetDisplayPreset(String instId, SelectSkinStrategy selectSkinStrategy) { }
	// RVA: 0x280d1c0 VA: 0x7594e251c0
	public Void SetShowRotationList(Boolean show) { }
	// RVA: 0x280d240 VA: 0x7594e25240
	public Void ChangePresetList(Int64 direction) { }
	// RVA: 0x280d3d4 VA: 0x7594e253d4
	public Void ChangeSkinList(Int64 direction) { }
	// RVA: 0x280d578 VA: 0x7594e25578
	public Void SetSelectedSkinId(String skinId) { }
	// RVA: 0x280d680 VA: 0x7594e25680
	public Void SetDisplaySkinId(String skinId) { }
	// RVA: 0x280d78c VA: 0x7594e2578c
	public HomeCharRotationPresetSkinItemViewModel GetSkinModel(String skinId) { }
	// RVA: 0x280d880 VA: 0x7594e25880
	public Int32 GetSkinIndex(String skinId) { }
	// RVA: 0x280d978 VA: 0x7594e25978
	public InputParams GenerateChangeSkinParams() { }
	// RVA: 0x280dcac VA: 0x7594e25cac
	public Void .ctor() { }
}
```
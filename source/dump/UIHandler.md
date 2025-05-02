# UIHandler

**Namespace:** ` `


## Fields

- `DIYPage m_closure`


## Methods

- `FurnitureMemento GetFurnitureMemento()`

- `DIYRoomModifierMemento GetModifierMemento()`

- `Int32 GetRoomIndex()`

- `FurnitureGenreConfig GetFurnGenre()`

- `UnequipModifierViewData GetUnequipModifierData()`

- `Sprite GetUnequipModifierSprite()`

- `Int32 GetRoomComfortLimit()`

- `Boolean TrySaveDIY()`

- `Void SetCameraStateCeilDirectly()`

- `Void SetCameraStateFloorDirectly()`

- `Void SetCameraStateWallDirectly()`

- `Void ResetCameraState()`

- `Params GetPresetPanelParams()`

- `Void TrySavePreset(Int32, Action`1)`

- `Void TrySavePreset(Int32, Texture2D, Action`1)`

- `Void TrySavePreset(Int32, String, Texture2D, Action`1)`

- `Void LoadPreset(Int32, IDIYPreset)`

- `Void ApplyThemePresetToRoom(String)`

- `Texture2D GetPresetViewTexture()`

- `Void ClearRoomHilightMark()`

- `IListener GetFurnitureListener()`

- `IListener GetModifierListener()`

- `Void AddDIYItemToRoom(IDIYItem)`

- `Void SelectSameDIYItem(IDIYItem)`

- `Void UnequipModifierFromRoom(DIYRoomPart)`

- `Void ResetAllChanges()`

- `Void ResetFurnitureCameraState()`

- `Void ClearAllFurnitures()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UIHandler : IHotfixable
{
	private DIYPage m_closure; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetFurnitureMemento; // 0x8
	private static DelegateBridge __Hotfix0_GetModifierMemento; // 0x10
	private static DelegateBridge __Hotfix0_GetRoomIndex; // 0x18
	private static DelegateBridge __Hotfix0_GetFurnGenre; // 0x20
	private static DelegateBridge __Hotfix0_GetUnequipModifierData; // 0x28
	private static DelegateBridge __Hotfix0_GetUnequipModifierSprite; // 0x30
	private static DelegateBridge __Hotfix0_GetRoomComfortLimit; // 0x38
	private static DelegateBridge __Hotfix0_TrySaveDIY; // 0x40
	private static DelegateBridge __Hotfix0_SetCameraStateCeilDirectly; // 0x48
	private static DelegateBridge __Hotfix0_SetCameraStateFloorDirectly; // 0x50
	private static DelegateBridge __Hotfix0_SetCameraStateWallDirectly; // 0x58
	private static DelegateBridge __Hotfix0_ResetCameraState; // 0x60
	private static DelegateBridge __Hotfix0_GetPresetPanelParams; // 0x68
	private static DelegateBridge __Hotfix0_TrySavePreset; // 0x70
	private static DelegateBridge __Hotfix1_TrySavePreset; // 0x78
	private static DelegateBridge __Hotfix2_TrySavePreset; // 0x80
	private static DelegateBridge __Hotfix0_LoadPreset; // 0x88
	private static DelegateBridge __Hotfix0_ApplyThemePresetToRoom; // 0x90
	private static DelegateBridge __Hotfix0_GetPresetViewTexture; // 0x98
	private static DelegateBridge __Hotfix0_ClearRoomHilightMark; // 0xa0
	private static DelegateBridge __Hotfix0_GetFurnitureListener; // 0xa8
	private static DelegateBridge __Hotfix0_GetModifierListener; // 0xb0
	private static DelegateBridge __Hotfix0_AddDIYItemToRoom; // 0xb8
	private static DelegateBridge __Hotfix0_SelectSameDIYItem; // 0xc0
	private static DelegateBridge __Hotfix0_UnequipModifierFromRoom; // 0xc8
	private static DelegateBridge __Hotfix0_ResetAllChanges; // 0xd0
	private static DelegateBridge __Hotfix0_ResetFurnitureCameraState; // 0xd8
	private static DelegateBridge __Hotfix0_ClearAllFurnitures; // 0xe0


	// RVA: 0x3d26e20 VA: 0x759633ee20
	public Void .ctor(DIYPage page) { }
	// RVA: 0x3d2bf5c VA: 0x7596343f5c
	public FurnitureMemento GetFurnitureMemento() { }
	// RVA: 0x3d2bfd0 VA: 0x7596343fd0
	public DIYRoomModifierMemento GetModifierMemento() { }
	// RVA: 0x3d2c044 VA: 0x7596344044
	public Int32 GetRoomIndex() { }
	// RVA: 0x3d2c0c0 VA: 0x75963440c0
	public FurnitureGenreConfig GetFurnGenre() { }
	// RVA: 0x3d2c134 VA: 0x7596344134
	public UnequipModifierViewData GetUnequipModifierData() { }
	// RVA: 0x3d2c1a8 VA: 0x75963441a8
	public Sprite GetUnequipModifierSprite() { }
	// RVA: 0x3d2c21c VA: 0x759634421c
	public Int32 GetRoomComfortLimit() { }
	// RVA: 0x3d2c28c VA: 0x759634428c
	public Boolean TrySaveDIY() { }
	// RVA: 0x3d2c2fc VA: 0x75963442fc
	public Void SetCameraStateCeilDirectly() { }
	// RVA: 0x3d2c374 VA: 0x7596344374
	public Void SetCameraStateFloorDirectly() { }
	// RVA: 0x3d2c3ec VA: 0x75963443ec
	public Void SetCameraStateWallDirectly() { }
	// RVA: 0x3d2c464 VA: 0x7596344464
	public Void ResetCameraState() { }
	// RVA: 0x3d2c4dc VA: 0x75963444dc
	public Params GetPresetPanelParams() { }
	// RVA: 0x3d2c5f0 VA: 0x75963445f0
	public Void TrySavePreset(Int32 index, Action`1 resHandler) { }
	// RVA: 0x3d2c684 VA: 0x7596344684
	public Void TrySavePreset(Int32 index, Texture2D tex, Action`1 resHandler) { }
	// RVA: 0x3d2c730 VA: 0x7596344730
	public Void TrySavePreset(Int32 index, String presetName, Texture2D tex, Action`1 resHandler) { }
	// RVA: 0x3d2c7e8 VA: 0x75963447e8
	public Void LoadPreset(Int32 index, IDIYPreset preset) { }
	// RVA: 0x3d2c87c VA: 0x759634487c
	public Void ApplyThemePresetToRoom(String themeId) { }
	// RVA: 0x3d2c904 VA: 0x7596344904
	public Texture2D GetPresetViewTexture() { }
	// RVA: 0x3d2c974 VA: 0x7596344974
	public Void ClearRoomHilightMark() { }
	// RVA: 0x3d2c9f0 VA: 0x75963449f0
	public IListener GetFurnitureListener() { }
	// RVA: 0x3d2ca64 VA: 0x7596344a64
	public IListener GetModifierListener() { }
	// RVA: 0x3d2cad8 VA: 0x7596344ad8
	public Void AddDIYItemToRoom(IDIYItem diyItem) { }
	// RVA: 0x3d2cb60 VA: 0x7596344b60
	public Void SelectSameDIYItem(IDIYItem diyItem) { }
	// RVA: 0x3d2cbe8 VA: 0x7596344be8
	public Void UnequipModifierFromRoom(DIYRoomPart roomPart) { }
	// RVA: 0x3d2cc70 VA: 0x7596344c70
	public Void ResetAllChanges() { }
	// RVA: 0x3d2cce0 VA: 0x7596344ce0
	public Void ResetFurnitureCameraState() { }
	// RVA: 0x3d2cd54 VA: 0x7596344d54
	public Void ClearAllFurnitures() { }
}
```
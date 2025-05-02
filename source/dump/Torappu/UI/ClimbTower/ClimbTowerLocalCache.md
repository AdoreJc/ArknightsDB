# ClimbTowerLocalCache

**Namespace:** `Torappu.UI.ClimbTower`


## Methods

- `Data _EnsureMemCacheData()`

- `Void _SaveData(Data)`

- `Boolean GetTrainTowerToastPlayed()`

- `Void SetTrainTowerToastPlayed()`

- `Void SaveCharEditCacheDict(Dictionary`2)`

- `Boolean GetGodCardChecked(String)`

- `Void SetGodCardChecked(String)`

- `Boolean LoadTowerSelectedModeCache(String)`

- `Void SaveTowerSelectedModeCache(String, Boolean)`

- `Boolean GetEntryFloatGodCardTabIsClose()`

- `Void SaveEntryFloatGodCardTabIsClose(Boolean)`

- `Boolean GetSeasonReplicatedTowerChecked(String)`

- `Void SaveSeasonReplicatedTowerChecked(String)`

- `Boolean GetTowerIsUseSweep(String, Boolean)`

- `Void SetTowerIsUseSweep(String, Boolean, Boolean)`

- `String _GeneSweepKey(String, Boolean)`

- `String _CurGameID()`

- `DataInGame _EnsureDataInGame()`

- `Void _ConfirmDataInGame(DataInGame, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLocalCache : Singleton`1
{
	private const String HARD_MODE; // 0x0
	private const String NORMAL_MODE; // 0x0
	private const String SWEEP_TOWER_ID_AND_HARD_MODE_KEY_FORMAT; // 0x0
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__SaveData; // 0x10
	private static DelegateBridge __Hotfix0_GetTrainTowerToastPlayed; // 0x18
	private static DelegateBridge __Hotfix0_SetTrainTowerToastPlayed; // 0x20
	private static DelegateBridge __Hotfix0_LoadCharEditCacheDict; // 0x28
	private static DelegateBridge __Hotfix0_SaveCharEditCacheDict; // 0x30
	private static DelegateBridge __Hotfix0_GetGodCardChecked; // 0x38
	private static DelegateBridge __Hotfix0_SetGodCardChecked; // 0x40
	private static DelegateBridge __Hotfix0_LoadTowerSelectedModeCache; // 0x48
	private static DelegateBridge __Hotfix0_SaveTowerSelectedModeCache; // 0x50
	private static DelegateBridge __Hotfix0_GetEntryFloatGodCardTabIsClose; // 0x58
	private static DelegateBridge __Hotfix0_SaveEntryFloatGodCardTabIsClose; // 0x60
	private static DelegateBridge __Hotfix0_GetSeasonReplicatedTowerChecked; // 0x68
	private static DelegateBridge __Hotfix0_SaveSeasonReplicatedTowerChecked; // 0x70
	private static DelegateBridge __Hotfix0_GetTowerIsUseSweep; // 0x78
	private static DelegateBridge __Hotfix0_SetTowerIsUseSweep; // 0x80
	private static DelegateBridge __Hotfix0__GeneSweepKey; // 0x88
	private static DelegateBridge __Hotfix0__CurGameID; // 0x90
	private static DelegateBridge __Hotfix0__EnsureDataInGame; // 0x98
	private static DelegateBridge __Hotfix0__ConfirmDataInGame; // 0xa0


	// RVA: 0x2c6f3c0 VA: 0x75952873c0
	private Void .ctor() { }
	// RVA: 0x2c6f450 VA: 0x7595287450
	private Data _EnsureMemCacheData() { }
	// RVA: 0x2c6f5b4 VA: 0x75952875b4
	private Void _SaveData(Data data) { }
	// RVA: 0x2c6bdf8 VA: 0x7595283df8
	public Boolean GetTrainTowerToastPlayed() { }
	// RVA: 0x2c6be74 VA: 0x7595283e74
	public Void SetTrainTowerToastPlayed() { }
	// RVA: 0x2c6f668 VA: 0x7595287668
	public Dictionary`2 LoadCharEditCacheDict() { }
	// RVA: 0x2c6f838 VA: 0x7595287838
	public Void SaveCharEditCacheDict(Dictionary`2 charEditCache) { }
	// RVA: 0x2c6f9f8 VA: 0x75952879f8
	public Boolean GetGodCardChecked(String cardId) { }
	// RVA: 0x2c6fad4 VA: 0x7595287ad4
	public Void SetGodCardChecked(String cardId) { }
	// RVA: 0x2c6fc64 VA: 0x7595287c64
	public Boolean LoadTowerSelectedModeCache(String towerId) { }
	// RVA: 0x2c61544 VA: 0x7595279544
	public Void SaveTowerSelectedModeCache(String towerId, Boolean isHardMode) { }
	// RVA: 0x2c6fd48 VA: 0x7595287d48
	public Boolean GetEntryFloatGodCardTabIsClose() { }
	// RVA: 0x2c6fdf0 VA: 0x7595287df0
	public Void SaveEntryFloatGodCardTabIsClose(Boolean isClose) { }
	// RVA: 0x2c6feb8 VA: 0x7595287eb8
	public Boolean GetSeasonReplicatedTowerChecked(String seasonId) { }
	// RVA: 0x2c6ffbc VA: 0x7595287fbc
	public Void SaveSeasonReplicatedTowerChecked(String seasonId) { }
	// RVA: 0x2c7012c VA: 0x759528812c
	public Boolean GetTowerIsUseSweep(String towerId, Boolean isHardMode) { }
	// RVA: 0x2c70310 VA: 0x7595288310
	public Void SetTowerIsUseSweep(String towerId, Boolean isHardMode, Boolean isUseSweep) { }
	// RVA: 0x2c7023c VA: 0x759528823c
	private String _GeneSweepKey(String towerId, Boolean isHardMode) { }
	// RVA: 0x2c704e8 VA: 0x75952884e8
	private String _CurGameID() { }
	// RVA: 0x2c6f728 VA: 0x7595287728
	private DataInGame _EnsureDataInGame() { }
	// RVA: 0x2c6f914 VA: 0x7595287914
	private Void _ConfirmDataInGame(DataInGame data, Boolean triggerSave) { }
}
```
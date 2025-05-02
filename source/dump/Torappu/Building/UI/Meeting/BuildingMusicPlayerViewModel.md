# BuildingMusicPlayerViewModel

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Boolean visitMode`

- `String currBgmId`

- `Boolean sortAscending`

- `String playingBgmId`

- `String playingBgmName`

- `String playingBgmDes`

- `Boolean playingBgmCanClick`

- `Boolean needRebuildList`

- `Int32 focusIdx`


## Methods

- `Void LoadData()`

- `Void LoadVisitModeData()`

- `Void UpdatePlayerData()`

- `Void RefreshMusicStatus()`

- `Void RegenerateList()`

- `Int32 _CompareByTime(BuildingMusicItemViewModel, BuildingMusicItemViewModel)`

- `Boolean _CheckHomeBGDisplay(MusicSingleData, Dictionary`2, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMusicPlayerViewModel : IHotfixable
{
	private const String MAIN_BG; // 0x0
	public Boolean visitMode; // 0x10
	public String currBgmId; // 0x18
	public Boolean sortAscending; // 0x20
	public String playingBgmId; // 0x28
	public String playingBgmName; // 0x30
	public String playingBgmDes; // 0x38
	public Boolean playingBgmCanClick; // 0x40
	public Boolean needRebuildList; // 0x41
	public Int32 focusIdx; // 0x44
	private List`1 m_musicModels; // 0x48
	private static DelegateBridge __Hotfix0_get_musicList; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_LoadVisitModeData; // 0x10
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x18
	private static DelegateBridge __Hotfix0_RefreshMusicStatus; // 0x20
	private static DelegateBridge __Hotfix0_RegenerateList; // 0x28
	private static DelegateBridge __Hotfix0__CompareByTime; // 0x30
	private static DelegateBridge __Hotfix0__CheckHomeBGDisplay; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public List`1 musicList { get; }

	// RVA: 0x3dec304 VA: 0x7596404304
	public List`1 get_musicList() { }
	// RVA: 0x3deb7e4 VA: 0x75964037e4
	public Void LoadData() { }
	// RVA: 0x3debce4 VA: 0x7596403ce4
	public Void LoadVisitModeData() { }
	// RVA: 0x3dec740 VA: 0x7596404740
	public Void UpdatePlayerData() { }
	// RVA: 0x3debf40 VA: 0x7596403f40
	public Void RefreshMusicStatus() { }
	// RVA: 0x3debe68 VA: 0x7596403e68
	public Void RegenerateList() { }
	// RVA: 0x3decc84 VA: 0x7596404c84
	private Int32 _CompareByTime(BuildingMusicItemViewModel x, BuildingMusicItemViewModel y) { }
	// RVA: 0x3dec36c VA: 0x759640436c
	private Boolean _CheckHomeBGDisplay(MusicSingleData musicData, Dictionary`2 limitDataList, Dictionary`2 homeBgList) { }
	// RVA: 0x3deb720 VA: 0x7596403720
	public Void .ctor() { }
}
```
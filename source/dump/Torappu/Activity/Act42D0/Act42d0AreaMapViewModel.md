# Act42d0AreaMapViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String actId`

- `Act42D0AreaDifficulty currentDiff`

- `String areaSelectedId`

- `Boolean hardUnlocked`

- `NewestProgress lastProgressInfo`


## Methods

- `Void LoadData(String, String, String)`

- `Void _InitSelection(String, String)`

- `Act42D0AreaDifficulty _FindUnlockHardestAreaDiff()`

- `Void RefreshPlayerData()`

- `Act42d0AreaViewModel GetAreaViewModel(String)`

- `Boolean AreaIdValid(String)`

- `Void ClearSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42d0AreaMapViewModel : IHotfixable
{
	public String actId; // 0x10
	public Act42D0AreaDifficulty currentDiff; // 0x18
	public Dictionary`2 areaViewModelDict; // 0x20
	public String areaSelectedId; // 0x28
	public Boolean hardUnlocked; // 0x30
	public NewestProgress lastProgressInfo; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__InitSelection; // 0x8
	private static DelegateBridge __Hotfix0__FindUnlockHardestAreaDiff; // 0x10
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x18
	private static DelegateBridge __Hotfix0_GetAreaViewModel; // 0x20
	private static DelegateBridge __Hotfix0_AreaIdValid; // 0x28
	private static DelegateBridge __Hotfix0_ClearSelect; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3218850 VA: 0x7595830850
	public Void LoadData(String activityId, String areaId, String stageId) { }
	// RVA: 0x3219560 VA: 0x7595831560
	private Void _InitSelection(String areaId, String stageId) { }
	// RVA: 0x3219790 VA: 0x7595831790
	private Act42D0AreaDifficulty _FindUnlockHardestAreaDiff() { }
	// RVA: 0x3219300 VA: 0x7595831300
	public Void RefreshPlayerData() { }
	// RVA: 0x32184ec VA: 0x75958304ec
	public Act42d0AreaViewModel GetAreaViewModel(String areaId) { }
	// RVA: 0x3219b3c VA: 0x7595831b3c
	public Boolean AreaIdValid(String areaId) { }
	// RVA: 0x3219bf8 VA: 0x7595831bf8
	public Void ClearSelect() { }
	// RVA: 0x3219d34 VA: 0x7595831d34
	public Void .ctor() { }
}
```
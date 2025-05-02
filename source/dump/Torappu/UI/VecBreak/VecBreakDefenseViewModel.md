# VecBreakDefenseViewModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `String activityId`

- `LastPage lastPage`

- `Boolean needFocus`

- `Int32 focusIndex`

- `String rightText`

- `String retreatText`

- `String retreatToastText`


## Methods

- `Void LoadData(String, LastPage, String)`

- `Void RefreshPlayerData()`

- `VecBreakDefenseStageViewModel GetStageModel(String)`

- `Int32 GetStageIndex(String)`

- `Int32 _GetLatestAvailStageIndex()`

- `Void _LoadFocusIndex(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseViewModel : IHotfixable
{
	public List`1 stageModels; // 0x10
	public String activityId; // 0x18
	public LastPage lastPage; // 0x20
	public Boolean needFocus; // 0x24
	public Int32 focusIndex; // 0x28
	public String rightText; // 0x30
	public String retreatText; // 0x38
	public String retreatToastText; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge __Hotfix0_GetStageModel; // 0x10
	private static DelegateBridge __Hotfix0_GetStageIndex; // 0x18
	private static DelegateBridge __Hotfix0__GetLatestAvailStageIndex; // 0x20
	private static DelegateBridge __Hotfix0__LoadFocusIndex; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x22cbcd0 VA: 0x75948e3cd0
	public Void LoadData(String actId, LastPage inputLastPage, String playedStageId) { }
	// RVA: 0x22cb9a0 VA: 0x75948e39a0
	public Void RefreshPlayerData() { }
	// RVA: 0x22cb4a4 VA: 0x75948e34a4
	public VecBreakDefenseStageViewModel GetStageModel(String stageId) { }
	// RVA: 0x22cc8d4 VA: 0x75948e48d4
	public Int32 GetStageIndex(String stageId) { }
	// RVA: 0x22cc9d0 VA: 0x75948e49d0
	private Int32 _GetLatestAvailStageIndex() { }
	// RVA: 0x22cc7cc VA: 0x75948e47cc
	private Void _LoadFocusIndex(String actId, String playedStageId) { }
	// RVA: 0x22ccb20 VA: 0x75948e4b20
	public Void .ctor() { }
}
```
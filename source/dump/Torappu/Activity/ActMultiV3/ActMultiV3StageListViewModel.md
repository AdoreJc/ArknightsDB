# ActMultiV3StageListViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String actId`

- `ViewMode viewMode`

- `ActMultiV3MapDiffType selectedDiffType`

- `String selectedStageId`

- `Int32 initSeqNum`

- `String stageTimeLockToast`


## Methods

- `Void LoadData(String, LoadParam)`

- `Void SetSelectedTab(Int32)`

- `ActMultiV3StageItemViewModel GetStageViewModel(String)`

- `Void GetCurrDiffStageIdList(List`1, ref)`

- `Void ReloadTrackpointStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListViewModel : IHotfixable
{
	public String actId; // 0x10
	public ViewMode viewMode; // 0x18
	public Dictionary`2 stageDiffGroups; // 0x20
	public Dictionary`2 stages; // 0x28
	public Dictionary`2 modeStarCount; // 0x30
	public ActMultiV3MapDiffType selectedDiffType; // 0x38
	public String selectedStageId; // 0x40
	public Int32 initSeqNum; // 0x48
	public String stageTimeLockToast; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedTab; // 0x8
	private static DelegateBridge __Hotfix0_GetStageViewModel; // 0x10
	private static DelegateBridge __Hotfix0_GetCurrDiffStageIdList; // 0x18
	private static DelegateBridge __Hotfix0_ReloadTrackpointStatus; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3151ccc VA: 0x7595769ccc
	public Void LoadData(String actId, LoadParam loadParam) { }
	// RVA: 0x314ed58 VA: 0x7595766d58
	public Void SetSelectedTab(Int32 diff) { }
	// RVA: 0x314ee04 VA: 0x7595766e04
	public ActMultiV3StageItemViewModel GetStageViewModel(String stageId) { }
	// RVA: 0x314e964 VA: 0x7595766964
	public Void GetCurrDiffStageIdList(List`1 stageList, ref Int32 normalStageCount) { }
	// RVA: 0x314dc7c VA: 0x7595765c7c
	public Void ReloadTrackpointStatus() { }
	// RVA: 0x315264c VA: 0x759576a64c
	public Void .ctor() { }
}
```
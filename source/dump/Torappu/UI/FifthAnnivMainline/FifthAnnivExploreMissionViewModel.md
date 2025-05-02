# FifthAnnivExploreMissionViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Boolean hasRewardToCollect`

- `Boolean m_isInited`


## Methods

- `Void LoadData()`

- `Int32 _MissionSortingCompare(MissionObjHolderViewModel, MissionObjHolderViewModel)`

- `Boolean CanCollect(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMissionViewModel : IHotfixable
{
	public Dictionary`2 missionModelDict; // 0x10
	public List`1 missionModelList; // 0x18
	public Boolean hasRewardToCollect; // 0x20
	public List`1 toCollectMissionIds; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__MissionSortingCompare; // 0x8
	private static DelegateBridge __Hotfix0__MissionSortingRefVal; // 0x10
	private static DelegateBridge __Hotfix0_GetAllToCollectMissionIds; // 0x18
	private static DelegateBridge __Hotfix0_CanCollect; // 0x20
	private static DelegateBridge __Hotfix0__GetFifthAnnivMainLineMissionData; // 0x28
	private static DelegateBridge __Hotfix0__GetFifthAnnivMainLinePlayerMissionData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x292b014 VA: 0x7594f43014
	public Void LoadData() { }
	// RVA: 0x292d230 VA: 0x7594f45230
	private Int32 _MissionSortingCompare(MissionObjHolderViewModel vm0, MissionObjHolderViewModel vm1) { }
	// RVA: 0x292d334 VA: 0x7594f45334
	private static Int32 _MissionSortingRefVal(MissionObjHolderViewModel vm) { }
	// RVA: 0x292bfc4 VA: 0x7594f43fc4
	public List`1 GetAllToCollectMissionIds() { }
	// RVA: 0x292bc34 VA: 0x7594f43c34
	public Boolean CanCollect(String missionId) { }
	// RVA: 0x292d0e8 VA: 0x7594f450e8
	private static Dictionary`2 _GetFifthAnnivMainLineMissionData() { }
	// RVA: 0x292d178 VA: 0x7594f45178
	private static Dictionary`2 _GetFifthAnnivMainLinePlayerMissionData() { }
	// RVA: 0x292d3e0 VA: 0x7594f453e0
	public Void .ctor() { }
}
```
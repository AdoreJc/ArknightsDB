# ClimbTowerSquadGroupViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Boolean isFromRecord`


## Properties

- `Int32 currentAssitCount`

- `Int32 editableMemCount`

- `EvolvePhaseAndLevel maxEvolvePhaseAndLevel`


## Methods

- `Int32 get_currentAssitCount()`

- `Int32 get_editableMemCount()`

- `EvolvePhaseAndLevel get_maxEvolvePhaseAndLevel()`

- `Int32 GetTotalMemCount()`

- `Void GetAssistDataList(List`1)`

- `Int32 GetProfessionCount(ProfessionCategory)`

- `Int32 _GetRealAssistIdx(Int32)`

- `Void LoadDataFromClimbTower(PlayerTower)`

- `Void _LoadSquadFromPlayerData(PlayerTower, out)`

- `ClimbTowerFriendAssistModel GetAssistModelByIndex(Int32)`

- `Boolean TryGetInstInSquad(Int32, out)`

- `Void ShrinkAssistList()`

- `Boolean CheckIfContainedInAssistList(String, Int32)`

- `Boolean IsFull()`

- `Int32 GetAvailAssistIndex()`

- `Boolean TryGetMutuallyExclusiveCharInfoInAssist(Int32, String, out)`

- `Void CheckAndClearMutuallyExclusiveChar(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadGroupViewModel : SquadGroupViewModel
{
	private ClimbTowerFriendAssistModel[] m_assistList; // 0x40
	public Boolean isFromRecord; // 0x48
	private static DelegateBridge __Hotfix0_get_currentAssitCount; // 0x0
	private static DelegateBridge __Hotfix0_get_editableMemCount; // 0x8
	private static DelegateBridge __Hotfix0_get_selfMembers; // 0x10
	private static DelegateBridge __Hotfix0_get_maxEvolvePhaseAndLevel; // 0x18
	private static DelegateBridge __Hotfix0_GetTotalMemCount; // 0x20
	private static DelegateBridge __Hotfix0_GetAssistDataList; // 0x28
	private static DelegateBridge __Hotfix0_GetProfessionCount; // 0x30
	private static DelegateBridge __Hotfix0__GetRealAssistIdx; // 0x38
	private static DelegateBridge __Hotfix0_LoadDataFromClimbTower; // 0x40
	private static DelegateBridge __Hotfix0__LoadSquadFromPlayerData; // 0x48
	private static DelegateBridge __Hotfix0_GetAssistModelByIndex; // 0x50
	private static DelegateBridge __Hotfix0_TryGetInstInSquad; // 0x58
	private static DelegateBridge __Hotfix0_ShrinkAssistList; // 0x60
	private static DelegateBridge __Hotfix0_CheckIfContainedInAssistList; // 0x68
	private static DelegateBridge __Hotfix0_IsFull; // 0x70
	private static DelegateBridge __Hotfix0_GetAvailAssistIndex; // 0x78
	private static DelegateBridge __Hotfix0_TryGetMutuallyExclusiveCharInfoInAssist; // 0x80
	private static DelegateBridge __Hotfix0_CheckAndClearMutuallyExclusiveChar; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Int32 currentAssitCount { get; }
	public Int32 editableMemCount { get; }
	public SquadItemStruct[] selfMembers { get; }
	public EvolvePhaseAndLevel maxEvolvePhaseAndLevel { get; }

	// RVA: 0x2cb638c VA: 0x75952ce38c
	public Int32 get_currentAssitCount() { }
	// RVA: 0x2cb64fc VA: 0x75952ce4fc
	public Int32 get_editableMemCount() { }
	// RVA: 0x2cb38fc VA: 0x75952cb8fc
	public SquadItemStruct[] get_selfMembers() { }
	// RVA: 0x2cb6570 VA: 0x75952ce570
	public EvolvePhaseAndLevel get_maxEvolvePhaseAndLevel() { }
	// RVA: 0x2cb6608 VA: 0x75952ce608
	public Int32 GetTotalMemCount() { }
	// RVA: 0x2cb66b8 VA: 0x75952ce6b8
	public Void GetAssistDataList(List`1 outputList) { }
	// RVA: 0x2cb6878 VA: 0x75952ce878
	public Int32 GetProfessionCount(ProfessionCategory profession) { }
	// RVA: 0x2cb6af0 VA: 0x75952ceaf0
	private Int32 _GetRealAssistIdx(Int32 index) { }
	// RVA: 0x2cb4708 VA: 0x75952cc708
	public Void LoadDataFromClimbTower(PlayerTower playerTower) { }
	// RVA: 0x2cb6b70 VA: 0x75952ceb70
	private Void _LoadSquadFromPlayerData(PlayerTower playerTower, out SquadItemStruct[] squadItemList) { }
	// RVA: 0x2cb4e28 VA: 0x75952cce28
	public ClimbTowerFriendAssistModel GetAssistModelByIndex(Int32 index) { }
	// RVA: 0x2cb5ad4 VA: 0x75952cdad4
	public Boolean TryGetInstInSquad(Int32 instId, out SquadItemStruct inst) { }
	// RVA: 0x2cb701c VA: 0x75952cf01c
	public Void ShrinkAssistList() { }
	// RVA: 0x2cb4978 VA: 0x75952cc978
	public Boolean CheckIfContainedInAssistList(String charId, Int32 m_selectAssistIndex) { }
	// RVA: 0x2cb71e4 VA: 0x75952cf1e4
	public Boolean IsFull() { }
	// RVA: 0x2cb7258 VA: 0x75952cf258
	public Int32 GetAvailAssistIndex() { }
	// RVA: 0x2cb4a8c VA: 0x75952cca8c
	public Boolean TryGetMutuallyExclusiveCharInfoInAssist(Int32 m_selectAssistIndex, String charId, out String exclusiveCharInfo) { }
	// RVA: 0x2cb59a4 VA: 0x75952cd9a4
	public Void CheckAndClearMutuallyExclusiveChar(String charId) { }
	// RVA: 0x2cb4698 VA: 0x75952cc698
	public Void .ctor() { }
}
```
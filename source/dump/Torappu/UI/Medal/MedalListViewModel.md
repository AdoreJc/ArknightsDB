# MedalListViewModel

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Int64 m_lastReloadTs`

- `MedalCount m_allMedalCount`

- `MedalCount m_oneMedalCount`

- `MedalCount m_twoMedalCount`

- `MedalCount m_threeMedalCount`

- `ListFilter m_listFilter`


## Properties

- `Int32 haveCount`

- `Int32 totalCount`

- `Int32 haveOneCount`

- `Int32 totalOneCount`

- `Int32 haveTwoCount`

- `Int32 totalTwoCount`

- `Int32 haveThreeCount`

- `Int32 totalThreeCount`


## Methods

- `Int32 get_haveCount()`

- `Int32 get_totalCount()`

- `Int32 get_haveOneCount()`

- `Int32 get_totalOneCount()`

- `Int32 get_haveTwoCount()`

- `Int32 get_totalTwoCount()`

- `Int32 get_haveThreeCount()`

- `Int32 get_totalThreeCount()`

- `Void _LoadBarListModelsIfNot()`

- `Void _InitGroupListIfNeeded()`

- `Void _InitGroupTemplatesIfNeeded()`

- `Void _ResetListsForDisplay()`

- `MedalGroupViewModel GetMostRecentNonDefaultGroup()`

- `Void ReloadData(Boolean)`

- `Void UpdatePlayerStatus()`

- `ListFilter GetListFilter()`

- `Boolean ChangeFilterStatus(ListFilter)`

- `Void _PostUpdateTypeAndGroupStatus(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListViewModel : IHotfixable
{
	private Int64 m_lastReloadTs; // 0x10
	private ListDict`2 m_rawMedalData; // 0x18
	private MedalCount m_allMedalCount; // 0x20
	private MedalCount m_oneMedalCount; // 0x2c
	private MedalCount m_twoMedalCount; // 0x38
	private MedalCount m_threeMedalCount; // 0x44
	private ListFilter m_listFilter; // 0x50
	private List`1 m_barList4Display; // 0x60
	private List`1 m_typeList4Display; // 0x68
	private List`1 m_groupList4Display; // 0x70
	private List`1 m_groupTemplates4Display; // 0x78
	private static DelegateBridge __Hotfix0_get_haveCount; // 0x0
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x8
	private static DelegateBridge __Hotfix0_get_haveOneCount; // 0x10
	private static DelegateBridge __Hotfix0_get_totalOneCount; // 0x18
	private static DelegateBridge __Hotfix0_get_haveTwoCount; // 0x20
	private static DelegateBridge __Hotfix0_get_totalTwoCount; // 0x28
	private static DelegateBridge __Hotfix0_get_haveThreeCount; // 0x30
	private static DelegateBridge __Hotfix0_get_totalThreeCount; // 0x38
	private static DelegateBridge __Hotfix0_GetBarListModels4Display; // 0x40
	private static DelegateBridge __Hotfix0__LoadBarListModelsIfNot; // 0x48
	private static DelegateBridge __Hotfix0_GetTypeList4Display; // 0x50
	private static DelegateBridge __Hotfix0_GetGroupList4Display; // 0x58
	private static DelegateBridge __Hotfix0__InitGroupListIfNeeded; // 0x60
	private static DelegateBridge __Hotfix0_GetGroupTemplates4Display; // 0x68
	private static DelegateBridge __Hotfix0__InitGroupTemplatesIfNeeded; // 0x70
	private static DelegateBridge __Hotfix0__ResetListsForDisplay; // 0x78
	private static DelegateBridge __Hotfix0_GetMostRecentNonDefaultGroup; // 0x80
	private static DelegateBridge __Hotfix0_ReloadData; // 0x88
	private static DelegateBridge __Hotfix0_UpdatePlayerStatus; // 0x90
	private static DelegateBridge __Hotfix0_GetListFilter; // 0x98
	private static DelegateBridge __Hotfix0_ChangeFilterStatus; // 0xa0
	private static DelegateBridge __Hotfix0__PostUpdateTypeAndGroupStatus; // 0xa8
	private static DelegateBridge __Hotfix0_GetMedalEnumerator; // 0xb0
	private static DelegateBridge __Hotfix0__GetWrappedMedalEnumerator; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public Int32 haveCount { get; }
	public Int32 totalCount { get; }
	public Int32 haveOneCount { get; }
	public Int32 totalOneCount { get; }
	public Int32 haveTwoCount { get; }
	public Int32 totalTwoCount { get; }
	public Int32 haveThreeCount { get; }
	public Int32 totalThreeCount { get; }

	// RVA: 0x27a677c VA: 0x7594dbe77c
	public Int32 get_haveCount() { }
	// RVA: 0x27a6808 VA: 0x7594dbe808
	public Int32 get_totalCount() { }
	// RVA: 0x27a6894 VA: 0x7594dbe894
	public Int32 get_haveOneCount() { }
	// RVA: 0x27a6920 VA: 0x7594dbe920
	public Int32 get_totalOneCount() { }
	// RVA: 0x27a69ac VA: 0x7594dbe9ac
	public Int32 get_haveTwoCount() { }
	// RVA: 0x27a6a38 VA: 0x7594dbea38
	public Int32 get_totalTwoCount() { }
	// RVA: 0x27a6ac4 VA: 0x7594dbeac4
	public Int32 get_haveThreeCount() { }
	// RVA: 0x27a6b50 VA: 0x7594dbeb50
	public Int32 get_totalThreeCount() { }
	// RVA: 0x27a6198 VA: 0x7594dbe198
	public List`1 GetBarListModels4Display() { }
	// RVA: 0x27ab9a8 VA: 0x7594dc39a8
	private Void _LoadBarListModelsIfNot() { }
	// RVA: 0x27a5d84 VA: 0x7594dbdd84
	public List`1 GetTypeList4Display() { }
	// RVA: 0x27ac018 VA: 0x7594dc4018
	public List`1 GetGroupList4Display() { }
	// RVA: 0x27ac088 VA: 0x7594dc4088
	private Void _InitGroupListIfNeeded() { }
	// RVA: 0x27ac50c VA: 0x7594dc450c
	public List`1 GetGroupTemplates4Display() { }
	// RVA: 0x27ac57c VA: 0x7594dc457c
	private Void _InitGroupTemplatesIfNeeded() { }
	// RVA: 0x27ac8f8 VA: 0x7594dc48f8
	private Void _ResetListsForDisplay() { }
	// RVA: 0x27ac998 VA: 0x7594dc4998
	public MedalGroupViewModel GetMostRecentNonDefaultGroup() { }
	// RVA: 0x27acb6c VA: 0x7594dc4b6c
	public Void ReloadData(Boolean abortNotGetMedals) { }
	// RVA: 0x27ad4f0 VA: 0x7594dc54f0
	public Void UpdatePlayerStatus() { }
	// RVA: 0x27a6208 VA: 0x7594dbe208
	public ListFilter GetListFilter() { }
	// RVA: 0x27ad6f0 VA: 0x7594dc56f0
	public Boolean ChangeFilterStatus(ListFilter targetFilter) { }
	// RVA: 0x27ad074 VA: 0x7594dc5074
	private Void _PostUpdateTypeAndGroupStatus(Int64 curTs) { }
	// RVA: 0x27ad800 VA: 0x7594dc5800
	public IEnumerator`1 GetMedalEnumerator() { }
	// RVA: 0x27abd64 VA: 0x7594dc3d64
	private static IEnumerator`1 _GetWrappedMedalEnumerator(ListDict`2 typeList) { }
	// RVA: 0x27ad8fc VA: 0x7594dc58fc
	public Void .ctor() { }
}
```
# FriendListViewModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `String friendSearchData`

- `Boolean myFriendsListChangeFlag`

- `Boolean friendRequestListChangeFlag`

- `Boolean friendSearchResultChangeFlag`

- `Boolean myFriendsListRefreshFlag`

- `Boolean friendRequestListRefreshFlag`

- `Boolean friendSearchResultRefreshFlag`

- `Boolean friendAssistChangeFlag`

- `Boolean friendAssistUnSaveFlag`

- `Boolean friendAssistFloatPanelShowFlag`

- `Int32 friendAssistFloatPanelFocusedIndex`

- `String friendAssistFloatPanelSelectedId`

- `ItemType friendAssistFloatPanelShowType`


## Properties

- `Int32 friendCount`

- `Int32 friendSearchCount`

- `Int32 friendRequestCount`


## Methods

- `Void set_myFriendsList(List`1)`

- `Void set_friendSearchResult(List`1)`

- `Void set_friendRequestList(List`1)`

- `FriendSortViewModel SearchSortViewModelByUid(String)`

- `FriendSortViewModel SearchSearchSortViewModelByUid(String)`

- `FriendSortViewModel SearchRequestSortViewModelByUid(String)`

- `Void SetEditingAssists(UISquadEditCharModel[])`

- `Void UpdateEditingAssists(out)`

- `Int32 get_friendCount()`

- `Int32 get_friendSearchCount()`

- `Int32 get_friendRequestCount()`

- `Void MarkAssitListDataDirty()`

- `Void ApplyAssist(Int32, Int32, String, String)`

- `Void CleanAssist(Int32)`

- `Void ApplyAssistSkill(Int32, String)`

- `Void ApplyAssistEquip(Int32, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendListViewModel
{
	public List`1 myFriendsIdList; // 0x10
	public List`1 friendSearchIdList; // 0x18
	public List`1 friendRequestIdList; // 0x20
	public List`1 friendSearchState; // 0x28
	public List`1 friendAlias; // 0x30
	private List`1 m_myFriendsList; // 0x38
	private List`1 m_friendRequestList; // 0x40
	private List`1 m_friendSearchResult; // 0x48
	public SharedCharData[] mySharedChar; // 0x50
	private UISquadEditCharModel[] m_editingAssists; // 0x58
	public String friendSearchData; // 0x60
	public Boolean myFriendsListChangeFlag; // 0x68
	public Boolean friendRequestListChangeFlag; // 0x69
	public Boolean friendSearchResultChangeFlag; // 0x6a
	public Boolean myFriendsListRefreshFlag; // 0x6b
	public Boolean friendRequestListRefreshFlag; // 0x6c
	public Boolean friendSearchResultRefreshFlag; // 0x6d
	public Boolean friendAssistChangeFlag; // 0x6e
	public Boolean friendAssistUnSaveFlag; // 0x6f
	public Boolean friendAssistFloatPanelShowFlag; // 0x70
	public Int32 friendAssistFloatPanelFocusedIndex; // 0x74
	public String friendAssistFloatPanelSelectedId; // 0x78
	public ItemType friendAssistFloatPanelShowType; // 0x80

	public List`1 myFriendsList { get; set; }
	public List`1 friendSearchResult { get; set; }
	public List`1 friendRequestList { get; set; }
	public Int32 friendCount { get; }
	public Int32 friendSearchCount { get; }
	public Int32 friendRequestCount { get; }

	// RVA: 0x28bd240 VA: 0x7594ed5240
	public List`1 get_myFriendsList() { }
	// RVA: 0x28bd248 VA: 0x7594ed5248
	public Void set_myFriendsList(List`1 value) { }
	// RVA: 0x28bd250 VA: 0x7594ed5250
	public List`1 get_friendSearchResult() { }
	// RVA: 0x28b395c VA: 0x7594ecb95c
	public Void set_friendSearchResult(List`1 value) { }
	// RVA: 0x28bd258 VA: 0x7594ed5258
	public List`1 get_friendRequestList() { }
	// RVA: 0x28b24a8 VA: 0x7594eca4a8
	public Void set_friendRequestList(List`1 value) { }
	// RVA: 0x28bd260 VA: 0x7594ed5260
	public FriendSortViewModel SearchSortViewModelByUid(String uid) { }
	// RVA: 0x28bd360 VA: 0x7594ed5360
	public FriendSortViewModel SearchSearchSortViewModelByUid(String uid) { }
	// RVA: 0x28bd458 VA: 0x7594ed5458
	public FriendSortViewModel SearchRequestSortViewModelByUid(String uid) { }
	// RVA: 0x28bd550 VA: 0x7594ed5550
	public List`1 LoadFriendAssistViewDatas() { }
	// RVA: 0x28bc69c VA: 0x7594ed469c
	public UISquadEditCharModel[] GetEditingAssists() { }
	// RVA: 0x28bdd44 VA: 0x7594ed5d44
	public Void SetEditingAssists(UISquadEditCharModel[] setVal) { }
	// RVA: 0x28bcc8c VA: 0x7594ed4c8c
	public Void UpdateEditingAssists(out Boolean tmplChange) { }
	// RVA: 0x28bdd68 VA: 0x7594ed5d68
	public Int32 get_friendCount() { }
	// RVA: 0x28bddb4 VA: 0x7594ed5db4
	public Int32 get_friendSearchCount() { }
	// RVA: 0x28bde00 VA: 0x7594ed5e00
	public Int32 get_friendRequestCount() { }
	// RVA: 0x28bde4c VA: 0x7594ed5e4c
	public Void MarkAssitListDataDirty() { }
	// RVA: 0x28bcd14 VA: 0x7594ed4d14
	public Void ApplyAssist(Int32 selectedCharacterIndex, Int32 chrInstId, String skillId, String equipId) { }
	// RVA: 0x28bccc0 VA: 0x7594ed4cc0
	public Void CleanAssist(Int32 selectedIndex) { }
	// RVA: 0x28bd03c VA: 0x7594ed503c
	public Void ApplyAssistSkill(Int32 selectedIndex, String skillId) { }
	// RVA: 0x28bd134 VA: 0x7594ed5134
	public Void ApplyAssistEquip(Int32 selectedIndex, String equipId) { }
	// RVA: 0x28bde58 VA: 0x7594ed5e58
	public Void .ctor() { }
}
```
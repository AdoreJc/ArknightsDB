# FriendSearchState

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendListStateBean _stateBean`

- `FriendSearchView _searchView`

- `String m_cacheInputNickName`

- `String m_inputNickId`


## Methods

- `Void RemoveTop()`

- `Void OnSearch(String)`

- `Void OnFriendRequest(FriendData)`

- `Void SendSearchRequest(String, String)`

- `Void _SendSearchContinue(Int32)`

- `Void SendSearchResultNextPage(Int32)`

- `Void SendSearchResultNextPage()`

- `Void _SendFriendProcessRequestListRequest(FriendData)`

- `Void <SendSearchRequest>b__8_0(GetSortListInfoResponse)`

- `Void <_SendFriendProcessRequestListRequest>b__12_0(SendFriendResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendSearchState : PopupFloatState
{
	private FriendListStateBean _stateBean; // 0x70
	private FriendSearchView _searchView; // 0x78
	private String m_cacheInputNickName; // 0x80
	private String m_inputNickId; // 0x88
	private const String LEVEL_PARAM; // 0x0
	private const String NICKNAME_PARAM; // 0x0
	private const String NICKID_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_RemoveTop; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnSearch; // 0x10
	private static DelegateBridge __Hotfix0_OnFriendRequest; // 0x18
	private static DelegateBridge __Hotfix0_SendSearchRequest; // 0x20
	private static DelegateBridge __Hotfix0__SendSearchContinue; // 0x28
	private static DelegateBridge __Hotfix0_SendSearchResultNextPage; // 0x30
	private static DelegateBridge __Hotfix1_SendSearchResultNextPage; // 0x38
	private static DelegateBridge __Hotfix0__SendFriendProcessRequestListRequest; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x28b3788 VA: 0x7594ecb788
	public Void RemoveTop() { }
	// RVA: 0x28b3980 VA: 0x7594ecb980
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28b39e8 VA: 0x7594ecb9e8
	public Void OnSearch(String searchKeyWord) { }
	// RVA: 0x28b3ef4 VA: 0x7594ecbef4
	public Void OnFriendRequest(FriendData friend) { }
	// RVA: 0x28b3b58 VA: 0x7594ecbb58
	public Void SendSearchRequest(String inputNickName, String inputNickId) { }
	// RVA: 0x28b4164 VA: 0x7594ecc164
	private Void _SendSearchContinue(Int32 index) { }
	// RVA: 0x28b45a4 VA: 0x7594ecc5a4
	public Void SendSearchResultNextPage(Int32 index) { }
	// RVA: 0x28b4670 VA: 0x7594ecc670
	public Void SendSearchResultNextPage() { }
	// RVA: 0x28b3f74 VA: 0x7594ecbf74
	private Void _SendFriendProcessRequestListRequest(FriendData friend) { }
	// RVA: 0x28b4754 VA: 0x7594ecc754
	public Void .ctor() { }
	// RVA: 0x28b47c4 VA: 0x7594ecc7c4
	private Void <SendSearchRequest>b__8_0(GetSortListInfoResponse response) { }
	// RVA: 0x28b4b84 VA: 0x7594eccb84
	private Void <_SendFriendProcessRequestListRequest>b__12_0(SendFriendResponse response) { }
}
```
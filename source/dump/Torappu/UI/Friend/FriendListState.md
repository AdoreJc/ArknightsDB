# FriendListState

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendListStateBean _stateBean`

- `FriendStateControl _stateControl`

- `FriendAliasView _aliasView`


## Methods

- `Void OnFriendShow(FriendData)`

- `Void OnDeleteFriend(String)`

- `Void OnAliasRequest(String, String)`

- `Void OnAliasSendRequest(String, String)`

- `Void OnCancelAlias()`

- `Void _SendFriendList(Int32)`

- `Void SendFriendListRequest()`

- `Void SendFriendListRequestContinue()`

- `Void _SendDeleteFriend(String)`

- `Void _SendSetFriendAliasRequest(String, String)`

- `Void <SendFriendListRequest>b__13_0(GetSortListInfoResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendListState : State
{
	private FriendListStateBean _stateBean; // 0x50
	private FriendStateControl _stateControl; // 0x58
	private FriendAliasView _aliasView; // 0x60
	private const String LEVEL_PARAM; // 0x0
	private const String INFO_SHARE_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnFriendShow; // 0x10
	private static DelegateBridge __Hotfix0_OnDeleteFriend; // 0x18
	private static DelegateBridge __Hotfix0_OnAliasRequest; // 0x20
	private static DelegateBridge __Hotfix0_OnAliasSendRequest; // 0x28
	private static DelegateBridge __Hotfix0_OnCancelAlias; // 0x30
	private static DelegateBridge __Hotfix0__SendFriendList; // 0x38
	private static DelegateBridge __Hotfix0_SendFriendListRequest; // 0x40
	private static DelegateBridge __Hotfix0_SendFriendListRequestContinue; // 0x48
	private static DelegateBridge __Hotfix0__SendDeleteFriend; // 0x50
	private static DelegateBridge __Hotfix0__SendSetFriendAliasRequest; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x28af120 VA: 0x7594ec7120
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28af188 VA: 0x7594ec7188
	protected override Void OnEnter() { }
	// RVA: 0x28af7d4 VA: 0x7594ec77d4
	public Void OnFriendShow(FriendData friendData) { }
	// RVA: 0x28af920 VA: 0x7594ec7920
	public Void OnDeleteFriend(String uid) { }
	// RVA: 0x28afb10 VA: 0x7594ec7b10
	public Void OnAliasRequest(String alias, String uid) { }
	// RVA: 0x28afbc4 VA: 0x7594ec7bc4
	public Void OnAliasSendRequest(String uid, String alias) { }
	// RVA: 0x28afee0 VA: 0x7594ec7ee0
	public Void OnCancelAlias() { }
	// RVA: 0x28aff60 VA: 0x7594ec7f60
	private Void _SendFriendList(Int32 index) { }
	// RVA: 0x28af3ac VA: 0x7594ec73ac
	public Void SendFriendListRequest() { }
	// RVA: 0x28b03a8 VA: 0x7594ec83a8
	public Void SendFriendListRequestContinue() { }
	// RVA: 0x28b048c VA: 0x7594ec848c
	private Void _SendDeleteFriend(String uid) { }
	// RVA: 0x28afc70 VA: 0x7594ec7c70
	private Void _SendSetFriendAliasRequest(String uid, String alias) { }
	// RVA: 0x28b06d8 VA: 0x7594ec86d8
	public Void .ctor() { }
	// RVA: 0x28b0748 VA: 0x7594ec8748
	private Void <SendFriendListRequest>b__13_0(GetSortListInfoResponse response) { }
	// RVA: 0x28b099c VA: 0x7594ec899c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
# FriendRequestState

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendListStateBean _stateBean`

- `FriendStateControl _stateControl`


## Methods

- `Void OnFriendDealRequest(FriendData, FriendDealEnum)`

- `Void SendFriendRequestListRequest()`

- `Void SendFriendRequestListRequestContinue()`

- `Void _SendFriendRequestListRequest(Int32)`

- `Void _SendFriendDealRequest(FriendData, FriendDealEnum)`

- `Void <SendFriendRequestListRequest>b__4_0(GetSortListInfoResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendRequestState : State
{
	private FriendListStateBean _stateBean; // 0x50
	private FriendStateControl _stateControl; // 0x58
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnFriendDealRequest; // 0x8
	private static DelegateBridge __Hotfix0_SendFriendRequestListRequest; // 0x10
	private static DelegateBridge __Hotfix0_SendFriendRequestListRequestContinue; // 0x18
	private static DelegateBridge __Hotfix0__SendFriendRequestListRequest; // 0x20
	private static DelegateBridge __Hotfix0__SendFriendDealRequest; // 0x28
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x28b2368 VA: 0x7594eca368
	protected override Void OnEnter() { }
	// RVA: 0x28b27fc VA: 0x7594eca7fc
	public Void OnFriendDealRequest(FriendData requestPlayer, FriendDealEnum dealAction) { }
	// RVA: 0x28b24cc VA: 0x7594eca4cc
	public Void SendFriendRequestListRequest() { }
	// RVA: 0x28b2acc VA: 0x7594ecaacc
	public Void SendFriendRequestListRequestContinue() { }
	// RVA: 0x28b2bb0 VA: 0x7594ecabb0
	private Void _SendFriendRequestListRequest(Int32 index) { }
	// RVA: 0x28b2888 VA: 0x7594eca888
	private Void _SendFriendDealRequest(FriendData requestPlayer, FriendDealEnum dealAction) { }
	// RVA: 0x28b2ff8 VA: 0x7594ecaff8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28b3060 VA: 0x7594ecb060
	public Void .ctor() { }
	// RVA: 0x28b30d0 VA: 0x7594ecb0d0
	private Void <SendFriendRequestListRequest>b__4_0(GetSortListInfoResponse response) { }
	// RVA: 0x28b3210 VA: 0x7594ecb210
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
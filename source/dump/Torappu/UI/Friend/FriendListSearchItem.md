# FriendListSearchItem

**Namespace:** `Torappu.UI.Friend`


## Fields

- `ThreeStateToggle _addFriendFlag`


## Methods

- `Void SetFriend(FriendStatus)`

- `Void AddFriend()`

- `Void AlreadySend()`

- `Void AlreadyFriend()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendListSearchItem : FriendListItem
{
	private ThreeStateToggle _addFriendFlag; // 0x100
	public Action`1 DealAction; // 0x108
	private const Int32 NORMAL; // 0x0
	private const Int32 ALREADY_SEND; // 0x0
	private const Int32 ALREADY_ADD; // 0x0
	private static DelegateBridge __Hotfix0_SetFriend; // 0x0
	private static DelegateBridge __Hotfix0_AddFriend; // 0x8
	private static DelegateBridge __Hotfix0_AlreadySend; // 0x10
	private static DelegateBridge __Hotfix0_AlreadyFriend; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28ce770 VA: 0x7594ee6770
	public Void SetFriend(FriendStatus friendAdded) { }
	// RVA: 0x28ce840 VA: 0x7594ee6840
	public Void AddFriend() { }
	// RVA: 0x28ce8c0 VA: 0x7594ee68c0
	public Void AlreadySend() { }
	// RVA: 0x28ce95c VA: 0x7594ee695c
	public Void AlreadyFriend() { }
	// RVA: 0x28ce9f8 VA: 0x7594ee69f8
	public Void .ctor() { }
}
```
# BuildingVisitContext

**Namespace:** `Torappu`


## Fields

- `Int32 nextIndex`

- `String originScene`

- `PlayerInfo playerInfo`


## Methods

- `Boolean TryFindFriend(String, out)`

- `Boolean TryPickNextFriend(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuildingVisitContext
{
	public Int32 nextIndex; // 0x10
	public String originScene; // 0x18
	public PlayerInfo playerInfo; // 0x20
	public List`1 sortedFriendList; // 0x48


	// RVA: 0x2d0a460 VA: 0x7595322460
	public Boolean TryFindFriend(String uid, out FriendInfo target) { }
	// RVA: 0x2d0a580 VA: 0x7595322580
	public Boolean TryPickNextFriend(out FriendInfo nextFriend) { }
	// RVA: 0x2d0a660 VA: 0x7595322660
	public Void .ctor() { }
}
```
# SendFriendRequest

**Namespace:** `Torappu`


## Fields

- `String friendId`

- `Int32 afterBattle`

- `Int32 originType`

- `String battleOrigin`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SendFriendRequest
{
	public const Int32 SOURCE_NONE; // 0x0
	public const Int32 FROM_DEFAULT_BATTLE; // 0x0
	public const Int32 ROGUELIKE_FRIEND; // 0x0
	public const Int32 FRIEND_SEARCH; // 0x0
	public const Int32 SQUAD; // 0x0
	public const Int32 MULTIPLAY_MANUAL; // 0x0
	public const Int32 ENEMY_DUEL_MANUAL; // 0x0
	public String friendId; // 0x10
	public Int32 afterBattle; // 0x18
	public Int32 originType; // 0x1c
	public String battleOrigin; // 0x20


	// RVA: 0x32cb838 VA: 0x75958e3838
	public Void .ctor() { }
}
```
# SquadAssistData

**Namespace:** `Torappu`


## Fields

- `Int32 assistSlotIndex`

- `String aliasName`

- `Boolean isFriend`

- `Boolean canRequestFriend`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SquadAssistData : FriendCommonData
{
	public Int32 assistSlotIndex; // 0x50
	public String aliasName; // 0x58
	public SharedCharData[] assistCharList; // 0x60
	public Boolean isFriend; // 0x68
	public Boolean canRequestFriend; // 0x69


	// RVA: 0x32cdc54 VA: 0x75958e5c54
	public Void .ctor() { }
}
```
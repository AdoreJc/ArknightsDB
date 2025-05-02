# NameCardViewModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Boolean isSelf`

- `String name`

- `DateTime registerDate`

- `String nickNameId`

- `Int32 level`

- `String id`

- `String serverName`

- `String resume`

- `String lastMissionCode`

- `Int32 charCount`

- `Int32 furnCount`

- `AvatarInfo AvatarInfo`

- `CharUISkinStruct homeIllustChar`

- `FriendMedalBoard medalBoard`


## Methods

- `Void InitSelfData()`

- `Void RefreshSelfData()`

- `Void InitFriendData(FriendDataWithNameCard)`

- `String GetResume()`

- `Void _InitTeamCountList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardViewModel
{
	public Boolean isSelf; // 0x10
	public String name; // 0x18
	public DateTime registerDate; // 0x20
	public String nickNameId; // 0x28
	public Int32 level; // 0x30
	public String id; // 0x38
	public String serverName; // 0x40
	public String resume; // 0x48
	public String lastMissionCode; // 0x50
	public Int32 charCount; // 0x58
	public Int32 furnCount; // 0x5c
	public AvatarInfo AvatarInfo; // 0x60
	public List`1 teamCountList; // 0x68
	public CharUISkinStruct homeIllustChar; // 0x70
	public List`1 sharedCharDataSelf; // 0x80
	public List`1 sharedCharDataFriend; // 0x88
	public FriendMedalBoard medalBoard; // 0x90


	// RVA: 0x28c6348 VA: 0x7594ede348
	public Void InitSelfData() { }
	// RVA: 0x28c7538 VA: 0x7594edf538
	public Void RefreshSelfData() { }
	// RVA: 0x28c7600 VA: 0x7594edf600
	public Void InitFriendData(FriendDataWithNameCard data) { }
	// RVA: 0x28c7d4c VA: 0x7594edfd4c
	public String GetResume() { }
	// RVA: 0x28c70f8 VA: 0x7594edf0f8
	private Void _InitTeamCountList() { }
	// RVA: 0x28c7ddc VA: 0x7594edfddc
	public Void .ctor() { }
}
```
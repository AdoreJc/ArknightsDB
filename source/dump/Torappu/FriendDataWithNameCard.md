# FriendDataWithNameCard

**Namespace:** `Torappu`


## Fields

- `DateTime registerTs`

- `PlayerBirthday birthday`

- `String mainStageProgress`

- `Int32 charCnt`

- `Int32 skinCnt`

- `Int32 furnCnt`

- `String secretary`

- `String secretarySkinId`

- `String resume`

- `FriendMedalBoard medalBoard`

- `PlayerNameCardStyle nameCardStyle`

- `BusinessCardEquipStatus equipStatus`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class FriendDataWithNameCard : FriendData
{
	public DateTime registerTs; // 0x78
	public PlayerBirthday birthday; // 0x80
	public String mainStageProgress; // 0x88
	public Int32 charCnt; // 0x90
	public Int32 skinCnt; // 0x94
	public Int32 furnCnt; // 0x98
	public String secretary; // 0xa0
	public String secretarySkinId; // 0xa8
	public String resume; // 0xb0
	public Dictionary`2 team; // 0xb8
	public Dictionary`2 teamV2; // 0xc0
	public FriendMedalBoard medalBoard; // 0xc8
	public PlayerNameCardStyle nameCardStyle; // 0xd0
	public BusinessCardEquipStatus equipStatus; // 0xd8


	// RVA: 0x352cc28 VA: 0x7595b44c28
	public Void .ctor() { }
}
```
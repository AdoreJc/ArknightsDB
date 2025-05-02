# PlayerStatus

**Namespace:** `Torappu`


## Fields

- `String nickName`

- `String nickNumber`

- `String serverName`

- `Int32 ap`

- `DateTime lastApAddTime`

- `DateTime lastRefreshTs`

- `DateTime lastOnlineTs`

- `Int32 level`

- `Int32 exp`

- `Int32 maxAp`

- `Int32 practiceTicket`

- `Int64 gold`

- `Int32 diamondShard`

- `Int32 recruitLicense`

- `Int32 gachaTicket`

- `Int32 tenGachaTicket`

- `Int32 instantFinishTicket`

- `Int32 hggShard`

- `Int32 lggShard`

- `Int32 classicShard`

- `Int32 socialPoint`

- `Int32 buyApRemainTimes`

- `Boolean apLimitUpFlag`

- `Int32 classicGachaTicket`

- `Int32 classicTenGachaTicket`

- `Int64 registerTs`

- `String secretary`

- `String secretarySkinId`

- `String resume`

- `PlayerBirthday birthday`

- `DateTime monthlySubscriptionEndTime`

- `DateTime monthlySubscriptionStartTime`

- `Int32 progress`

- `String mainStageProgress`

- `AvatarInfo avatar`

- `VoiceLangType globalVoiceLan`

- `Int32 iosDiamond`

- `Int32 androidDiamond`

- `Int32 payDiamond`

- `Int32 freeDiamond`


## Properties

- `Int32 diamond`


## Methods

- `Int32 get_diamond()`

- `String GetNickNameWithNumber()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerStatus : IHotfixable
{
	public String nickName; // 0x10
	public String nickNumber; // 0x18
	public String serverName; // 0x20
	public Int32 ap; // 0x28
	public DateTime lastApAddTime; // 0x30
	public DateTime lastRefreshTs; // 0x38
	public DateTime lastOnlineTs; // 0x40
	public Int32 level; // 0x48
	public Int32 exp; // 0x4c
	public Int32 maxAp; // 0x50
	public Int32 practiceTicket; // 0x54
	public Int64 gold; // 0x58
	public Int32 diamondShard; // 0x60
	public Int32 recruitLicense; // 0x64
	public Int32 gachaTicket; // 0x68
	public Int32 tenGachaTicket; // 0x6c
	public Int32 instantFinishTicket; // 0x70
	public Int32 hggShard; // 0x74
	public Int32 lggShard; // 0x78
	public Int32 classicShard; // 0x7c
	public Int32 socialPoint; // 0x80
	public Int32 buyApRemainTimes; // 0x84
	public Boolean apLimitUpFlag; // 0x88
	public Int32 classicGachaTicket; // 0x8c
	public Int32 classicTenGachaTicket; // 0x90
	public Int64 registerTs; // 0x98
	public String secretary; // 0xa0
	public String secretarySkinId; // 0xa8
	public String resume; // 0xb0
	public PlayerBirthday birthday; // 0xb8
	public DateTime monthlySubscriptionEndTime; // 0xc0
	public DateTime monthlySubscriptionStartTime; // 0xc8
	public Int32 progress; // 0xd0
	public String mainStageProgress; // 0xd8
	public AvatarInfo avatar; // 0xe0
	public VoiceLangType globalVoiceLan; // 0xe8
	public Int32 iosDiamond; // 0xec
	public Int32 androidDiamond; // 0xf0
	public Int32 payDiamond; // 0xf4
	public Int32 freeDiamond; // 0xf8
	public Dictionary`2 flags; // 0x100
	public List`1 friendAssist; // 0x108
	private static DelegateBridge __Hotfix0_get_diamond; // 0x0
	private static DelegateBridge __Hotfix0_GetNickNameWithNumber; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Int32 diamond { get; }

	// RVA: 0x32ce2f8 VA: 0x75958e62f8
	public Int32 get_diamond() { }
	// RVA: 0x32ce39c VA: 0x75958e639c
	public String GetNickNameWithNumber() { }
	// RVA: 0x32ce45c VA: 0x75958e645c
	public Void .ctor() { }
}
```
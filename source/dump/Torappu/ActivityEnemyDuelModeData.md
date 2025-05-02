# ActivityEnemyDuelModeData

**Namespace:** `Torappu`


## Fields

- `String modeId`

- `Boolean isMultiPlayer`

- `Boolean isRoom`

- `EnemyDuelModeType modeType`

- `Int32 pageId`

- `Int32 innerSortId`

- `String modeName`

- `String modeShortName`

- `String modeEnName`

- `Int32 maxPlayer`

- `String preposedMode`

- `Int64 startTs`

- `Int64 endTs`

- `String entryPicId`

- `String modeTarget`

- `String modeDesc`

- `String modeRecordDesc`

- `Boolean extraTag`

- `String modeAvatarPicId`

- `String modeAvatarName`

- `String modeAvatarText`

- `Boolean hasUnlockToast`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActivityEnemyDuelModeData
{
	public String modeId; // 0x10
	public Boolean isMultiPlayer; // 0x18
	public Boolean isRoom; // 0x19
	public EnemyDuelModeType modeType; // 0x1c
	public List`1 stageIds; // 0x20
	public Int32 pageId; // 0x28
	public Int32 innerSortId; // 0x2c
	public String modeName; // 0x30
	public String modeShortName; // 0x38
	public String modeEnName; // 0x40
	public Int32 maxPlayer; // 0x48
	public String preposedMode; // 0x50
	public Int64 startTs; // 0x58
	public Int64 endTs; // 0x60
	public String entryPicId; // 0x68
	public List`1 titlePics; // 0x70
	public String modeTarget; // 0x78
	public String modeDesc; // 0x80
	public String modeRecordDesc; // 0x88
	public Boolean extraTag; // 0x90
	public String modeAvatarPicId; // 0x98
	public String modeAvatarName; // 0xa0
	public String modeAvatarText; // 0xa8
	public Boolean hasUnlockToast; // 0xb0


	// RVA: 0x33baf50 VA: 0x75959d2f50
	public Void .ctor() { }
}
```
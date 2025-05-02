# ActMultiV3ManualProfileModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int32 completeMatchCount`

- `Int32 assistPlayerCount`

- `Int32 praisedCount`

- `String titlePrefix`

- `String titleSuffix`

- `String skinId`

- `Int32 skinTmpl`

- `String nickName`

- `String nickNameId`

- `Int32 level`

- `String uid`

- `AvatarInfo avatarInfo`

- `Boolean hasTrackPoint`

- `Int32 loadSeqNum`


## Methods

- `Void LoadData(String)`

- `Void RefreshStatus(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualProfileModel : IHotfixable
{
	public Int32 completeMatchCount; // 0x10
	public Int32 assistPlayerCount; // 0x14
	public Int32 praisedCount; // 0x18
	public String titlePrefix; // 0x20
	public String titleSuffix; // 0x28
	public String skinId; // 0x30
	public Int32 skinTmpl; // 0x38
	public String nickName; // 0x40
	public String nickNameId; // 0x48
	public Int32 level; // 0x50
	public String uid; // 0x58
	public AvatarInfo avatarInfo; // 0x60
	public Boolean hasTrackPoint; // 0x68
	public Int32 loadSeqNum; // 0x6c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31214c8 VA: 0x75957394c8
	public Void LoadData(String actId) { }
	// RVA: 0x3122848 VA: 0x759573a848
	public Void RefreshStatus(String actId) { }
	// RVA: 0x3122650 VA: 0x759573a650
	public Void .ctor() { }
}
```
# ActMultiV3PhotoDetailViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String actId`

- `FriendStatus friendStatus`

- `String skinId`

- `Int32 skinTmpl`

- `String fullNickName`

- `Int32 level`

- `String uid`

- `AvatarInfo avatarInfo`

- `String mateTitlePrefix`

- `String mateTitleSuffix`

- `Boolean hasTrackPoint`

- `String photoInstId`

- `String stageName`

- `String stageDifficultyName`

- `String stageModeName`

- `String mineTitlePrefix`

- `String mineTitleSuffix`

- `Int64 ts`

- `Boolean isCommitted`


## Methods

- `Void LoadData(String, String, PhotoInstance, ActMultiV3PhotoTypeData)`

- `String _LoadTitle(String, Dictionary`2)`

- `Void _LoadStageDesc(ActMultiV3Data, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PhotoDetailViewModel : IHotfixable
{
	public String actId; // 0x10
	public FriendStatus friendStatus; // 0x18
	public String skinId; // 0x20
	public Int32 skinTmpl; // 0x28
	public String fullNickName; // 0x30
	public Int32 level; // 0x38
	public String uid; // 0x40
	public AvatarInfo avatarInfo; // 0x48
	public String mateTitlePrefix; // 0x50
	public String mateTitleSuffix; // 0x58
	public Boolean hasTrackPoint; // 0x60
	public String photoInstId; // 0x68
	public String stageName; // 0x70
	public String stageDifficultyName; // 0x78
	public String stageModeName; // 0x80
	public String mineTitlePrefix; // 0x88
	public String mineTitleSuffix; // 0x90
	public Int64 ts; // 0x98
	public List`1 charModels; // 0xa0
	public Boolean isCommitted; // 0xa8
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadTitle; // 0x8
	private static DelegateBridge __Hotfix0__LoadStageDesc; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x311f8fc VA: 0x75957378fc
	public Void LoadData(String actId, String instId, PhotoInstance photo, ActMultiV3PhotoTypeData photoTypeData) { }
	// RVA: 0x31200dc VA: 0x75957380dc
	private String _LoadTitle(String titleId, Dictionary`2 titleDataDict) { }
	// RVA: 0x3120350 VA: 0x7595738350
	private Void _LoadStageDesc(ActMultiV3Data actData, String stageId) { }
	// RVA: 0x311f838 VA: 0x7595737838
	public Void .ctor() { }
}
```
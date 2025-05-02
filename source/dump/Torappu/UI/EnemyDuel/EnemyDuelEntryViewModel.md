# EnemyDuelEntryViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String actId`

- `Boolean showMainWnd`

- `Boolean showMusicWnd`

- `Int32 enterSeq`

- `String videoResPath`

- `String titleMainWnd`

- `String musicName`

- `ActState actState`

- `Boolean isMultiPreposedPassed`

- `Boolean announceShowNew`

- `String announceText`

- `Int32 dailyProcess`

- `Int32 dailyTarget`

- `Boolean haveMatchTrack`

- `String playerName`

- `AvatarInfo playerAvatar`


## Methods

- `Void LoadData(String, TemplateActivityLifeCycleViewModel)`

- `ActivityEnemyDuelAnnounceData _LoadValidAnnounce(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryViewModel : IHotfixable
{
	public String actId; // 0x10
	public Boolean showMainWnd; // 0x18
	public Boolean showMusicWnd; // 0x19
	public Int32 enterSeq; // 0x1c
	public String videoResPath; // 0x20
	public String titleMainWnd; // 0x28
	public String musicName; // 0x30
	public ActState actState; // 0x38
	public Boolean isMultiPreposedPassed; // 0x3c
	public Boolean announceShowNew; // 0x3d
	public String announceText; // 0x40
	public Int32 dailyProcess; // 0x48
	public Int32 dailyTarget; // 0x4c
	public Boolean haveMatchTrack; // 0x50
	public String playerName; // 0x58
	public AvatarInfo playerAvatar; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadValidAnnounce; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2949d48 VA: 0x7594f61d48
	public Void LoadData(String actId, TemplateActivityLifeCycleViewModel actModel) { }
	// RVA: 0x294edb4 VA: 0x7594f66db4
	private ActivityEnemyDuelAnnounceData _LoadValidAnnounce(List`1 announceData) { }
	// RVA: 0x294eef8 VA: 0x7594f66ef8
	public Void .ctor() { }
}
```
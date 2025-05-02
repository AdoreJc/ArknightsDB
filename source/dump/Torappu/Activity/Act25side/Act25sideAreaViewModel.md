# Act25sideAreaViewModel

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `String m_actId`

- `String m_areaId`

- `Int32 m_sortId`

- `String m_areaName`

- `String m_areaIcon`

- `String m_unlockText`

- `Boolean m_isNew`

- `Boolean m_canArchiveAccess`

- `Boolean m_isUnlocked`

- `Boolean m_isBattleOver`

- `Boolean m_isEnd`

- `Boolean m_isEmpty`

- `Boolean m_isMissionComplete`

- `String m_areaDesc`

- `String m_endDesc`

- `Int32 m_progress`

- `String m_progressIconId`

- `Int32 m_costCount`

- `String m_preposedStageId`

- `Act25sideMissionViewModel m_currentMission`


## Properties

- `String actId`

- `Int32 sortId`

- `String areaId`

- `String areaName`

- `String areaIcon`

- `String unlockText`

- `Boolean isNew`

- `Boolean isUnlocked`

- `Boolean canArchiveAccess`

- `Boolean isBattleOver`

- `Boolean isEnd`

- `Boolean isEmpty`

- `Boolean isMissionComplete`

- `String areaDesc`

- `String endDesc`

- `Int32 progress`

- `String progressIconId`

- `Int32 costCount`

- `String preposedStageId`

- `Act25sideMissionViewModel currentMission`


## Methods

- `String get_actId()`

- `Int32 get_sortId()`

- `String get_areaId()`

- `String get_areaName()`

- `String get_areaIcon()`

- `String get_unlockText()`

- `Boolean get_isNew()`

- `Boolean get_isUnlocked()`

- `Boolean get_canArchiveAccess()`

- `Boolean get_isBattleOver()`

- `Boolean get_isEnd()`

- `Boolean get_isEmpty()`

- `Boolean get_isMissionComplete()`

- `String get_areaDesc()`

- `String get_endDesc()`

- `Int32 get_progress()`

- `String get_progressIconId()`

- `Int32 get_costCount()`

- `String get_preposedStageId()`

- `Act25sideMissionViewModel get_currentMission()`

- `Void Load(String, Act25SideData, PlayerAct25SideActivity, AreaInfoData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideAreaViewModel : IHotfixable
{
	private String m_actId; // 0x10
	private String m_areaId; // 0x18
	private Int32 m_sortId; // 0x20
	private String m_areaName; // 0x28
	private String m_areaIcon; // 0x30
	private String m_unlockText; // 0x38
	private Boolean m_isNew; // 0x40
	private Boolean m_canArchiveAccess; // 0x41
	private Boolean m_isUnlocked; // 0x42
	private Boolean m_isBattleOver; // 0x43
	private Boolean m_isEnd; // 0x44
	private Boolean m_isEmpty; // 0x45
	private Boolean m_isMissionComplete; // 0x46
	private String m_areaDesc; // 0x48
	private String m_endDesc; // 0x50
	private Int32 m_progress; // 0x58
	private String m_progressIconId; // 0x60
	private Int32 m_costCount; // 0x68
	private String m_preposedStageId; // 0x70
	private Act25sideMissionViewModel m_currentMission; // 0x78
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_sortId; // 0x8
	private static DelegateBridge __Hotfix0_get_areaId; // 0x10
	private static DelegateBridge __Hotfix0_get_areaName; // 0x18
	private static DelegateBridge __Hotfix0_get_areaIcon; // 0x20
	private static DelegateBridge __Hotfix0_get_unlockText; // 0x28
	private static DelegateBridge __Hotfix0_get_isNew; // 0x30
	private static DelegateBridge __Hotfix0_get_isUnlocked; // 0x38
	private static DelegateBridge __Hotfix0_get_canArchiveAccess; // 0x40
	private static DelegateBridge __Hotfix0_get_isBattleOver; // 0x48
	private static DelegateBridge __Hotfix0_get_isEnd; // 0x50
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x58
	private static DelegateBridge __Hotfix0_get_isMissionComplete; // 0x60
	private static DelegateBridge __Hotfix0_get_areaDesc; // 0x68
	private static DelegateBridge __Hotfix0_get_endDesc; // 0x70
	private static DelegateBridge __Hotfix0_get_progress; // 0x78
	private static DelegateBridge __Hotfix0_get_progressIconId; // 0x80
	private static DelegateBridge __Hotfix0_get_costCount; // 0x88
	private static DelegateBridge __Hotfix0_get_preposedStageId; // 0x90
	private static DelegateBridge __Hotfix0_get_currentMission; // 0x98
	private static DelegateBridge __Hotfix0_Load; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public String actId { get; }
	public Int32 sortId { get; }
	public String areaId { get; }
	public String areaName { get; }
	public String areaIcon { get; }
	public String unlockText { get; }
	public Boolean isNew { get; }
	public Boolean isUnlocked { get; }
	public Boolean canArchiveAccess { get; }
	public Boolean isBattleOver { get; }
	public Boolean isEnd { get; }
	public Boolean isEmpty { get; }
	public Boolean isMissionComplete { get; }
	public String areaDesc { get; }
	public String endDesc { get; }
	public Int32 progress { get; }
	public String progressIconId { get; }
	public Int32 costCount { get; }
	public String preposedStageId { get; }
	public Act25sideMissionViewModel currentMission { get; }

	// RVA: 0x3282a70 VA: 0x759589aa70
	public String get_actId() { }
	// RVA: 0x3287788 VA: 0x759589f788
	public Int32 get_sortId() { }
	// RVA: 0x3282860 VA: 0x759589a860
	public String get_areaId() { }
	// RVA: 0x32828c8 VA: 0x759589a8c8
	public String get_areaName() { }
	// RVA: 0x3287860 VA: 0x759589f860
	public String get_areaIcon() { }
	// RVA: 0x32878c8 VA: 0x759589f8c8
	public String get_unlockText() { }
	// RVA: 0x3282998 VA: 0x759589a998
	public Boolean get_isNew() { }
	// RVA: 0x32827f8 VA: 0x759589a7f8
	public Boolean get_isUnlocked() { }
	// RVA: 0x3283c2c VA: 0x759589bc2c
	public Boolean get_canArchiveAccess() { }
	// RVA: 0x3283bc4 VA: 0x759589bbc4
	public Boolean get_isBattleOver() { }
	// RVA: 0x3282a00 VA: 0x759589aa00
	public Boolean get_isEnd() { }
	// RVA: 0x3283af4 VA: 0x759589baf4
	public Boolean get_isEmpty() { }
	// RVA: 0x3283b5c VA: 0x759589bb5c
	public Boolean get_isMissionComplete() { }
	// RVA: 0x3283da0 VA: 0x759589bda0
	public String get_areaDesc() { }
	// RVA: 0x3283ed8 VA: 0x759589bed8
	public String get_endDesc() { }
	// RVA: 0x3282930 VA: 0x759589a930
	public Int32 get_progress() { }
	// RVA: 0x3283c94 VA: 0x759589bc94
	public String get_progressIconId() { }
	// RVA: 0x3283e08 VA: 0x759589be08
	public Int32 get_costCount() { }
	// RVA: 0x3282d48 VA: 0x759589ad48
	public String get_preposedStageId() { }
	// RVA: 0x3283a8c VA: 0x759589ba8c
	public Act25sideMissionViewModel get_currentMission() { }
	// RVA: 0x3287930 VA: 0x759589f930
	public Void Load(String actId, Act25SideData actData, PlayerAct25SideActivity playerAct, AreaInfoData areaInfoData) { }
	// RVA: 0x3287d5c VA: 0x759589fd5c
	public Void .ctor() { }
}
```
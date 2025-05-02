# Act42D0BattleFinishViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Boolean m_isValid`

- `CharUISkinStruct m_randomIllust`

- `String m_playerName`

- `SquadItemStruct m_assistChar`

- `Act42D0FinishInfoModel m_finishInfoModel`

- `AvatarInfo m_avatarInfo`

- `String m_actId`

- `Int32 m_milestoneLv`

- `Int32 m_milestoneCurrent`

- `Int32 m_milestoneMax`

- `String m_milestoneId`


## Properties

- `String milestoneId`

- `Int32 milestoneLv`

- `String progressStr`

- `Single milestoneProgress`

- `String actId`

- `SquadItemStruct assistChar`

- `String playerName`

- `CharUISkinStruct randomIllust`

- `Int64 finishTs`

- `Boolean isValid`

- `Act42D0FinishInfoModel finishInfoModel`

- `ViewType viewType`

- `AvatarInfo avatarInfo`

- `Int32 milestoneGot`


## Methods

- `String get_milestoneId()`

- `Int32 get_milestoneLv()`

- `String get_progressStr()`

- `Single get_milestoneProgress()`

- `String get_actId()`

- `SquadItemStruct get_assistChar()`

- `String get_playerName()`

- `CharUISkinStruct get_randomIllust()`

- `Int64 get_finishTs()`

- `Boolean get_isValid()`

- `Act42D0FinishInfoModel get_finishInfoModel()`

- `String GetStageName()`

- `String GetDisplayIconId()`

- `ViewType get_viewType()`

- `AvatarInfo get_avatarInfo()`

- `Int32 get_milestoneGot()`

- `Void LoadData()`

- `Void _LoadMilestoneLvInfo(Act42D0Data, Act42D0FinishInfoModel)`

- `Boolean _TryLoadFinishInfo(Act42D0Data, BattleInOut)`

- `Void _LoadBasicInfo(BattleInOut, PlayerDataModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0BattleFinishViewModel : IHotfixable
{
	private Boolean m_isValid; // 0x10
	private CharUISkinStruct m_randomIllust; // 0x18
	private String m_playerName; // 0x28
	private SquadItemStruct[] m_squadList; // 0x30
	private SquadItemStruct m_assistChar; // 0x38
	private Act42D0FinishInfoModel m_finishInfoModel; // 0x48
	private AvatarInfo m_avatarInfo; // 0x50
	private String m_actId; // 0x58
	private Int32 m_milestoneLv; // 0x60
	private Int32 m_milestoneCurrent; // 0x64
	private Int32 m_milestoneMax; // 0x68
	private String m_milestoneId; // 0x70
	private static DelegateBridge __Hotfix0_get_milestoneId; // 0x0
	private static DelegateBridge __Hotfix0_get_milestoneLv; // 0x8
	private static DelegateBridge __Hotfix0_get_progressStr; // 0x10
	private static DelegateBridge __Hotfix0_get_milestoneProgress; // 0x18
	private static DelegateBridge __Hotfix0_get_actId; // 0x20
	private static DelegateBridge __Hotfix0_get_squadList; // 0x28
	private static DelegateBridge __Hotfix0_get_assistChar; // 0x30
	private static DelegateBridge __Hotfix0_get_playerName; // 0x38
	private static DelegateBridge __Hotfix0_get_randomIllust; // 0x40
	private static DelegateBridge __Hotfix0_get_finishTs; // 0x48
	private static DelegateBridge __Hotfix0_get_isValid; // 0x50
	private static DelegateBridge __Hotfix0_get_finishInfoModel; // 0x58
	private static DelegateBridge __Hotfix0_GetStageName; // 0x60
	private static DelegateBridge __Hotfix0_GetDisplayIconId; // 0x68
	private static DelegateBridge __Hotfix0_get_viewType; // 0x70
	private static DelegateBridge __Hotfix0_get_avatarInfo; // 0x78
	private static DelegateBridge __Hotfix0_get_milestoneGot; // 0x80
	private static DelegateBridge __Hotfix0_LoadData; // 0x88
	private static DelegateBridge __Hotfix0__LoadMilestoneLvInfo; // 0x90
	private static DelegateBridge __Hotfix0__TryLoadFinishInfo; // 0x98
	private static DelegateBridge __Hotfix0__LoadBasicInfo; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public String milestoneId { get; }
	public Int32 milestoneLv { get; }
	public String progressStr { get; }
	public Single milestoneProgress { get; }
	public String actId { get; }
	public SquadItemStruct[] squadList { get; }
	public SquadItemStruct assistChar { get; }
	public String playerName { get; }
	public CharUISkinStruct randomIllust { get; }
	public Int64 finishTs { get; }
	public Boolean isValid { get; }
	public Act42D0FinishInfoModel finishInfoModel { get; }
	public ViewType viewType { get; }
	public AvatarInfo avatarInfo { get; }
	public Int32 milestoneGot { get; }

	// RVA: 0x3206580 VA: 0x759581e580
	public String get_milestoneId() { }
	// RVA: 0x3206378 VA: 0x759581e378
	public Int32 get_milestoneLv() { }
	// RVA: 0x32063e0 VA: 0x759581e3e0
	public String get_progressStr() { }
	// RVA: 0x32064fc VA: 0x759581e4fc
	public Single get_milestoneProgress() { }
	// RVA: 0x3205a10 VA: 0x759581da10
	public String get_actId() { }
	// RVA: 0x3207af0 VA: 0x759581faf0
	public SquadItemStruct[] get_squadList() { }
	// RVA: 0x3207a8c VA: 0x759581fa8c
	public SquadItemStruct get_assistChar() { }
	// RVA: 0x32057c4 VA: 0x759581d7c4
	public String get_playerName() { }
	// RVA: 0x32058a4 VA: 0x759581d8a4
	public CharUISkinStruct get_randomIllust() { }
	// RVA: 0x320582c VA: 0x759581d82c
	public Int64 get_finishTs() { }
	// RVA: 0x3206de0 VA: 0x759581ede0
	public Boolean get_isValid() { }
	// RVA: 0x32052d4 VA: 0x759581d2d4
	public Act42D0FinishInfoModel get_finishInfoModel() { }
	// RVA: 0x3205908 VA: 0x759581d908
	public String GetStageName() { }
	// RVA: 0x3205a78 VA: 0x759581da78
	public String GetDisplayIconId() { }
	// RVA: 0x3206e48 VA: 0x759581ee48
	public ViewType get_viewType() { }
	// RVA: 0x32059a8 VA: 0x759581d9a8
	public AvatarInfo get_avatarInfo() { }
	// RVA: 0x3206300 VA: 0x759581e300
	public Int32 get_milestoneGot() { }
	// RVA: 0x3206870 VA: 0x759581e870
	public Void LoadData() { }
	// RVA: 0x3208510 VA: 0x7595820510
	private Void _LoadMilestoneLvInfo(Act42D0Data actData, Act42D0FinishInfoModel finishInfoModel) { }
	// RVA: 0x320834c VA: 0x759582034c
	private Boolean _TryLoadFinishInfo(Act42D0Data actData, BattleInOut battleInOut) { }
	// RVA: 0x3208054 VA: 0x7595820054
	private Void _LoadBasicInfo(BattleInOut battleInOut, PlayerDataModel playerData) { }
	// RVA: 0x32070d8 VA: 0x759581f0d8
	public Void .ctor() { }
}
```
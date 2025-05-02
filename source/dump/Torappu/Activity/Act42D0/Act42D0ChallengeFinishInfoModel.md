# Act42D0ChallengeFinishInfoModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Int32 m_progress`

- `Boolean m_isProgressNew`

- `Act42D0ChallengeInfoData m_stageInfo`


## Properties

- `Int32 progress`

- `Int32 totalMissionCount`

- `Boolean isProgressNew`


## Methods

- `Int32 get_progress()`

- `Int32 get_totalMissionCount()`

- `Boolean get_isProgressNew()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ChallengeFinishInfoModel : Act42D0FinishInfoModel
{
	private Int32 m_progress; // 0x28
	private Boolean m_isProgressNew; // 0x2c
	private Act42D0ChallengeInfoData m_stageInfo; // 0x30
	private static DelegateBridge __Hotfix0_get_progress; // 0x0
	private static DelegateBridge __Hotfix0_get_totalMissionCount; // 0x8
	private static DelegateBridge __Hotfix0_get_isProgressNew; // 0x10
	private static DelegateBridge __Hotfix0_GetStageName; // 0x18
	private static DelegateBridge __Hotfix0_GetViewType; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_GetDisplayIconId; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 progress { get; }
	public Int32 totalMissionCount { get; }
	public Boolean isProgressNew { get; }

	// RVA: 0x3207670 VA: 0x759581f670
	public Int32 get_progress() { }
	// RVA: 0x32076d8 VA: 0x759581f6d8
	public Int32 get_totalMissionCount() { }
	// RVA: 0x3207608 VA: 0x759581f608
	public Boolean get_isProgressNew() { }
	// RVA: 0x3208ec4 VA: 0x7595820ec4
	public override String GetStageName() { }
	// RVA: 0x3208f58 VA: 0x7595820f58
	public override ViewType GetViewType() { }
	// RVA: 0x3208fc0 VA: 0x7595820fc0
	public override Void LoadData(Act42D0Data actData, CommonFinishBattleResponse response) { }
	// RVA: 0x3209118 VA: 0x7595821118
	public override String GetDisplayIconId() { }
	// RVA: 0x32087f4 VA: 0x75958207f4
	public Void .ctor() { }
}
```
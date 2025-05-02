# Act42D0NormalFinishInfoModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Int32 m_ratingLv`

- `Boolean m_isRatingNew`

- `Act42D0StageInfoData m_stageInfo`

- `Act42D0StageRatingInfoData m_stageRatingInfo`

- `Act42D0RatingInfoData m_currentRatingInfo`


## Properties

- `Boolean isRatingNew`

- `Int32 ratingLevel`

- `String ratingAudioSignal`

- `String stageCode`

- `String ratingIconName`

- `String ratingDesc`


## Methods

- `Boolean get_isRatingNew()`

- `Int32 get_ratingLevel()`

- `String get_ratingAudioSignal()`

- `String get_stageCode()`

- `String get_ratingIconName()`

- `String get_ratingDesc()`

- `Act42D0RatingInfoData _FindRatingInfo(Act42D0StageRatingInfoData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0NormalFinishInfoModel : Act42D0FinishInfoModel
{
	private const Int32 RATING_MIN_LEVEL; // 0x0
	private const Int32 RATING_MAX_LEVEL; // 0x0
	private Int32 m_ratingLv; // 0x28
	private Boolean m_isRatingNew; // 0x2c
	private List`1 m_effectDataList; // 0x30
	private Act42D0StageInfoData m_stageInfo; // 0x38
	private Act42D0StageRatingInfoData m_stageRatingInfo; // 0x40
	private Act42D0RatingInfoData m_currentRatingInfo; // 0x48
	private static DelegateBridge __Hotfix0_get_isRatingNew; // 0x0
	private static DelegateBridge __Hotfix0_get_ratingLevel; // 0x8
	private static DelegateBridge __Hotfix0_get_ratingAudioSignal; // 0x10
	private static DelegateBridge __Hotfix0_get_stageCode; // 0x18
	private static DelegateBridge __Hotfix0_get_ratingIconName; // 0x20
	private static DelegateBridge __Hotfix0_get_ratingDesc; // 0x28
	private static DelegateBridge __Hotfix0_get_effectDataList; // 0x30
	private static DelegateBridge __Hotfix0__FindRatingInfo; // 0x38
	private static DelegateBridge __Hotfix0_GetStageName; // 0x40
	private static DelegateBridge __Hotfix0_GetViewType; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_GetDisplayIconId; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Boolean isRatingNew { get; }
	public Int32 ratingLevel { get; }
	public String ratingAudioSignal { get; }
	public String stageCode { get; }
	public String ratingIconName { get; }
	public String ratingDesc { get; }
	public List`1 effectDataList { get; }

	// RVA: 0x32073fc VA: 0x759581f3fc
	public Boolean get_isRatingNew() { }
	// RVA: 0x32053d0 VA: 0x759581d3d0
	public Int32 get_ratingLevel() { }
	// RVA: 0x3206d20 VA: 0x759581ed20
	public String get_ratingAudioSignal() { }
	// RVA: 0x3207368 VA: 0x759581f368
	public String get_stageCode() { }
	// RVA: 0x3207464 VA: 0x759581f464
	public String get_ratingIconName() { }
	// RVA: 0x320533c VA: 0x759581d33c
	public String get_ratingDesc() { }
	// RVA: 0x32074dc VA: 0x759581f4dc
	public List`1 get_effectDataList() { }
	// RVA: 0x3208938 VA: 0x7595820938
	private Act42D0RatingInfoData _FindRatingInfo(Act42D0StageRatingInfoData stageRatingInfo) { }
	// RVA: 0x3208a3c VA: 0x7595820a3c
	public override String GetStageName() { }
	// RVA: 0x3208ad0 VA: 0x7595820ad0
	public override ViewType GetViewType() { }
	// RVA: 0x3208b38 VA: 0x7595820b38
	public override Void LoadData(Act42D0Data actData, CommonFinishBattleResponse response) { }
	// RVA: 0x3208e4c VA: 0x7595820e4c
	public override String GetDisplayIconId() { }
	// RVA: 0x3208734 VA: 0x7595820734
	public Void .ctor() { }
}
```
# CrisisV2AchievementSeasonViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String seasonId`

- `String mapName`

- `String mapCode`

- `MedalGroupViewModel medalGroupModel`

- `CrisisV2AppraiseType appraiseType`

- `Int32 totalScore`

- `Boolean hasRecord`

- `Boolean hasHistory`

- `CrisisV2SnapShotBase snapshotData`

- `Int32 runeCount`

- `AvatarInfo playerAvatarInfo`

- `String playerNickName`

- `String playerNickNumber`

- `Int64 m_startTs`


## Methods

- `Void _LoadCommonData(String, CrisisV2SeasonInfo, ListDict`2, PlayerCrisisV2Season, PlayerStatus, CrisisV2SnapShotBase)`

- `Void _LoadDimensionItemData(IList`1)`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2AchievementSeasonViewModel : IHotfixable, IComparable
{
	public String seasonId; // 0x10
	public String mapName; // 0x18
	public String mapCode; // 0x20
	public MedalGroupViewModel medalGroupModel; // 0x28
	public CrisisV2AppraiseType appraiseType; // 0x30
	public Int32 totalScore; // 0x34
	public Boolean hasRecord; // 0x38
	public Boolean hasHistory; // 0x39
	public CrisisV2SnapShotBase snapshotData; // 0x40
	public Int32 runeCount; // 0x48
	public List`1 runeModelList; // 0x50
	public List`1 commentModelList; // 0x58
	public List`1 dimensionSingleScore; // 0x60
	public List`1 dimensionTotalScore; // 0x68
	public List`1 dimensionDesc; // 0x70
	public List`1 dimensionMaxScore; // 0x78
	public AvatarInfo playerAvatarInfo; // 0x80
	public String playerNickName; // 0x88
	public String playerNickNumber; // 0x90
	private Int64 m_startTs; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetViewModelForCurrSeason; // 0x8
	private static DelegateBridge __Hotfix0_GetViewModelForPassedSeason; // 0x10
	private static DelegateBridge __Hotfix0__LoadCommonData; // 0x18
	private static DelegateBridge __Hotfix0__LoadDimensionItemData; // 0x20
	private static DelegateBridge __Hotfix0_CompareTo; // 0x28
	private static DelegateBridge __Hotfix0__LoadRuneDataFromServer; // 0x30
	private static DelegateBridge __Hotfix0_LoadRuneDataFromServer; // 0x38
	private static DelegateBridge __Hotfix0_LoadCommentDataFromServer; // 0x40
	private static DelegateBridge __Hotfix0_LoadRuneData; // 0x48
	private static DelegateBridge __Hotfix0_LoadCommentData; // 0x50


	// RVA: 0x2be3530 VA: 0x75951fb530
	private Void .ctor() { }
	// RVA: 0x2be3740 VA: 0x75951fb740
	public static CrisisV2AchievementSeasonViewModel GetViewModelForCurrSeason(String seasonId, ListDict`2 scoreLevelToAppraiseDataMap, CrisisV2SeasonInfo data, PlayerCrisisV2Season playerData, PlayerStatus playerStatus, CrisisV2MapStageData mapStageData, CrisisV2MapDetailData mapDetailData, CrisisV2SnapShotBase snapshot) { }
	// RVA: 0x2be4784 VA: 0x75951fc784
	public static CrisisV2AchievementSeasonViewModel GetViewModelForPassedSeason(String seasonId, CrisisV2SeasonInfo data, ListDict`2 scoreLevelToAppraiseDataMap, CrisisV2AchievementData achievement, PlayerCrisisV2Season playerData, PlayerStatus playerStatus, CrisisV2SnapShotBase snapshot) { }
	// RVA: 0x2be3ca4 VA: 0x75951fbca4
	private Void _LoadCommonData(String seasonId, CrisisV2SeasonInfo data, ListDict`2 scoreLevelToAppraiseDataMap, PlayerCrisisV2Season playerData, PlayerStatus playerStatus, CrisisV2SnapShotBase snapshot) { }
	// RVA: 0x2be3a18 VA: 0x75951fba18
	private Void _LoadDimensionItemData(IList`1 dimensionItemList) { }
	// RVA: 0x2be4980 VA: 0x75951fc980
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2be3ff4 VA: 0x75951fbff4
	private static Void _LoadRuneDataFromServer(ref List`1 dataList, IDictionary`2 runePlayerData, CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2be4a7c VA: 0x75951fca7c
	public static Void LoadRuneDataFromServer(ref List`1 dataList, IList`1 runeIdList, CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2be44dc VA: 0x75951fc4dc
	public static Void LoadCommentDataFromServer(ref List`1 dataList, IList`1 commentPlayerData, IDictionary`2 commentDataMap) { }
	// RVA: 0x VA: 0x0
	public static Void LoadRuneData(ref List`1 runeModelList, IList`1 runeData) { }
	// RVA: 0x VA: 0x0
	public static Void LoadCommentData(ref List`1 commentModelList, IList`1 commentData) { }
}
```
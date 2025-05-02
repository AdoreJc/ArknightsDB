# HomeMainStateBean

**Namespace:** `Torappu.UI.Home`


## Fields

- `ResourceBarViewProperty _resourceProperty`

- `String activityOpenId`

- `DataBundle activityOpenMeta`

- `CharWordData m_illustWord`

- `TrackPointViewProperty mailTrackProp`

- `TrackPointViewProperty recruitTrackProp`

- `TrackPointViewProperty charRepoTrackProp`

- `TrackPointViewProperty buildingTrackProp`

- `TrackPointViewProperty missionTrackProp`

- `TrackPointViewProperty friendTrackProp`

- `TrackPointViewProperty openServerTrackProp`

- `TrackPointViewProperty returnTrackProp`

- `TrackPointViewProperty shopTrackProp`

- `TrackPointViewProperty announceTrackProp`

- `TrackPointViewProperty apItemTrackProp`

- `TrackPointViewProperty infoPolyTrackProp`

- `TrackPointViewProperty illustTrackProp`

- `ActivityOnBattleViewProperty actOnBattleProp`

- `Boolean <isOpenServerAvailable>k__BackingField`

- `ReturnningStatus <returnningStatus>k__BackingField`

- `String <validActivityAnnounceStoryId>k__BackingField`

- `String <validNeedPlayStoryId>k__BackingField`


## Properties

- `Boolean isOpenServerAvailable`

- `ReturnningStatus returnningStatus`

- `String validActivityAnnounceStoryId`

- `String validNeedPlayStoryId`


## Methods

- `Boolean get_isOpenServerAvailable()`

- `Void set_isOpenServerAvailable(Boolean)`

- `ReturnningStatus get_returnningStatus()`

- `Void set_returnningStatus(ReturnningStatus)`

- `String get_validActivityAnnounceStoryId()`

- `Void set_validActivityAnnounceStoryId(String)`

- `String get_validNeedPlayStoryId()`

- `Void set_validNeedPlayStoryId(String)`

- `Void LoadData()`

- `Boolean TryLoadRandomIllustText(out)`

- `Void NotifyMailUpdated()`

- `Void OnPlayerDataChanged()`

- `Void UpdateResourceProperty()`

- `Void _SplitUncompleteHomeActs(List`1, List`1, List`1)`

- `Void _FindHomeEntryActivity(List`1, List`1, List`1, List`1)`

- `String FindCurrentValidHomeAct(String)`

- `String _TryFindCurrentValidAprilFoolAct()`

- `Void _FindValidActivityAnnounceStory(out)`

- `Void _FindValidAct17D7Story(out, out)`

- `Void _FindValidActFun(out, out)`

- `Void _FindActivityWithAvg(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMainStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private static ILuaExtension s_luaExt; // 0x0
	private ResourceBarViewProperty _resourceProperty; // 0x18
	public String activityOpenId; // 0x20
	public DataBundle activityOpenMeta; // 0x28
	private CharWordData m_illustWord; // 0x30
	public TrackPointViewProperty mailTrackProp; // 0x38
	public TrackPointViewProperty recruitTrackProp; // 0x40
	public TrackPointViewProperty charRepoTrackProp; // 0x48
	public TrackPointViewProperty buildingTrackProp; // 0x50
	public TrackPointViewProperty missionTrackProp; // 0x58
	public TrackPointViewProperty friendTrackProp; // 0x60
	public TrackPointViewProperty openServerTrackProp; // 0x68
	public TrackPointViewProperty returnTrackProp; // 0x70
	public TrackPointViewProperty shopTrackProp; // 0x78
	public TrackPointViewProperty announceTrackProp; // 0x80
	public TrackPointViewProperty apItemTrackProp; // 0x88
	public TrackPointViewProperty infoPolyTrackProp; // 0x90
	public TrackPointViewProperty illustTrackProp; // 0x98
	public ActivityOnBattleViewProperty actOnBattleProp; // 0xa0
	private Boolean <isOpenServerAvailable>k__BackingField; // 0xa8
	private ReturnningStatus <returnningStatus>k__BackingField; // 0xa9
	private String <validActivityAnnounceStoryId>k__BackingField; // 0xb0
	private String <validNeedPlayStoryId>k__BackingField; // 0xb8
	public List`1 validActWithAvgList; // 0xc0
	private List`1 m_validHomeEntryActs; // 0xc8
	private List`1 m_uncompleteHomeActs; // 0xd0
	public List`1 unfinishedHomeActs; // 0xd8
	public List`1 finishedHomeActs; // 0xe0
	public List`1 popupWithCheckinActs; // 0xe8
	public List`1 popupAfterCheckinActs; // 0xf0
	private List`1 m_validActsCache; // 0xf8
	private List`1 m_uncmpltActsCache; // 0x100
	private List`1 m_unfinishedActsCache; // 0x108
	private List`1 m_finishedActsCache; // 0x110
	private static DelegateBridge __Hotfix0_SetExtension; // 0x8
	private static DelegateBridge __Hotfix0_get_isOpenServerAvailable; // 0x10
	private static DelegateBridge __Hotfix0_set_isOpenServerAvailable; // 0x18
	private static DelegateBridge __Hotfix0_get_returnningStatus; // 0x20
	private static DelegateBridge __Hotfix0_set_returnningStatus; // 0x28
	private static DelegateBridge __Hotfix0_get_validActivityAnnounceStoryId; // 0x30
	private static DelegateBridge __Hotfix0_set_validActivityAnnounceStoryId; // 0x38
	private static DelegateBridge __Hotfix0_get_validNeedPlayStoryId; // 0x40
	private static DelegateBridge __Hotfix0_set_validNeedPlayStoryId; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_TryLoadRandomIllustText; // 0x58
	private static DelegateBridge __Hotfix0_NotifyMailUpdated; // 0x60
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x68
	private static DelegateBridge __Hotfix0_UpdateResourceProperty; // 0x70
	private static DelegateBridge __Hotfix0__SplitUncompleteHomeActs; // 0x78
	private static DelegateBridge __Hotfix0__FindHomeEntryActivity; // 0x80
	private static DelegateBridge __Hotfix0_FindCurrentValidHomeAct; // 0x88
	private static DelegateBridge __Hotfix0__TryFindCurrentValidAprilFoolAct; // 0x90
	private static DelegateBridge __Hotfix0__FindValidActivityAnnounceStory; // 0x98
	private static DelegateBridge __Hotfix0__FindValidAct17D7Story; // 0xa0
	private static DelegateBridge __Hotfix0__FindValidActFun; // 0xa8
	private static DelegateBridge __Hotfix0__FindActivityWithAvg; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public Boolean isOpenServerAvailable { get; set; }
	public ReturnningStatus returnningStatus { get; set; }
	public String validActivityAnnounceStoryId { get; set; }
	public String validNeedPlayStoryId { get; set; }

	// RVA: 0x280f55c VA: 0x7594e2755c
	public static Void SetExtension(ILuaExtension ext) { }
	// RVA: 0x280f5d0 VA: 0x7594e275d0
	public Boolean get_isOpenServerAvailable() { }
	// RVA: 0x280f638 VA: 0x7594e27638
	private Void set_isOpenServerAvailable(Boolean value) { }
	// RVA: 0x280f6b8 VA: 0x7594e276b8
	public ReturnningStatus get_returnningStatus() { }
	// RVA: 0x280f720 VA: 0x7594e27720
	private Void set_returnningStatus(ReturnningStatus value) { }
	// RVA: 0x280f79c VA: 0x7594e2779c
	public String get_validActivityAnnounceStoryId() { }
	// RVA: 0x280f804 VA: 0x7594e27804
	private Void set_validActivityAnnounceStoryId(String value) { }
	// RVA: 0x280f888 VA: 0x7594e27888
	public String get_validNeedPlayStoryId() { }
	// RVA: 0x280f8f0 VA: 0x7594e278f0
	public Void set_validNeedPlayStoryId(String value) { }
	// RVA: 0x280f974 VA: 0x7594e27974
	public Void LoadData() { }
	// RVA: 0x280fb10 VA: 0x7594e27b10
	public Boolean TryLoadRandomIllustText(out CharWordData charWord) { }
	// RVA: 0x280fc54 VA: 0x7594e27c54
	public Void NotifyMailUpdated() { }
	// RVA: 0x280fcc4 VA: 0x7594e27cc4
	public Void OnPlayerDataChanged() { }
	// RVA: 0x280fa30 VA: 0x7594e27a30
	public Void UpdateResourceProperty() { }
	// RVA: 0x2811164 VA: 0x7594e29164
	private Void _SplitUncompleteHomeActs(List`1 uncompleteHomeActs, List`1 popupWithCheckinActs, List`1 popupAfterCheckinActs) { }
	// RVA: 0x28100b0 VA: 0x7594e280b0
	private Void _FindHomeEntryActivity(List`1 outValidActs, List`1 outUncompleteActs, List`1 outUnfinishedActs, List`1 outFinishedActs) { }
	// RVA: 0x281172c VA: 0x7594e2972c
	public String FindCurrentValidHomeAct(String funcActId) { }
	// RVA: 0x2811868 VA: 0x7594e29868
	private String _TryFindCurrentValidAprilFoolAct() { }
	// RVA: 0x281138c VA: 0x7594e2938c
	private Void _FindValidActivityAnnounceStory(out String validStoryId) { }
	// RVA: 0x28119d8 VA: 0x7594e299d8
	private Void _FindValidAct17D7Story(out String actId, out String validStoryId) { }
	// RVA: 0x2811ae0 VA: 0x7594e29ae0
	private Void _FindValidActFun(out String actId, out String validStoryId) { }
	// RVA: 0x2811464 VA: 0x7594e29464
	private Void _FindActivityWithAvg(out List`1 list) { }
	// RVA: 0x2811bf0 VA: 0x7594e29bf0
	public Void .ctor() { }
}
```
# LocalTrackStore

**Namespace:** `Torappu`


## Fields

- `Boolean m_isInited`

- `TrackObserverCenter m_observerCenter`

- `TrackBinderMgr m_binderMgr`

- `Coroutine m_saveCoroutine`

- `Int64 m_saveStartTick`


## Methods

- `Void NotifyPlayerDataChanged(PlayerDataDelta, PlayerDataModel, PlayerDataModel)`

- `Boolean DoTrackTrigger(String, String)`

- `Boolean ConsumeTrack(String, String)`

- `Boolean CheckTrack(String, String)`

- `Boolean ConsumeTracksByType(String)`

- `Boolean CheckTracksByType(String)`

- `Void RemoveTrackVer(String)`

- `Void Dispose()`

- `Void _InitIfNot()`

- `Boolean _DoTrackTrigger(TrackTrigger)`

- `Int64 _GetTrackTypeVersion(String)`

- `Void _NotifyEnteringMainGame()`

- `Void _NotifyCrossDay()`

- `Void _AddTrigger(TrackTrigger)`

- `Data _GetStoreData()`

- `Void _SaveStoreDataImmediately()`

- `Void _SaveStoreDataWithDelay()`

- `IEnumerator _SaveStoreCoroutine()`

- `Void _CancelSaveStoreRequest()`

- `Void BindLocalTrackPoint(TrackPointBinderKey, IBindLocalTrackStore)`

- `Void UnBindLocalTrackPoint(IBindLocalTrackStore)`

- `Boolean _MatchPrefixCondition(String, String, Boolean)`

- `Boolean _MatchSuffixCondition(String, String, Boolean)`

- `Boolean _MatchByTypeRule(String, List`1)`

- `MatchConditionDelegate _GetConditionDelegate(MatchConditionType)`

- `MatchRuleDelegate _GetRuleDelegate(MatchRuleType)`

- `Void _TryMatch(HashSet`1, List`1, List`1)`

- `Boolean ConsumeTracksByMatchRule(MatchRule)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class LocalTrackStore : Singleton`1, IDisposable
{
	private const Int32 SAVE_DELAY_FRAMES; // 0x0
	private const Int64 SAVE_TIMEOUT_TICKS; // 0x0
	private readonly List`1 TRIGGER_HOLDERS; // 0x10
	private Dictionary`2 m_triggerToHolder; // 0x18
	private List`1 m_playerTrackHolders; // 0x20
	private List`1 m_versionTrackHolders; // 0x28
	private Boolean m_isInited; // 0x30
	private TrackObserverCenter m_observerCenter; // 0x38
	private TrackBinderMgr m_binderMgr; // 0x40
	private Coroutine m_saveCoroutine; // 0x48
	private Int64 m_saveStartTick; // 0x50
	private Data`1 m_memData; // 0x58
	private static DelegateBridge __Hotfix0_NotifyPlayerDataChanged; // 0x0
	private static DelegateBridge __Hotfix0_NotifyEnteringMainGame; // 0x8
	private static DelegateBridge __Hotfix0_NotifyCrossDay; // 0x10
	private static DelegateBridge __Hotfix0_DoTrackTrigger; // 0x18
	private static DelegateBridge __Hotfix0_ConsumeTrack; // 0x20
	private static DelegateBridge __Hotfix0_CheckTrack; // 0x28
	private static DelegateBridge __Hotfix0_ConsumeTracksByType; // 0x30
	private static DelegateBridge __Hotfix0_CheckTracksByType; // 0x38
	private static DelegateBridge __Hotfix0_GetTracksByType; // 0x40
	private static DelegateBridge __Hotfix0_RemoveTrackVer; // 0x48
	private static DelegateBridge __Hotfix0_Dispose; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__DoTrackTrigger; // 0x60
	private static DelegateBridge __Hotfix0__GetTrackTypeVersion; // 0x68
	private static DelegateBridge __Hotfix0__NotifyEnteringMainGame; // 0x70
	private static DelegateBridge __Hotfix0__NotifyCrossDay; // 0x78
	private static DelegateBridge __Hotfix0__AddTrigger; // 0x80
	private static DelegateBridge __Hotfix0__BeforeSceneLoadingStart; // 0x88
	private static DelegateBridge __Hotfix0__LockStoreDataWrite; // 0x90
	private static DelegateBridge __Hotfix0__GetStoreData; // 0x98
	private static DelegateBridge __Hotfix0__SaveStoreDataImmediately; // 0xa0
	private static DelegateBridge __Hotfix0__SaveStoreDataWithDelay; // 0xa8
	private static DelegateBridge __Hotfix0__SaveStoreCoroutine; // 0xb0
	private static DelegateBridge __Hotfix0__CancelSaveStoreRequest; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0
	private static DelegateBridge __Hotfix0_BindLocalTrackPoint; // 0xc8
	private static DelegateBridge __Hotfix0_UnBindLocalTrackPoint; // 0xd0
	private static DelegateBridge __Hotfix0__MatchPrefixCondition; // 0xd8
	private static DelegateBridge __Hotfix0__MatchSuffixCondition; // 0xe0
	private static DelegateBridge __Hotfix0__MatchByTypeRule; // 0xe8
	private static DelegateBridge __Hotfix0__GetConditionDelegate; // 0xf0
	private static DelegateBridge __Hotfix0__GetRuleDelegate; // 0xf8
	private static DelegateBridge __Hotfix0__TryMatch; // 0x100
	private static DelegateBridge __Hotfix0_ConsumeTracksByMatchRule; // 0x108


	// RVA: 0x2f36fc4 VA: 0x759554efc4
	public Void NotifyPlayerDataChanged(PlayerDataDelta delta, PlayerDataModel prevData, PlayerDataModel curData) { }
	// RVA: 0x2f3759c VA: 0x759554f59c
	public static Void NotifyEnteringMainGame() { }
	// RVA: 0x2f37694 VA: 0x759554f694
	public static Void NotifyCrossDay() { }
	// RVA: 0x2f37874 VA: 0x759554f874
	public Boolean DoTrackTrigger(String type, String id) { }
	// RVA: 0x2f37e48 VA: 0x759554fe48
	public Boolean ConsumeTrack(String type, String id) { }
	// RVA: 0x2f38040 VA: 0x7595550040
	public Boolean CheckTrack(String type, String id) { }
	// RVA: 0x2f381d0 VA: 0x75955501d0
	public Boolean ConsumeTracksByType(String type) { }
	// RVA: 0x2f383c0 VA: 0x75955503c0
	public Boolean CheckTracksByType(String type) { }
	// RVA: 0x2f3852c VA: 0x759555052c
	public IEnumerator`1 GetTracksByType(String type) { }
	// RVA: 0x2f38624 VA: 0x7595550624
	public Void RemoveTrackVer(String type) { }
	// RVA: 0x2f38700 VA: 0x7595550700
	public Void Dispose() { }
	// RVA: 0x2f37188 VA: 0x759554f188
	private Void _InitIfNot() { }
	// RVA: 0x2f38910 VA: 0x7595550910
	private Boolean _DoTrackTrigger(TrackTrigger trigger) { }
	// RVA: 0x2f38c8c VA: 0x7595550c8c
	private Int64 _GetTrackTypeVersion(String type) { }
	// RVA: 0x2f38d48 VA: 0x7595550d48
	private Void _NotifyEnteringMainGame() { }
	// RVA: 0x2f3771c VA: 0x759554f71c
	private Void _NotifyCrossDay() { }
	// RVA: 0x2f38e9c VA: 0x7595550e9c
	private Void _AddTrigger(TrackTrigger trigger) { }
	// RVA: 0x2f38fdc VA: 0x7595550fdc
	private static Void _BeforeSceneLoadingStart(String fromScene, String toScene) { }
	// RVA: 0x2f39138 VA: 0x7595551138
	private static IDisposable _LockStoreDataWrite() { }
	// RVA: 0x2f37924 VA: 0x759554f924
	private Data _GetStoreData() { }
	// RVA: 0x2f3926c VA: 0x759555126c
	private Void _SaveStoreDataImmediately() { }
	// RVA: 0x2f37c4c VA: 0x759554fc4c
	private Void _SaveStoreDataWithDelay() { }
	// RVA: 0x2f39394 VA: 0x7595551394
	private IEnumerator _SaveStoreCoroutine() { }
	// RVA: 0x2f38768 VA: 0x7595550768
	private Void _CancelSaveStoreRequest() { }
	// RVA: 0x2f39468 VA: 0x7595551468
	private Void .ctor() { }
	// RVA: 0x2f3a1c4 VA: 0x75955521c4
	public Void BindLocalTrackPoint(TrackPointBinderKey binderKey, IBindLocalTrackStore binder) { }
	// RVA: 0x2f3a4cc VA: 0x75955524cc
	public Void UnBindLocalTrackPoint(IBindLocalTrackStore trackPoint) { }
	// RVA: 0x2f3a650 VA: 0x7595552650
	private Boolean _MatchPrefixCondition(String trackId, String conditionPattern, Boolean exclude) { }
	// RVA: 0x2f3a708 VA: 0x7595552708
	private Boolean _MatchSuffixCondition(String trackId, String conditionPattern, Boolean exclude) { }
	// RVA: 0x2f3a7c0 VA: 0x75955527c0
	private Boolean _MatchByTypeRule(String rulePattern, List`1 conditions) { }
	// RVA: 0x2f3af68 VA: 0x7595552f68
	private MatchConditionDelegate _GetConditionDelegate(MatchConditionType conditionType) { }
	// RVA: 0x2f3b1d4 VA: 0x75955531d4
	private MatchRuleDelegate _GetRuleDelegate(MatchRuleType ruleType) { }
	// RVA: 0x2f3a9b4 VA: 0x75955529b4
	private Void _TryMatch(HashSet`1 tracks, List`1 conditions, List`1 matchedRes) { }
	// RVA: 0x2f3b4ac VA: 0x75955534ac
	public Boolean ConsumeTracksByMatchRule(MatchRule rule) { }
}
```
# StageZoneState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageStateBean _stateBean`

- `StageZoneMapContainer _zoneMapContainer`

- `StageMainZoneMapContainer _mainZoneMapContainer`

- `UIAnimationLocation _switchZoneOut`

- `UIAnimationLocation _switchZoneIn`

- `GameObject _switchAnimTarget`

- `GameObject _guideBookMainline`

- `GameObject _guideBookCampaign`

- `StagePageGameMusicController m_musicController`

- `Boolean m_mapLoadedCache`

- `Boolean m_switchZoneLock`


## Methods

- `Int64 _GetBGMInstId()`

- `Void _RefreshBGM()`

- `Void _ClearBGM()`

- `String _FindMusicId()`

- `Void EventOnSwitchMainline(String)`

- `Void EventOnOpenDetailInfo()`

- `Void EventOnPlayRecap()`

- `Void _OnSwitchSelectStateEnd()`

- `StateRuntime _SaveToRuntime()`

- `Void _LoadFromRuntime(StateRuntime)`

- `Boolean SwitchToZone(String)`

- `Void SwitchToDiff(StageDiffGroup)`

- `Boolean _LockSwitchZone()`

- `Void _UnlockSwitchZone()`

- `IEnumerator _SwitchSelectStateCoroutine(String, StageDiffGroup)`

- `Void _NotifyZoneLoadedForGuideBook(String)`

- `Void _TriggerRecap(String)`

- `Void <RegisterToDataListener>b__15_0(IStateBean)`

- `Void <RegisterFromDataListener>b__17_0(IStateBean)`

- `Void <EventOnSwitchMainline>b__25_0(String)`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnMapLoadError(String)`

- `Void <>xLuaBaseProxy_OnMapLoadFinish(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneState : StageTabBaseState
{
	private const Single SWITCH_ZONE_TIME_OUT; // 0x0
	private StageStateBean _stateBean; // 0x58
	private StageZoneMapContainer _zoneMapContainer; // 0x60
	private StageMainZoneMapContainer _mainZoneMapContainer; // 0x68
	private UIAnimationLocation _switchZoneOut; // 0x70
	private UIAnimationLocation _switchZoneIn; // 0x80
	private GameObject _switchAnimTarget; // 0x90
	private GameObject _guideBookMainline; // 0x98
	private GameObject _guideBookCampaign; // 0xa0
	private StateCacheHandler`1 m_runtimeHandler; // 0xa8
	private StagePageGameMusicController m_musicController; // 0xb0
	private Boolean m_mapLoadedCache; // 0xb8
	private Boolean m_switchZoneLock; // 0xb9
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x18
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnResume; // 0x30
	private static DelegateBridge __Hotfix0_OnExit; // 0x38
	private static DelegateBridge __Hotfix0__GetBGMInstId; // 0x40
	private static DelegateBridge __Hotfix0__RefreshBGM; // 0x48
	private static DelegateBridge __Hotfix0__ClearBGM; // 0x50
	private static DelegateBridge __Hotfix0__FindMusicId; // 0x58
	private static DelegateBridge __Hotfix0_EventOnSwitchMainline; // 0x60
	private static DelegateBridge __Hotfix0_EventOnOpenDetailInfo; // 0x68
	private static DelegateBridge __Hotfix0_EventOnPlayRecap; // 0x70
	private static DelegateBridge __Hotfix0_OnMapLoadError; // 0x78
	private static DelegateBridge __Hotfix0_OnMapLoadFinish; // 0x80
	private static DelegateBridge __Hotfix0__OnSwitchSelectStateEnd; // 0x88
	private static DelegateBridge __Hotfix0__SaveToRuntime; // 0x90
	private static DelegateBridge __Hotfix0__LoadFromRuntime; // 0x98
	private static DelegateBridge __Hotfix0_SwitchToZone; // 0xa0
	private static DelegateBridge __Hotfix0_SwitchToDiff; // 0xa8
	private static DelegateBridge __Hotfix0__LockSwitchZone; // 0xb0
	private static DelegateBridge __Hotfix0__UnlockSwitchZone; // 0xb8
	private static DelegateBridge __Hotfix0__SwitchSelectStateCoroutine; // 0xc0
	private static DelegateBridge __Hotfix0__NotifyZoneLoadedForGuideBook; // 0xc8
	private static DelegateBridge __Hotfix0__TriggerRecap; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x2f72ea0 VA: 0x759558aea0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f72f08 VA: 0x759558af08
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x2f7308c VA: 0x759558b08c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2f73204 VA: 0x759558b204
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2f7327c VA: 0x759558b27c
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2f733f4 VA: 0x759558b3f4
	protected override Void OnEnter() { }
	// RVA: 0x2f7359c VA: 0x759558b59c
	protected override Void OnResume() { }
	// RVA: 0x2f73774 VA: 0x759558b774
	protected override Void OnExit() { }
	// RVA: 0x2f738a8 VA: 0x759558b8a8
	private Int64 _GetBGMInstId() { }
	// RVA: 0x2f734f8 VA: 0x759558b4f8
	private Void _RefreshBGM() { }
	// RVA: 0x2f73820 VA: 0x759558b820
	private Void _ClearBGM() { }
	// RVA: 0x2f7391c VA: 0x759558b91c
	private String _FindMusicId() { }
	// RVA: 0x2f73a78 VA: 0x759558ba78
	public Void EventOnSwitchMainline(String zoneId) { }
	// RVA: 0x2f73ce8 VA: 0x759558bce8
	public Void EventOnOpenDetailInfo() { }
	// RVA: 0x2f73e4c VA: 0x759558be4c
	public Void EventOnPlayRecap() { }
	// RVA: 0x2f73fcc VA: 0x759558bfcc
	public override Void OnMapLoadError(String zoneId) { }
	// RVA: 0x2f74058 VA: 0x759558c058
	public override Void OnMapLoadFinish(String zoneId) { }
	// RVA: 0x2f740ec VA: 0x759558c0ec
	private Void _OnSwitchSelectStateEnd() { }
	// RVA: 0x2f74150 VA: 0x759558c150
	private StateRuntime _SaveToRuntime() { }
	// RVA: 0x2f74228 VA: 0x759558c228
	private Void _LoadFromRuntime(StateRuntime runtime) { }
	// RVA: 0x2f73c38 VA: 0x759558bc38
	public Boolean SwitchToZone(String zoneId) { }
	// RVA: 0x2f74420 VA: 0x759558c420
	public Void SwitchToDiff(StageDiffGroup diffGroup) { }
	// RVA: 0x2f742c8 VA: 0x759558c2c8
	private Boolean _LockSwitchZone() { }
	// RVA: 0x2f744e4 VA: 0x759558c4e4
	private Void _UnlockSwitchZone() { }
	// RVA: 0x2f74344 VA: 0x759558c344
	private IEnumerator _SwitchSelectStateCoroutine(String targetZoneId, StageDiffGroup targetDiff) { }
	// RVA: 0x2f73684 VA: 0x759558b684
	private Void _NotifyZoneLoadedForGuideBook(String zoneId) { }
	// RVA: 0x2f7454c VA: 0x759558c54c
	private Void _TriggerRecap(String zoneId) { }
	// RVA: 0x2f746c8 VA: 0x759558c6c8
	public Void .ctor() { }
	// RVA: 0x2f74734 VA: 0x759558c734
	private Void <RegisterToDataListener>b__15_0(IStateBean stateBean) { }
	// RVA: 0x2f747f8 VA: 0x759558c7f8
	private Void <RegisterFromDataListener>b__17_0(IStateBean statebean) { }
	// RVA: 0x2f74878 VA: 0x759558c878
	private Void <EventOnSwitchMainline>b__25_0(String _) { }
	// RVA: 0x2f7487c VA: 0x759558c87c
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
	// RVA: 0x2f74884 VA: 0x759558c884
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2f7488c VA: 0x759558c88c
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2f74894 VA: 0x759558c894
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x2f7489c VA: 0x759558c89c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2f748a4 VA: 0x759558c8a4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2f748a8 VA: 0x759558c8a8
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2f748b0 VA: 0x759558c8b0
	private Void <>xLuaBaseProxy_OnMapLoadError(String P0) { }
	// RVA: 0x2f748b4 VA: 0x759558c8b4
	private Void <>xLuaBaseProxy_OnMapLoadFinish(String P0) { }
}
```
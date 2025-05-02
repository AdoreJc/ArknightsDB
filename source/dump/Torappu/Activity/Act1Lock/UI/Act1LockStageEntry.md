# Act1LockStageEntry

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `RectTransform _topMenuContainer`

- `AnimationWrapper _animWrapper`

- `Act1LockMainView _mainView`

- `UICommonTrackPoint _milestoneTrack`

- `UICommonTrackPoint _missionTrack`

- `Boolean m_hasInited`


## Methods

- `Void OnDisable()`

- `Void _InifIfNot()`

- `Void _TriggerInterlockAVG()`

- `Void _OnSysAvgFinish(Story)`

- `Boolean _TryTrigSeasonAVG()`

- `Void <>xLuaBaseProxy_OnLoaded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockStageEntry : ActivityStageSingleComponent
{
	private RectTransform _topMenuContainer; // 0x20
	private AnimationWrapper _animWrapper; // 0x28
	private Act1LockMainView _mainView; // 0x30
	private UICommonTrackPoint _milestoneTrack; // 0x38
	private UICommonTrackPoint _missionTrack; // 0x40
	private const String START_ANIM_NAME; // 0x0
	private Boolean m_hasInited; // 0x48
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0_OnDisable; // 0x8
	private static DelegateBridge __Hotfix0__InifIfNot; // 0x10
	private static DelegateBridge __Hotfix0__TriggerInterlockAVG; // 0x18
	private static DelegateBridge __Hotfix0__OnSysAvgFinish; // 0x20
	private static DelegateBridge __Hotfix0__TryTrigSeasonAVG; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x339bf84 VA: 0x75959b3f84
	protected override Void OnLoaded() { }
	// RVA: 0x339c494 VA: 0x75959b4494
	private Void OnDisable() { }
	// RVA: 0x339c234 VA: 0x75959b4234
	private Void _InifIfNot() { }
	// RVA: 0x339c380 VA: 0x75959b4380
	private Void _TriggerInterlockAVG() { }
	// RVA: 0x339c6a0 VA: 0x75959b46a0
	private Void _OnSysAvgFinish(Story story) { }
	// RVA: 0x339c520 VA: 0x75959b4520
	private Boolean _TryTrigSeasonAVG() { }
	// RVA: 0x339c75c VA: 0x75959b475c
	public Void .ctor() { }
	// RVA: 0x339c7cc VA: 0x75959b47cc
	private Void <>xLuaBaseProxy_OnLoaded() { }
}
```
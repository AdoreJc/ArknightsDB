# Act12sideStageEntry

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `RectTransform _topMenuContainer`

- `Act12sideEntryView _view`

- `Act12sideEntryZoneGroupView _zoneGroupView`

- `UICommonTrackPoint _milestoneTrackPoint`

- `UICommonTrackPoint _charmRecycleTrackPoint`

- `UICommonTrackPoint _charmFirstGotTrackPoint`

- `UICommonTrackPoint _honorShowcaseTrackPoint`

- `ActivityEntryAnimManager _entryAnimManager`

- `ActivityCommonFavorUpEntryView _favorUpView`

- `Boolean m_hasInited`

- `IActAnimContext m_enterAnimContext`

- `IActAnimContext m_loopAnimContext`


## Methods

- `Void OnBtnReplicateClick()`

- `Void OnBtnMilestoneClick()`

- `Void OnBtnCharmRepo()`

- `Void OnBtnMedalClick()`

- `Void OnBtnShopClick()`

- `Void OnBtnFavorUpClick()`

- `Void _AddTopToActStateEngine()`

- `Void _InitIfNot()`

- `Void <OnLoaded>b__13_0()`

- `Void <>xLuaBaseProxy_OnLoaded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideStageEntry : ActivityStageSingleComponent
{
	private RectTransform _topMenuContainer; // 0x20
	private Act12sideEntryView _view; // 0x28
	private Act12sideEntryZoneGroupView _zoneGroupView; // 0x30
	private UICommonTrackPoint _milestoneTrackPoint; // 0x38
	private UICommonTrackPoint _charmRecycleTrackPoint; // 0x40
	private UICommonTrackPoint _charmFirstGotTrackPoint; // 0x48
	private UICommonTrackPoint _honorShowcaseTrackPoint; // 0x50
	private ActivityEntryAnimManager _entryAnimManager; // 0x58
	private ActivityCommonFavorUpEntryView _favorUpView; // 0x60
	private Boolean m_hasInited; // 0x68
	private IActAnimContext m_enterAnimContext; // 0x70
	private IActAnimContext m_loopAnimContext; // 0x78
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0_OnBtnReplicateClick; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnMilestoneClick; // 0x10
	private static DelegateBridge __Hotfix0_OnBtnCharmRepo; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnMedalClick; // 0x20
	private static DelegateBridge __Hotfix0_OnBtnShopClick; // 0x28
	private static DelegateBridge __Hotfix0_OnBtnFavorUpClick; // 0x30
	private static DelegateBridge __Hotfix0__AddTopToActStateEngine; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x344ec7c VA: 0x7595a66c7c
	protected override Void OnLoaded() { }
	// RVA: 0x344f174 VA: 0x7595a67174
	public Void OnBtnReplicateClick() { }
	// RVA: 0x344f1f4 VA: 0x7595a671f4
	public Void OnBtnMilestoneClick() { }
	// RVA: 0x344f274 VA: 0x7595a67274
	public Void OnBtnCharmRepo() { }
	// RVA: 0x344f2f4 VA: 0x7595a672f4
	public Void OnBtnMedalClick() { }
	// RVA: 0x344f374 VA: 0x7595a67374
	public Void OnBtnShopClick() { }
	// RVA: 0x344f4e8 VA: 0x7595a674e8
	public Void OnBtnFavorUpClick() { }
	// RVA: 0x VA: 0x0
	private Void _AddTopToActStateEngine() { }
	// RVA: 0x344ed68 VA: 0x7595a66d68
	private Void _InitIfNot() { }
	// RVA: 0x344f598 VA: 0x7595a67598
	public Void .ctor() { }
	// RVA: 0x344f608 VA: 0x7595a67608
	private Void <OnLoaded>b__13_0() { }
	// RVA: 0x344f62c VA: 0x7595a6762c
	private Void <>xLuaBaseProxy_OnLoaded() { }
}
```
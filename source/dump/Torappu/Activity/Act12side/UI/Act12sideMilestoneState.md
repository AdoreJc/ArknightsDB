# Act12sideMilestoneState

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Act12sideMilestoneView _view`

- `UICommonTrackPoint _missionTrackPoint`

- `PhotoInfo m_bufferedPhotoInfo`


## Methods

- `Void _OnJumpToPhotoState(IStateBean)`

- `Void _OnPhotoClick(PhotoInfo)`

- `Void _OnMilestoneClick(String)`

- `Void _OnRewardAllMilestoneClick()`

- `Void _OnRewardMilestoneSuc(ActivityRewardMilestoneResponse)`

- `Void _OnRewardAllMilestoneSuc(ActivityRewardAllMilestoneResponse)`

- `Void _RefreshMilestoneStatus()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void OnBtnMissionClick()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMilestoneState : Act12sideGenericState
{
	private Act12sideMilestoneView _view; // 0x88
	private UICommonTrackPoint _missionTrackPoint; // 0x90
	private PhotoInfo m_bufferedPhotoInfo; // 0x98
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToPhotoState; // 0x28
	private static DelegateBridge __Hotfix0__OnPhotoClick; // 0x30
	private static DelegateBridge __Hotfix0__OnMilestoneClick; // 0x38
	private static DelegateBridge __Hotfix0__OnRewardAllMilestoneClick; // 0x40
	private static DelegateBridge __Hotfix0__OnRewardMilestoneSuc; // 0x48
	private static DelegateBridge __Hotfix0__OnRewardAllMilestoneSuc; // 0x50
	private static DelegateBridge __Hotfix0__RefreshMilestoneStatus; // 0x58
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x60
	private static DelegateBridge __Hotfix0_OnBtnMissionClick; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x345d9dc VA: 0x7595a759dc
	protected override Void OnEnter() { }
	// RVA: 0x345db08 VA: 0x7595a75b08
	protected override Void OnResume() { }
	// RVA: 0x345dd20 VA: 0x7595a75d20
	protected override Void InitIfNot() { }
	// RVA: 0x345e19c VA: 0x7595a7619c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x345e200 VA: 0x7595a76200
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x345e378 VA: 0x7595a76378
	private Void _OnJumpToPhotoState(IStateBean stateBean) { }
	// RVA: 0x345e474 VA: 0x7595a76474
	private Void _OnPhotoClick(PhotoInfo photoInfo) { }
	// RVA: 0x345e5a0 VA: 0x7595a765a0
	private Void _OnMilestoneClick(String milestoneId) { }
	// RVA: 0x345e7e8 VA: 0x7595a767e8
	private Void _OnRewardAllMilestoneClick() { }
	// RVA: 0x345ea90 VA: 0x7595a76a90
	private Void _OnRewardMilestoneSuc(ActivityRewardMilestoneResponse response) { }
	// RVA: 0x345ed18 VA: 0x7595a76d18
	private Void _OnRewardAllMilestoneSuc(ActivityRewardAllMilestoneResponse response) { }
	// RVA: 0x345eb30 VA: 0x7595a76b30
	private Void _RefreshMilestoneStatus() { }
	// RVA: 0x345ec58 VA: 0x7595a76c58
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x345ede0 VA: 0x7595a76de0
	public Void OnBtnMissionClick() { }
	// RVA: 0x345eee8 VA: 0x7595a76ee8
	public Void .ctor() { }
	// RVA: 0x345ef54 VA: 0x7595a76f54
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x345ef58 VA: 0x7595a76f58
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x345ef60 VA: 0x7595a76f60
	private Void <>xLuaBaseProxy_InitIfNot() { }
	// RVA: 0x345ef64 VA: 0x7595a76f64
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```
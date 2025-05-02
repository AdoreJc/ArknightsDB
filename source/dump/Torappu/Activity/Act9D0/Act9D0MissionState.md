# Act9D0MissionState

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Act9D0MissionBaseView _view`

- `Act9D0CoinView _coinView`

- `RectTransform _topMenuContainer`

- `Act9D0MissionStateBean m_stateBean`

- `CommonTopMenu m_topMenu`

- `Boolean m_inited`


## Methods

- `Void _RefreshView()`

- `Void EventOnMissionClaimAllClicked()`

- `Void EventOnMissionObjClicked(String)`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void _InitIfNot()`

- `Void <EventOnMissionClaimAllClicked>b__9_0(ActivityMissionCheckResponse)`

- `Void <EventOnMissionObjClicked>b__10_0(ActivityConfirmMissionResponse)`

- `Void <_InitIfNot>b__12_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0MissionState : PopupFloatState
{
	private Act9D0MissionBaseView _view; // 0x70
	private Act9D0CoinView _coinView; // 0x78
	private RectTransform _topMenuContainer; // 0x80
	private Act9D0MissionStateBean m_stateBean; // 0x88
	private CommonTopMenu m_topMenu; // 0x90
	private Boolean m_inited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__RefreshView; // 0x10
	private static DelegateBridge __Hotfix0_EventOnMissionClaimAllClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnMissionObjClicked; // 0x20
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x31a00d8 VA: 0x75957b80d8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31a0140 VA: 0x75957b8140
	protected override Void OnEnter() { }
	// RVA: 0x31a02a8 VA: 0x75957b82a8
	private Void _RefreshView() { }
	// RVA: 0x31a0334 VA: 0x75957b8334
	public Void EventOnMissionClaimAllClicked() { }
	// RVA: 0x31a06b8 VA: 0x75957b86b8
	public Void EventOnMissionObjClicked(String missionId) { }
	// RVA: 0x31a08ec VA: 0x75957b88ec
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x31a01bc VA: 0x75957b81bc
	private Void _InitIfNot() { }
	// RVA: 0x31a09d4 VA: 0x75957b89d4
	public Void .ctor() { }
	// RVA: 0x31a0a84 VA: 0x75957b8a84
	private Void <EventOnMissionClaimAllClicked>b__9_0(ActivityMissionCheckResponse response) { }
	// RVA: 0x31a0bd0 VA: 0x75957b8bd0
	private Void <EventOnMissionObjClicked>b__10_0(ActivityConfirmMissionResponse response) { }
	// RVA: 0x31a0d1c VA: 0x75957b8d1c
	private Void <_InitIfNot>b__12_0() { }
	// RVA: 0x31a0d24 VA: 0x75957b8d24
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
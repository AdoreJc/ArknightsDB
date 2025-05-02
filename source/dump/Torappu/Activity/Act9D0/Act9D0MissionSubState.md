# Act9D0MissionSubState

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Act9D0MissionStateBean m_stateBean`

- `Act9D0MissionSubView _view`

- `Act9D0SubMissionView _subView`

- `RectTransform _topMenuContainer`

- `CommonTopMenu m_topMenu`

- `Boolean m_inited`

- `String m_cacheId`


## Methods

- `Void EventOnMissionObjClicked(String)`

- `Void OpenDetail(String)`

- `Void _InitIfNot()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void <EventOnMissionObjClicked>b__8_0(ActivityConfirmMissionResponse)`

- `Void <RegisterToDataListener>b__10_0(IStateBean)`

- `Void <_InitIfNot>b__11_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0MissionSubState : PopupFadeState
{
	private Act9D0MissionStateBean m_stateBean; // 0x70
	private Act9D0MissionSubView _view; // 0x78
	private Act9D0SubMissionView _subView; // 0x80
	private RectTransform _topMenuContainer; // 0x88
	private CommonTopMenu m_topMenu; // 0x90
	private Boolean m_inited; // 0x98
	private String m_cacheId; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_EventOnMissionObjClicked; // 0x8
	private static DelegateBridge __Hotfix0_OpenDetail; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnResume; // 0x30
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x31a0e5c VA: 0x75957b8e5c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31a0ec4 VA: 0x75957b8ec4
	public Void EventOnMissionObjClicked(String missionId) { }
	// RVA: 0x31a10f4 VA: 0x75957b90f4
	public Void OpenDetail(String missionId) { }
	// RVA: 0x31a1224 VA: 0x75957b9224
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x31a139c VA: 0x75957b939c
	private Void _InitIfNot() { }
	// RVA: 0x31a147c VA: 0x75957b947c
	protected override Void OnEnter() { }
	// RVA: 0x31a1554 VA: 0x75957b9554
	protected override Void OnResume() { }
	// RVA: 0x31a1640 VA: 0x75957b9640
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x31a1728 VA: 0x75957b9728
	public Void .ctor() { }
	// RVA: 0x31a17d8 VA: 0x75957b97d8
	private Void <EventOnMissionObjClicked>b__8_0(ActivityConfirmMissionResponse response) { }
	// RVA: 0x31a1924 VA: 0x75957b9924
	private Void <RegisterToDataListener>b__10_0(IStateBean stateBean) { }
	// RVA: 0x31a1a6c VA: 0x75957b9a6c
	private Void <_InitIfNot>b__11_0() { }
	// RVA: 0x31a1a74 VA: 0x75957b9a74
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x31a1a7c VA: 0x75957b9a7c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x31a1a84 VA: 0x75957b9a84
	private Void <>xLuaBaseProxy_OnResume() { }
}
```
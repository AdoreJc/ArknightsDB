# Act9D0SubMissionDetailState

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Act9D0SubMissionDetailView _detailView`

- `Act9D0SubMissionStateBean m_stateBean`

- `Boolean m_isMissionConfirmSent`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnMissionObjClicked()`

- `Boolean _CheckIfAbleToFinishTask()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void <EventOnMissionObjClicked>b__7_0(ActivityConfirmMissionResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0SubMissionDetailState : PopupFloatState
{
	private Act9D0SubMissionDetailView _detailView; // 0x70
	private Act9D0SubMissionStateBean m_stateBean; // 0x78
	private Boolean m_isMissionConfirmSent; // 0x80
	private Boolean m_isInited; // 0x81
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_EventOnMissionObjClicked; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfAbleToFinishTask; // 0x20
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31a26b4 VA: 0x75957ba6b4
	private Void _InitIfNot() { }
	// RVA: 0x31a27b4 VA: 0x75957ba7b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31a281c VA: 0x75957ba81c
	protected override Void OnEnter() { }
	// RVA: 0x31a28b8 VA: 0x75957ba8b8
	public Void EventOnMissionObjClicked() { }
	// RVA: 0x31a2b04 VA: 0x75957bab04
	private Boolean _CheckIfAbleToFinishTask() { }
	// RVA: 0x31a2c24 VA: 0x75957bac24
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x31a2d1c VA: 0x75957bad1c
	public Void .ctor() { }
	// RVA: 0x31a2dcc VA: 0x75957badcc
	private Void <EventOnMissionObjClicked>b__7_0(ActivityConfirmMissionResponse response) { }
	// RVA: 0x31a2ee8 VA: 0x75957baee8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
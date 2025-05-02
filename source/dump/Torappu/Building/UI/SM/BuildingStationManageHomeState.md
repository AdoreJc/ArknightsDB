# BuildingStationManageHomeState

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `BuildingStationManageView _view`

- `TopMenuDynamicPrefabInstHolder _topMenuHodler`

- `StationHomeStateBean m_stateBean`

- `RoomSlotModel m_curEditSlotModel`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnJumpToEditQueueState(StationManageEditQueueStateBean)`

- `Void OnEnterDormEditLockClicked()`

- `Void OnClearDormEditLockClicked()`

- `Void OnConfirmDormEditLockClicked()`

- `Void _OnRoomClicked(StationRoomStructModel)`

- `Void _OnPlayerDataChanged()`

- `Void _OnUseQueueClicked(StationRoomStructModel)`

- `Void _OnEditQueueClicked(StationRoomStructModel)`

- `Void _OnSwitchModeClicked()`

- `Void _OnBatchWork()`

- `Void _OnCannotBatchWork()`

- `Void _OnBatchRest()`

- `Void _OnCannotBatchRest()`

- `Void _OnEditDormLock(EditLockInfo)`

- `Void _SendSaveDormLockRequest(Dictionary`2)`

- `Void _OnBackBtnClicked()`

- `Void <RegisterToDataListener>b__16_0(IStateBean)`

- `Void <OnEnter>b__18_0(GameObject)`

- `Void <OnEnter>b__18_1()`

- `Void <_SendSaveDormLockRequest>b__33_0(BuildingSaveDormLockResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingStationManageHomeState : State, IValueMsgReceiver
{
	private BuildingStationManageView _view; // 0x50
	private TopMenuDynamicPrefabInstHolder _topMenuHodler; // 0x58
	public const Int32 MSG_ROOM_CLICK; // 0x0
	public const Int32 MSG_USE_QUEUE_CLICK; // 0x0
	public const Int32 MSG_EDIT_QUEUE_CLICK; // 0x0
	public const Int32 MSG_BATCH_WORK_CLICK; // 0x0
	public const Int32 MSG_BATCH_WORK_INACTIVE_CLICK; // 0x0
	public const Int32 MSG_BATCH_REST_CLICK; // 0x0
	public const Int32 MSG_BATCH_REST_INACTIVE_CLICK; // 0x0
	public const Int32 MSG_USE_QUEUE_NOT_AVAIL_CLICK; // 0x0
	public const Int32 MSG_ON_CHAR_ANIM; // 0x0
	public const Int32 MSG_ON_EDIT_DORM_LOCK; // 0x0
	private StationHomeStateBean m_stateBean; // 0x60
	private RoomSlotModel m_curEditSlotModel; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0__OnJumpToEditQueueState; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge __Hotfix0_OnEnterDormEditLockClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnClearDormEditLockClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnConfirmDormEditLockClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnRoomClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x50
	private static DelegateBridge __Hotfix0__OnUseQueueClicked; // 0x58
	private static DelegateBridge __Hotfix0__OnEditQueueClicked; // 0x60
	private static DelegateBridge __Hotfix0__OnSwitchModeClicked; // 0x68
	private static DelegateBridge __Hotfix0__OnBatchWork; // 0x70
	private static DelegateBridge __Hotfix0__OnCannotBatchWork; // 0x78
	private static DelegateBridge __Hotfix0__OnBatchRest; // 0x80
	private static DelegateBridge __Hotfix0__OnCannotBatchRest; // 0x88
	private static DelegateBridge __Hotfix0__OnEditDormLock; // 0x90
	private static DelegateBridge __Hotfix0__SendSaveDormLockRequest; // 0x98
	private static DelegateBridge __Hotfix0__OnBackBtnClicked; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x3daa7cc VA: 0x75963c27cc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3daa834 VA: 0x75963c2834
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3dab42c VA: 0x75963c342c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3dab5a4 VA: 0x75963c35a4
	private Void _OnJumpToEditQueueState(StationManageEditQueueStateBean stateBean) { }
	// RVA: 0x3dab654 VA: 0x75963c3654
	protected override Void OnEnter() { }
	// RVA: 0x3dab97c VA: 0x75963c397c
	protected override Void OnResume() { }
	// RVA: 0x3daba54 VA: 0x75963c3a54
	public Void OnEnterDormEditLockClicked() { }
	// RVA: 0x3dabb50 VA: 0x75963c3b50
	public Void OnClearDormEditLockClicked() { }
	// RVA: 0x3dabbf0 VA: 0x75963c3bf0
	public Void OnConfirmDormEditLockClicked() { }
	// RVA: 0x3daab28 VA: 0x75963c2b28
	private Void _OnRoomClicked(StationRoomStructModel target) { }
	// RVA: 0x3dabeb8 VA: 0x75963c3eb8
	private Void _OnPlayerDataChanged() { }
	// RVA: 0x3daac1c VA: 0x75963c2c1c
	private Void _OnUseQueueClicked(StationRoomStructModel target) { }
	// RVA: 0x3daacd8 VA: 0x75963c2cd8
	private Void _OnEditQueueClicked(StationRoomStructModel target) { }
	// RVA: 0x3dabf58 VA: 0x75963c3f58
	private Void _OnSwitchModeClicked() { }
	// RVA: 0x3daaed0 VA: 0x75963c2ed0
	private Void _OnBatchWork() { }
	// RVA: 0x3daaf34 VA: 0x75963c2f34
	private Void _OnCannotBatchWork() { }
	// RVA: 0x3dab0e4 VA: 0x75963c30e4
	private Void _OnBatchRest() { }
	// RVA: 0x3dab148 VA: 0x75963c3148
	private Void _OnCannotBatchRest() { }
	// RVA: 0x3dab2b8 VA: 0x75963c32b8
	private Void _OnEditDormLock(EditLockInfo editLockInfo) { }
	// RVA: 0x3dabde8 VA: 0x75963c3de8
	private Void _SendSaveDormLockRequest(Dictionary`2 lockData) { }
	// RVA: 0x3dabfc8 VA: 0x75963c3fc8
	private Void _OnBackBtnClicked() { }
	// RVA: 0x3dac0c4 VA: 0x75963c40c4
	public Void .ctor() { }
	// RVA: 0x3dac170 VA: 0x75963c4170
	private Void <RegisterToDataListener>b__16_0(IStateBean stateBean) { }
	// RVA: 0x3dac1f0 VA: 0x75963c41f0
	private Void <OnEnter>b__18_0(GameObject obj) { }
	// RVA: 0x3dac2b4 VA: 0x75963c42b4
	private Void <OnEnter>b__18_1() { }
	// RVA: 0x3dac2b8 VA: 0x75963c42b8
	private Void <_SendSaveDormLockRequest>b__33_0(BuildingSaveDormLockResponse _) { }
	// RVA: 0x3dac324 VA: 0x75963c4324
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3dac32c VA: 0x75963c432c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3dac334 VA: 0x75963c4334
	private Void <>xLuaBaseProxy_OnResume() { }
}
```
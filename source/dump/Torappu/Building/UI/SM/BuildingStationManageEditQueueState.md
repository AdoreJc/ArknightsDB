# BuildingStationManageEditQueueState

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `BuildingStationManageRoomStatusView _editRoomStatusView`

- `Button _btnArrowLeft`

- `Button _btnArrowRight`

- `UIAnimationLocation _animLeftIn`

- `UIAnimationLocation _animLeftOut`

- `UIAnimationLocation _animRightIn`

- `UIAnimationLocation _animRightOut`

- `Boolean m_isInited`

- `Tween m_switchAnim`

- `Boolean m_enableClick`

- `StationManageEditQueueStateBean m_stateBean`

- `BuildingModel m_curBuildingModel`


## Properties

- `RoomSlotModel m_curSlotModel`


## Methods

- `RoomSlotModel get_m_curSlotModel()`

- `Void _InitIfNot()`

- `Void _RenderRoomView(BuildingModel, RoomSlotModel)`

- `Void _Refresh()`

- `IEnumerator _SwitchRoomCoroutine(String, AnimationWrapper, String, AnimationWrapper, TweenCallback)`

- `Void _RenderNextRoom()`

- `Void _RenderPrefRoom()`

- `Void _OnPlayerDataUpdate()`

- `Void _OnJumpToSelectConfirmState(StationSelectConfirmStateBean)`

- `Void EventOnBackgroundClicked()`

- `Void EventOnNextClicked()`

- `Void EventOnPrefClicked()`

- `Void _OnCharClicked(BuildingCharModel, Object)`

- `Void _OnPreQueueCharClicked(BuildingCharModel, Object)`

- `Void _OnApplyPreQueueClicked(RoomSlotModel, Int32)`

- `Void <RegisterToDataListener>b__18_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingStationManageEditQueueState : PopupFloatState
{
	private BuildingStationManageRoomStatusView _editRoomStatusView; // 0x70
	private Button _btnArrowLeft; // 0x78
	private Button _btnArrowRight; // 0x80
	private UIAnimationLocation _animLeftIn; // 0x88
	private UIAnimationLocation _animLeftOut; // 0x98
	private UIAnimationLocation _animRightIn; // 0xa8
	private UIAnimationLocation _animRightOut; // 0xb8
	private Boolean m_isInited; // 0xc8
	private Tween m_switchAnim; // 0xd0
	private Boolean m_enableClick; // 0xd8
	private List`1 m_tempSelectedChars; // 0xe0
	private StationManageEditQueueStateBean m_stateBean; // 0xe8
	private BuildingModel m_curBuildingModel; // 0xf0
	private static DelegateBridge __Hotfix0_get_m_curSlotModel; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__RenderRoomView; // 0x28
	private static DelegateBridge __Hotfix0__Refresh; // 0x30
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x38
	private static DelegateBridge __Hotfix0__SwitchRoomCoroutine; // 0x40
	private static DelegateBridge __Hotfix0__RenderNextRoom; // 0x48
	private static DelegateBridge __Hotfix0__RenderPrefRoom; // 0x50
	private static DelegateBridge __Hotfix0__OnPlayerDataUpdate; // 0x58
	private static DelegateBridge __Hotfix0__OnJumpToSelectConfirmState; // 0x60
	private static DelegateBridge __Hotfix0_EventOnBackgroundClicked; // 0x68
	private static DelegateBridge __Hotfix0_EventOnNextClicked; // 0x70
	private static DelegateBridge __Hotfix0_EventOnPrefClicked; // 0x78
	private static DelegateBridge __Hotfix0__OnCharClicked; // 0x80
	private static DelegateBridge __Hotfix0__OnPreQueueCharClicked; // 0x88
	private static DelegateBridge __Hotfix0__OnApplyPreQueueClicked; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	private RoomSlotModel m_curSlotModel { get; }

	// RVA: 0x3da868c VA: 0x75963c068c
	private RoomSlotModel get_m_curSlotModel() { }
	// RVA: 0x3da8728 VA: 0x75963c0728
	private Void _InitIfNot() { }
	// RVA: 0x3da8a94 VA: 0x75963c0a94
	protected override Void OnEnter() { }
	// RVA: 0x3da8de0 VA: 0x75963c0de0
	protected override Void OnResume() { }
	// RVA: 0x3da8ee0 VA: 0x75963c0ee0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3da8d30 VA: 0x75963c0d30
	private Void _RenderRoomView(BuildingModel buildingModel, RoomSlotModel roomSlotModel) { }
	// RVA: 0x3da8bbc VA: 0x75963c0bbc
	private Void _Refresh() { }
	// RVA: 0x3da9058 VA: 0x75963c1058
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3da90c0 VA: 0x75963c10c0
	private IEnumerator _SwitchRoomCoroutine(String outAnimName, AnimationWrapper outAnimWrapper, String inAnimName, AnimationWrapper inAnimWrapper, TweenCallback outAnimCallback) { }
	// RVA: 0x3da9230 VA: 0x75963c1230
	private Void _RenderNextRoom() { }
	// RVA: 0x3da93d0 VA: 0x75963c13d0
	private Void _RenderPrefRoom() { }
	// RVA: 0x3da94b0 VA: 0x75963c14b0
	private Void _OnPlayerDataUpdate() { }
	// RVA: 0x3da9538 VA: 0x75963c1538
	private Void _OnJumpToSelectConfirmState(StationSelectConfirmStateBean selectConfirmBean) { }
	// RVA: 0x3da9844 VA: 0x75963c1844
	public Void EventOnBackgroundClicked() { }
	// RVA: 0x3da9958 VA: 0x75963c1958
	public Void EventOnNextClicked() { }
	// RVA: 0x3da9a6c VA: 0x75963c1a6c
	public Void EventOnPrefClicked() { }
	// RVA: 0x3da9b80 VA: 0x75963c1b80
	private Void _OnCharClicked(BuildingCharModel target, Object param) { }
	// RVA: 0x3da9c94 VA: 0x75963c1c94
	private Void _OnPreQueueCharClicked(BuildingCharModel target, Object param) { }
	// RVA: 0x3da9dac VA: 0x75963c1dac
	private Void _OnApplyPreQueueClicked(RoomSlotModel roomSlotModel, Int32 preQueueIndex) { }
	// RVA: 0x3daa394 VA: 0x75963c2394
	public Void .ctor() { }
	// RVA: 0x3daa490 VA: 0x75963c2490
	private Void <RegisterToDataListener>b__18_0(IStateBean stateBean) { }
	// RVA: 0x3daa510 VA: 0x75963c2510
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3daa518 VA: 0x75963c2518
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3daa520 VA: 0x75963c2520
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```
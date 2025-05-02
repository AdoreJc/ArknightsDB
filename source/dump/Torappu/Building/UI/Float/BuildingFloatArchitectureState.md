# BuildingFloatArchitectureState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `GameObject m_roomDetailPanel`

- `BuildingFloatArchSwitchView m_switchView`

- `RoomPanelInfo m_currentRoomPanelInfo`

- `Boolean m_levelupValid`

- `UIRoomIconSpriteHub m_roomIconSpriteHub`


## Methods

- `UIRoomIconSpriteHub _GetIconSpriteHub()`

- `Void OnEnable()`

- `Boolean _RoomCleanConfirmed(RoomSlotModel)`

- `Boolean _RoomBuildConfirmed(RoomSlotModel)`

- `Boolean _RoomLevelupConfirmed(RoomSlotModel)`

- `Boolean _RoomTeardownConfirmed(RoomSlotModel)`

- `Void _OnRoomRequestClean(Object)`

- `Void _OnRoomRequestBuild(Object)`

- `Void _OnRoomRequestLevelup(Object)`

- `Void _OnRoomRequestTeardown(Object)`

- `Void _OnRoomShowDetail(Object)`

- `Void _OnBuildChoiceSelected(Object)`

- `Void _OnRoomBuildComplete(RoomType)`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatArchitectureState : BuildingFloatState
{
	private const String BUTTON_SWITCH_ON; // 0x0
	private const Single BY_SIDE_NOTIFY_DELAY; // 0x0
	private static readonly Color BUTTON_GRAY; // 0x0
	private GameObject m_roomDetailPanel; // 0x40
	private BuildingFloatArchSwitchView m_switchView; // 0x48
	private RoomPanelInfo m_currentRoomPanelInfo; // 0x50
	private Boolean m_levelupValid; // 0x58
	private UIRoomIconSpriteHub m_roomIconSpriteHub; // 0x60
	private static DelegateBridge __Hotfix0_get_state; // 0x10
	private static DelegateBridge __Hotfix0__GetIconSpriteHub; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge __Hotfix0__ActionCallback; // 0x48
	private static DelegateBridge __Hotfix0__RoomCleanConfirmed; // 0x50
	private static DelegateBridge __Hotfix0__RoomBuildConfirmed; // 0x58
	private static DelegateBridge __Hotfix0__RoomLevelupConfirmed; // 0x60
	private static DelegateBridge __Hotfix0__RoomTeardownConfirmed; // 0x68
	private static DelegateBridge __Hotfix0__OnRoomRequestClean; // 0x70
	private static DelegateBridge __Hotfix0__OnRoomRequestBuild; // 0x78
	private static DelegateBridge __Hotfix0__OnRoomRequestLevelup; // 0x80
	private static DelegateBridge __Hotfix0__OnRoomRequestTeardown; // 0x88
	private static DelegateBridge __Hotfix0__OnRoomShowDetail; // 0x90
	private static DelegateBridge __Hotfix0__OnBuildChoiceSelected; // 0x98
	private static DelegateBridge __Hotfix0__OnRoomBuildComplete; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	protected override FloatState state { get; }

	// RVA: 0x3e17070 VA: 0x759642f070
	protected override FloatState get_state() { }
	// RVA: 0x3e170e8 VA: 0x759642f0e8
	private UIRoomIconSpriteHub _GetIconSpriteHub() { }
	// RVA: 0x3e1726c VA: 0x759642f26c
	private Void OnEnable() { }
	// RVA: 0x3e172f4 VA: 0x759642f2f4
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e17418 VA: 0x759642f418
	protected override Void OnInit() { }
	// RVA: 0x3e17550 VA: 0x759642f550
	protected override Void OnEnter() { }
	// RVA: 0x3e17888 VA: 0x759642f888
	protected override Void OnExit() { }
	// RVA: 0x3e17c38 VA: 0x759642fc38
	private Func`1 _ActionCallback(RoomSlotModel model, Func`2 action) { }
	// RVA: 0x3e17d6c VA: 0x759642fd6c
	private Boolean _RoomCleanConfirmed(RoomSlotModel model) { }
	// RVA: 0x3e18268 VA: 0x7596430268
	private Boolean _RoomBuildConfirmed(RoomSlotModel model) { }
	// RVA: 0x3e18afc VA: 0x7596430afc
	private Boolean _RoomLevelupConfirmed(RoomSlotModel model) { }
	// RVA: 0x3e191ec VA: 0x75964311ec
	private Boolean _RoomTeardownConfirmed(RoomSlotModel model) { }
	// RVA: 0x3e19b20 VA: 0x7596431b20
	private Void _OnRoomRequestClean(Object arg) { }
	// RVA: 0x3e19c74 VA: 0x7596431c74
	private Void _OnRoomRequestBuild(Object arg) { }
	// RVA: 0x3e19dc8 VA: 0x7596431dc8
	private Void _OnRoomRequestLevelup(Object arg) { }
	// RVA: 0x3e19f1c VA: 0x7596431f1c
	private Void _OnRoomRequestTeardown(Object arg) { }
	// RVA: 0x3e1a070 VA: 0x7596432070
	private Void _OnRoomShowDetail(Object arg) { }
	// RVA: 0x3e1a2b4 VA: 0x75964322b4
	private Void _OnBuildChoiceSelected(Object arg) { }
	// RVA: 0x3e1a39c VA: 0x759643239c
	private Void _OnRoomBuildComplete(RoomType builtRoomType) { }
	// RVA: 0x3e1a58c VA: 0x759643258c
	public Void .ctor() { }
	// RVA: 0x3e1a678 VA: 0x7596432678
	private static Void .cctor() { }
	// RVA: 0x3e1a6c8 VA: 0x75964326c8
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
	// RVA: 0x3e1a6d0 VA: 0x75964326d0
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x3e1a738 VA: 0x7596432738
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e1a7a0 VA: 0x75964327a0
	private Void <>xLuaBaseProxy_OnExit() { }
}
```
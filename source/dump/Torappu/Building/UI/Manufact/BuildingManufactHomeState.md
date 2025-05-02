# BuildingManufactHomeState

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `BuildingManufactTabGroup _tabGroup`

- `BuildingManufactRemainCountView _remainCount`

- `BuildingManufactOutputSlot _outputSlot`

- `BuildingManufactOutputCountView _outputCount`

- `BuildingManufactStationView _stationView`

- `BuildingManufactRoomTitle _roomTitle`

- `BuildingManufactSpeedInfoView _speedInfo`

- `RectTransform _settleAnchor`

- `TwoStateToggle _labelAccelButton`

- `MHomeStateBean m_stateBean`


## Methods

- `Void _InitTopMenu()`

- `Void EventOnHarestClick()`

- `Void EventOnLaborAccelClick()`

- `Void _OnJumpToFormulaState(MFormulaStateBean)`

- `Void _OnJumpBackFromFormulaState(MFormulaStateBean)`

- `Void _OnJumpToLaborAccelState(LaborAccelStateBean)`

- `Void _OnRoomSelected(String)`

- `Void _OnConfirmEdit()`

- `Void _OnCancelEdit()`

- `Void _OnEditFormula()`

- `Void _OnChangeCount(Int32)`

- `Void _OnCharAvatarClick(BuildingCharModel, Int32)`

- `Void UpdateTime(Single)`

- `Void _OnPlayerDataChanged()`

- `Void _SettleManufact()`

- `Void _SendConfirmFormulaChangeService()`

- `Void _TryRequestSettleEffect()`

- `Void _ClearResEffects()`

- `Void <RegisterFromDataListener>b__15_0(IStateBean)`

- `Void <RegisterToDataListener>b__16_0(IStateBean)`

- `Void <RegisterToDataListener>b__16_1(IStateBean)`

- `Void <_InitTopMenu>b__20_0(GameObject)`

- `Void <_InitTopMenu>b__20_1()`

- `Void <_SendConfirmFormulaChangeService>b__35_0(BuildingChangeManufactResponse)`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactHomeState : State, ITimeWatcher
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x50
	private BuildingManufactTabGroup _tabGroup; // 0x58
	private PrefabInstHolder[] _inputSlots; // 0x60
	private BuildingManufactRemainCountView _remainCount; // 0x68
	private BuildingManufactOutputSlot _outputSlot; // 0x70
	private BuildingManufactOutputCountView _outputCount; // 0x78
	private BuildingManufactStationView _stationView; // 0x80
	private BuildingManufactRoomTitle _roomTitle; // 0x88
	private BuildingManufactSpeedInfoView _speedInfo; // 0x90
	private RectTransform _settleAnchor; // 0x98
	private TwoStateToggle _labelAccelButton; // 0xa0
	private MHomeStateBean m_stateBean; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x8
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge __Hotfix0_OnExit; // 0x30
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x38
	private static DelegateBridge __Hotfix0_EventOnHarestClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnLaborAccelClick; // 0x48
	private static DelegateBridge __Hotfix0__OnJumpToFormulaState; // 0x50
	private static DelegateBridge __Hotfix0__OnJumpBackFromFormulaState; // 0x58
	private static DelegateBridge __Hotfix0__OnJumpToLaborAccelState; // 0x60
	private static DelegateBridge __Hotfix0__OnRoomSelected; // 0x68
	private static DelegateBridge __Hotfix0__OnConfirmEdit; // 0x70
	private static DelegateBridge __Hotfix0__OnCancelEdit; // 0x78
	private static DelegateBridge __Hotfix0__OnEditFormula; // 0x80
	private static DelegateBridge __Hotfix0__OnChangeCount; // 0x88
	private static DelegateBridge __Hotfix0__OnCharAvatarClick; // 0x90
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x98
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0xa0
	private static DelegateBridge __Hotfix0__SettleManufact; // 0xa8
	private static DelegateBridge __Hotfix0__SendConfirmFormulaChangeService; // 0xb0
	private static DelegateBridge __Hotfix0__TryRequestSettleEffect; // 0xb8
	private static DelegateBridge __Hotfix0__ClearResEffects; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8


	// RVA: 0x3e0629c VA: 0x759641e29c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3e06304 VA: 0x759641e304
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x3e0637c VA: 0x759641e37c
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x3e064f4 VA: 0x759641e4f4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3e066e8 VA: 0x759641e6e8
	protected override Void OnEnter() { }
	// RVA: 0x3e07008 VA: 0x759641f008
	protected override Void OnResume() { }
	// RVA: 0x3e07084 VA: 0x759641f084
	protected override Void OnExit() { }
	// RVA: 0x3e06f44 VA: 0x759641ef44
	private Void _InitTopMenu() { }
	// RVA: 0x3e07154 VA: 0x759641f154
	public Void EventOnHarestClick() { }
	// RVA: 0x3e07394 VA: 0x759641f394
	public Void EventOnLaborAccelClick() { }
	// RVA: 0x3e075c0 VA: 0x759641f5c0
	private Void _OnJumpToFormulaState(MFormulaStateBean formulaBean) { }
	// RVA: 0x3e076cc VA: 0x759641f6cc
	private Void _OnJumpBackFromFormulaState(MFormulaStateBean formulaBean) { }
	// RVA: 0x3e07770 VA: 0x759641f770
	private Void _OnJumpToLaborAccelState(LaborAccelStateBean laborAccelBean) { }
	// RVA: 0x3e07954 VA: 0x759641f954
	private Void _OnRoomSelected(String slotId) { }
	// RVA: 0x3e07b98 VA: 0x759641fb98
	private Void _OnConfirmEdit() { }
	// RVA: 0x3e08220 VA: 0x7596420220
	private Void _OnCancelEdit() { }
	// RVA: 0x3e08290 VA: 0x7596420290
	private Void _OnEditFormula() { }
	// RVA: 0x3e083a8 VA: 0x75964203a8
	private Void _OnChangeCount(Int32 delta) { }
	// RVA: 0x3e08430 VA: 0x7596420430
	private Void _OnCharAvatarClick(BuildingCharModel charModel, Int32 index) { }
	// RVA: 0x3e085e8 VA: 0x75964205e8
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x3e0866c VA: 0x759642066c
	private Void _OnPlayerDataChanged() { }
	// RVA: 0x3e071ec VA: 0x759641f1ec
	private Void _SettleManufact() { }
	// RVA: 0x3e07dc0 VA: 0x759641fdc0
	private Void _SendConfirmFormulaChangeService() { }
	// RVA: 0x3e086dc VA: 0x75964206dc
	private Void _TryRequestSettleEffect() { }
	// RVA: 0x3e089f8 VA: 0x75964209f8
	private Void _ClearResEffects() { }
	// RVA: 0x3e08ae4 VA: 0x7596420ae4
	public Void .ctor() { }
	// RVA: 0x3e08b90 VA: 0x7596420b90
	private Void <RegisterFromDataListener>b__15_0(IStateBean stateBean) { }
	// RVA: 0x3e08c10 VA: 0x7596420c10
	private Void <RegisterToDataListener>b__16_0(IStateBean stateBean) { }
	// RVA: 0x3e08c90 VA: 0x7596420c90
	private Void <RegisterToDataListener>b__16_1(IStateBean stateBean) { }
	// RVA: 0x3e08d10 VA: 0x7596420d10
	private Void <_InitTopMenu>b__20_0(GameObject obj) { }
	// RVA: 0x3e08dd4 VA: 0x7596420dd4
	private Void <_InitTopMenu>b__20_1() { }
	// RVA: 0x3e08df4 VA: 0x7596420df4
	private Void <_SendConfirmFormulaChangeService>b__35_0(BuildingChangeManufactResponse _) { }
	// RVA: 0x3e08e0c VA: 0x7596420e0c
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x3e08e14 VA: 0x7596420e14
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x3e08e1c VA: 0x7596420e1c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3e08e24 VA: 0x7596420e24
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e08e2c VA: 0x7596420e2c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3e08e34 VA: 0x7596420e34
	private Void <>xLuaBaseProxy_OnExit() { }
}
```
# BuildingStationSelectConfirmHomeState

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `RectTransform _roomListContent`

- `BuildingStationSelectConfirmRoomListItemView _roomListPrefab`

- `StationSelectConfirmStateBean m_stateBean`

- `StationConfirmModel m_cachedModel`


## Methods

- `Void _OnJumpFromAssistReportState(CharSelectStateBean)`

- `Void _InitRoomList()`

- `Void OnBackButtonPressed()`

- `Void OnConfirmButtonPressed()`

- `IEnumerator _ConfirmWhenTransFinish()`

- `Void <RegisterFromDataListener>b__7_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectConfirmHomeState : PopupFloatState, IHotfixable
{
	private RectTransform _roomListContent; // 0x70
	private BuildingStationSelectConfirmRoomListItemView _roomListPrefab; // 0x78
	private StationSelectConfirmStateBean m_stateBean; // 0x80
	private StationConfirmModel m_cachedModel; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x10
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpFromAssistReportState; // 0x28
	private static DelegateBridge __Hotfix0__GenTrainingInstIds; // 0x30
	private static DelegateBridge __Hotfix0__InitRoomList; // 0x38
	private static DelegateBridge __Hotfix0__GenerateBuildingCharList; // 0x40
	private static DelegateBridge __Hotfix0_OnBackButtonPressed; // 0x48
	private static DelegateBridge __Hotfix0_OnConfirmButtonPressed; // 0x50
	private static DelegateBridge __Hotfix0__ConfirmWhenTransFinish; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x3d960dc VA: 0x75963ae0dc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d96144 VA: 0x75963ae144
	protected override Void OnEnter() { }
	// RVA: 0x3d963bc VA: 0x75963ae3bc
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x3d96434 VA: 0x75963ae434
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x3d965ac VA: 0x75963ae5ac
	protected override Void OnExit() { }
	// RVA: 0x3d967a8 VA: 0x75963ae7a8
	private Void _OnJumpFromAssistReportState(CharSelectStateBean stateBean) { }
	// RVA: 0x3d96ccc VA: 0x75963aeccc
	private List`1 _GenTrainingInstIds(List`1 selectedInstIds) { }
	// RVA: 0x3d96234 VA: 0x75963ae234
	private Void _InitRoomList() { }
	// RVA: 0x3d96f94 VA: 0x75963aef94
	private List`1 _GenerateBuildingCharList(List`1 instIds) { }
	// RVA: 0x3d973bc VA: 0x75963af3bc
	public Void OnBackButtonPressed() { }
	// RVA: 0x3d9745c VA: 0x75963af45c
	public Void OnConfirmButtonPressed() { }
	// RVA: 0x3d966fc VA: 0x75963ae6fc
	private IEnumerator _ConfirmWhenTransFinish() { }
	// RVA: 0x3d97528 VA: 0x75963af528
	public Void .ctor() { }
	// RVA: 0x3d97610 VA: 0x75963af610
	private Void <RegisterFromDataListener>b__7_0(IStateBean stateBean) { }
	// RVA: 0x3d97690 VA: 0x75963af690
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d97698 VA: 0x75963af698
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x3d976a0 VA: 0x75963af6a0
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x3d976a8 VA: 0x75963af6a8
	private Void <>xLuaBaseProxy_OnExit() { }
}
```
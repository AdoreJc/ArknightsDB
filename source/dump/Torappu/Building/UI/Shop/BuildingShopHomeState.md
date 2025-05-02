# BuildingShopHomeState

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `PrefabInstHolder _topMenuHolder`

- `BuildingShopTabGroup _tabGroup`

- `BuildingShopOutputSlot _outputSlot`

- `BuildingShopRoomTitle _roomTitle`

- `RectTransform _settleAnchor`

- `SHomeStateBean m_stateBean`

- `SStockViewModel m_clickedStockCache`


## Methods

- `Void EventOnHarestClick()`

- `Void _OnJumpToFormulaState(SFormulaStateBean)`

- `Void _OnJumpBackFromFormulaState(SFormulaStateBean)`

- `Void _OnStockEditConfirmed(SStockViewModel)`

- `Void _OnStockEditCancelled(SStockViewModel)`

- `Void _OnStockCountEdited(SStockViewModel, Int32)`

- `Void _OnStockFormulaClicked(SStockViewModel)`

- `Void _OnStockCharClicked(SStockViewModel)`

- `Void _OnRoomSelected(String)`

- `Void UpdateTime(Single)`

- `Void _OnPlayerDataChanged()`

- `Void _InitTopMenu()`

- `Void _SendConfirmFormulaChangeService(SStockViewModel)`

- `Void _SettleSale()`

- `Void _TryRequestSettleEffect()`

- `Void _ClearResEffects()`

- `Void <RegisterFromDataListener>b__10_0(IStateBean)`

- `Void <RegisterToDataListener>b__11_0(IStateBean)`

- `Void <_InitTopMenu>b__24_0(GameObject)`

- `Void <_InitTopMenu>b__24_1()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class BuildingShopHomeState : State, ITimeWatcher
{
	private PrefabInstHolder _topMenuHolder; // 0x50
	private BuildingShopTabGroup _tabGroup; // 0x58
	private PrefabInstHolder[] _stockHolders; // 0x60
	private BuildingShopOutputSlot _outputSlot; // 0x68
	private BuildingShopRoomTitle _roomTitle; // 0x70
	private RectTransform _settleAnchor; // 0x78
	private SHomeStateBean m_stateBean; // 0x80
	private SStockViewModel m_clickedStockCache; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x8
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_EventOnHarestClick; // 0x28
	private static DelegateBridge __Hotfix0__OnJumpToFormulaState; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpBackFromFormulaState; // 0x38
	private static DelegateBridge __Hotfix0__OnStockEditConfirmed; // 0x40
	private static DelegateBridge __Hotfix0__OnStockEditCancelled; // 0x48
	private static DelegateBridge __Hotfix0__OnStockCountEdited; // 0x50
	private static DelegateBridge __Hotfix0__OnStockFormulaClicked; // 0x58
	private static DelegateBridge __Hotfix0__OnStockCharClicked; // 0x60
	private static DelegateBridge __Hotfix0__OnRoomSelected; // 0x68
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x70
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x78
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x80
	private static DelegateBridge __Hotfix0__SendConfirmFormulaChangeService; // 0x88
	private static DelegateBridge __Hotfix0__SettleSale; // 0x90
	private static DelegateBridge __Hotfix0__TryRequestSettleEffect; // 0x98
	private static DelegateBridge __Hotfix0__ClearResEffects; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x3dbc404 VA: 0x75963d4404
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3dbc46c VA: 0x75963d446c
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x3dbc4e4 VA: 0x75963d44e4
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x3dbc65c VA: 0x75963d465c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3dbc7d4 VA: 0x75963d47d4
	protected override Void OnEnter() { }
	// RVA: 0x3dbcde8 VA: 0x75963d4de8
	public Void EventOnHarestClick() { }
	// RVA: 0x3dbd028 VA: 0x75963d5028
	private Void _OnJumpToFormulaState(SFormulaStateBean formulaBean) { }
	// RVA: 0x3dbd134 VA: 0x75963d5134
	private Void _OnJumpBackFromFormulaState(SFormulaStateBean formulaBean) { }
	// RVA: 0x3dbd1dc VA: 0x75963d51dc
	private Void _OnStockEditConfirmed(SStockViewModel stockModel) { }
	// RVA: 0x3dbd89c VA: 0x75963d589c
	private Void _OnStockEditCancelled(SStockViewModel stockModel) { }
	// RVA: 0x3dbd940 VA: 0x75963d5940
	private Void _OnStockCountEdited(SStockViewModel stockModel, Int32 delta) { }
	// RVA: 0x3dbd9d4 VA: 0x75963d59d4
	private Void _OnStockFormulaClicked(SStockViewModel stockModel) { }
	// RVA: 0x3dbdb04 VA: 0x75963d5b04
	private Void _OnStockCharClicked(SStockViewModel stockModel) { }
	// RVA: 0x3dbdba0 VA: 0x75963d5ba0
	private Void _OnRoomSelected(String slotId) { }
	// RVA: 0x3dbdc28 VA: 0x75963d5c28
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x3dbdcac VA: 0x75963d5cac
	private Void _OnPlayerDataChanged() { }
	// RVA: 0x3dbcd1c VA: 0x75963d4d1c
	private Void _InitTopMenu() { }
	// RVA: 0x3dbd470 VA: 0x75963d5470
	private Void _SendConfirmFormulaChangeService(SStockViewModel stockModel) { }
	// RVA: 0x3dbce80 VA: 0x75963d4e80
	private Void _SettleSale() { }
	// RVA: 0x3dbdd24 VA: 0x75963d5d24
	private Void _TryRequestSettleEffect() { }
	// RVA: 0x3dbe0a4 VA: 0x75963d60a4
	private Void _ClearResEffects() { }
	// RVA: 0x3dbe190 VA: 0x75963d6190
	public Void .ctor() { }
	// RVA: 0x3dbe23c VA: 0x75963d623c
	private Void <RegisterFromDataListener>b__10_0(IStateBean stateBean) { }
	// RVA: 0x3dbe2bc VA: 0x75963d62bc
	private Void <RegisterToDataListener>b__11_0(IStateBean stateBean) { }
	// RVA: 0x3dbe33c VA: 0x75963d633c
	private Void <_InitTopMenu>b__24_0(GameObject obj) { }
	// RVA: 0x3dbe400 VA: 0x75963d6400
	private Void <_InitTopMenu>b__24_1() { }
	// RVA: 0x3dbe420 VA: 0x75963d6420
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x3dbe428 VA: 0x75963d6428
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x3dbe430 VA: 0x75963d6430
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3dbe438 VA: 0x75963d6438
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
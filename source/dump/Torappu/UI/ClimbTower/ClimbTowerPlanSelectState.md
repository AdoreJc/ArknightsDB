# ClimbTowerPlanSelectState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerPlanSelectView _view`

- `RectTransform _backBtnRt`

- `ClimbTowerPlanSelectStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnPlanClick(Boolean)`

- `Void <RegisterFromDataListener>b__8_0(IStateBean)`

- `Void <RegisterToDataListener>b__9_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerPlanSelectState : PopupFloatState
{
	private ClimbTowerPlanSelectView _view; // 0x70
	private RectTransform _backBtnRt; // 0x78
	private ClimbTowerPlanSelectStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x18
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge __Hotfix0__OnPlanClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2c8d4b4 VA: 0x75952a54b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c8d51c VA: 0x75952a551c
	protected override Void OnEnter() { }
	// RVA: 0x2c8d78c VA: 0x75952a578c
	private Void _InitIfNot() { }
	// RVA: 0x2c8d990 VA: 0x75952a5990
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2c8da08 VA: 0x75952a5a08
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2c8db80 VA: 0x75952a5b80
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2c8dcf8 VA: 0x75952a5cf8
	private Void _OnPlanClick(Boolean isFree) { }
	// RVA: 0x2c8ddfc VA: 0x75952a5dfc
	public Void .ctor() { }
	// RVA: 0x2c8dea8 VA: 0x75952a5ea8
	private Void <RegisterFromDataListener>b__8_0(IStateBean stateBean) { }
	// RVA: 0x2c8df60 VA: 0x75952a5f60
	private Void <RegisterToDataListener>b__9_0(IStateBean stateBean) { }
	// RVA: 0x2c8e00c VA: 0x75952a600c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c8e014 VA: 0x75952a6014
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2c8e01c VA: 0x75952a601c
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x2c8e024 VA: 0x75952a6024
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```
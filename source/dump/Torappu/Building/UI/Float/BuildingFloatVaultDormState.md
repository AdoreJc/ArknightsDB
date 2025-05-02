# BuildingFloatVaultDormState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Text _comfortText`

- `Text _manpowerRecoverText`

- `Transform _shopPanelHolder`

- `DIYShopPanel m_diyShopPanel`


## Properties

- `Boolean DIYShopShown`


## Methods

- `Boolean get_DIYShopShown()`

- `Void EventOnDIYClick()`

- `Void EventOnDIYShopClick()`

- `Void <EventOnDIYShopClick>b__13_0(Int32)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatVaultDormState : BuildingFloatVaultInfoState
{
	private Text _comfortText; // 0xa0
	private Text _manpowerRecoverText; // 0xa8
	private Transform _shopPanelHolder; // 0xb0
	private DIYShopPanel m_diyShopPanel; // 0xb8
	private static DelegateBridge __Hotfix0_get_DIYShopShown; // 0x0
	private static DelegateBridge __Hotfix0_get_state; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x28
	private static DelegateBridge __Hotfix0_EventOnDIYClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnDIYShopClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean DIYShopShown { get; }
	protected override FloatState state { get; }

	// RVA: 0x3e25fa0 VA: 0x759643dfa0
	public Boolean get_DIYShopShown() { }
	// RVA: 0x3e26060 VA: 0x759643e060
	protected override FloatState get_state() { }
	// RVA: 0x3e260c8 VA: 0x759643e0c8
	protected override Void OnInit() { }
	// RVA: 0x3e2637c VA: 0x759643e37c
	protected override Void OnEnter() { }
	// RVA: 0x3e267e8 VA: 0x759643e7e8
	protected override Void OnExit() { }
	// RVA: 0x3e26b20 VA: 0x759643eb20
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e26ff8 VA: 0x759643eff8
	public Void EventOnDIYClick() { }
	// RVA: 0x3e270b8 VA: 0x759643f0b8
	public Void EventOnDIYShopClick() { }
	// RVA: 0x3e27314 VA: 0x759643f314
	public Void .ctor() { }
	// RVA: 0x3e273a4 VA: 0x759643f3a4
	private Void <EventOnDIYShopClick>b__13_0(Int32 result) { }
	// RVA: 0x3e27578 VA: 0x759643f578
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x3e2757c VA: 0x759643f57c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e27580 VA: 0x759643f580
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x3e27584 VA: 0x759643f584
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
}
```
# BuildingFloatBpOrVaultState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Button _btnSM`

- `GameObject _iconDisableSM`

- `GameObject _stationManageTrackPoint`


## Methods

- `Boolean _CheckPlayerHasBuiltDorm()`

- `Void OnStationManagerClick()`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatBpOrVaultState : BuildingFloatState
{
	private Button _btnSM; // 0x40
	private GameObject _iconDisableSM; // 0x48
	private GameObject _stationManageTrackPoint; // 0x50
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x8
	private static DelegateBridge __Hotfix0__CheckPlayerHasBuiltDorm; // 0x10
	private static DelegateBridge __Hotfix0_OnStationManagerClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override FloatState state { get; }

	// RVA: 0x3e1c24c VA: 0x759643424c
	protected override FloatState get_state() { }
	// RVA: 0x3e1c2b4 VA: 0x75964342b4
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e1c464 VA: 0x7596434464
	private Boolean _CheckPlayerHasBuiltDorm() { }
	// RVA: 0x3e1c534 VA: 0x7596434534
	public Void OnStationManagerClick() { }
	// RVA: 0x3e1c5a8 VA: 0x75964345a8
	public Void .ctor() { }
	// RVA: 0x3e1c614 VA: 0x7596434614
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
}
```
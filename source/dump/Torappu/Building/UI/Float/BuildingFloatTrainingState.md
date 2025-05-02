# BuildingFloatTrainingState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `BuildingFloatTrainingView _view`


## Methods

- `Void EventOnTrainingClick()`

- `Void OnUpgradeFinish()`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`

- `Void <>xLuaBaseProxy_OnPlayerDataChanged(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatTrainingState : BuildingFloatVaultInfoState
{
	private BuildingFloatTrainingView _view; // 0xa0
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x0
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_get_state; // 0x10
	private static DelegateBridge __Hotfix0_EventOnTrainingClick; // 0x18
	private static DelegateBridge __Hotfix0_OnUpgradeFinish; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override FloatState state { get; }

	// RVA: 0x3e24898 VA: 0x759643c898
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e24d90 VA: 0x759643cd90
	protected override Void OnPlayerDataChanged(Object args) { }
	// RVA: 0x3e24e14 VA: 0x759643ce14
	protected override FloatState get_state() { }
	// RVA: 0x3e24e7c VA: 0x759643ce7c
	public Void EventOnTrainingClick() { }
	// RVA: 0x3e24fd4 VA: 0x759643cfd4
	public Void OnUpgradeFinish() { }
	// RVA: 0x3e254b0 VA: 0x759643d4b0
	public Void .ctor() { }
	// RVA: 0x3e25540 VA: 0x759643d540
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
	// RVA: 0x3e25548 VA: 0x759643d548
	private Void <>xLuaBaseProxy_OnPlayerDataChanged(Object P0) { }
}
```
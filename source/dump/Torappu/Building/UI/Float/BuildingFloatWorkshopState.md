# BuildingFloatWorkshopState

**Namespace:** `Torappu.Building.UI.Float`


## Methods

- `Void EventOnWorkshopClick()`

- `Void <>xLuaBaseProxy_OnPlayerDataChanged(Object)`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatWorkshopState : BuildingFloatVaultInfoState
{
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x10
	private static DelegateBridge __Hotfix0_EventOnWorkshopClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override FloatState state { get; }

	// RVA: 0x3e2be58 VA: 0x7596443e58
	protected override FloatState get_state() { }
	// RVA: 0x3e2bec0 VA: 0x7596443ec0
	protected override Void OnPlayerDataChanged(Object args) { }
	// RVA: 0x3e2bf40 VA: 0x7596443f40
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e2bfc0 VA: 0x7596443fc0
	public Void EventOnWorkshopClick() { }
	// RVA: 0x3e2c0bc VA: 0x75964440bc
	public Void .ctor() { }
	// RVA: 0x3e2c14c VA: 0x759644414c
	private Void <>xLuaBaseProxy_OnPlayerDataChanged(Object P0) { }
	// RVA: 0x3e2c150 VA: 0x7596444150
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
}
```
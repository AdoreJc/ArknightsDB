# BuildingFloatTradingState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `BuildingFloatTradingView _tradingView`


## Methods

- `Void _Render(RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`

- `Void <>xLuaBaseProxy_OnPlayerDataChanged(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatTradingState : BuildingFloatVaultInfoState
{
	private BuildingFloatTradingView _tradingView; // 0xa0
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override FloatState state { get; }

	// RVA: 0x3e23d98 VA: 0x759643bd98
	protected override FloatState get_state() { }
	// RVA: 0x3e23e00 VA: 0x759643be00
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e24168 VA: 0x759643c168
	protected override Void OnPlayerDataChanged(Object args) { }
	// RVA: 0x3e23fbc VA: 0x759643bfbc
	private Void _Render(RoomSlotModel slotModel) { }
	// RVA: 0x3e2468c VA: 0x759643c68c
	public Void .ctor() { }
	// RVA: 0x3e2488c VA: 0x759643c88c
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
	// RVA: 0x3e24894 VA: 0x759643c894
	private Void <>xLuaBaseProxy_OnPlayerDataChanged(Object P0) { }
}
```
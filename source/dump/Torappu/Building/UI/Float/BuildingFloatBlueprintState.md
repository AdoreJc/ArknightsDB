# BuildingFloatBlueprintState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `GameObject m_extraViews`


## Methods

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatBlueprintState : BuildingFloatState
{
	private GameObject m_extraViews; // 0x40
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override FloatState state { get; }

	// RVA: 0x3e1c040 VA: 0x7596434040
	protected override FloatState get_state() { }
	// RVA: 0x3e1c0a8 VA: 0x75964340a8
	protected override Void OnInit() { }
	// RVA: 0x3e1c140 VA: 0x7596434140
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e1c1d4 VA: 0x75964341d4
	public Void .ctor() { }
	// RVA: 0x3e1c240 VA: 0x7596434240
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x3e1c244 VA: 0x7596434244
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
}
```
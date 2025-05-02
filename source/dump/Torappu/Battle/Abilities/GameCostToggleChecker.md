# GameCostToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _minCost`

- `Int32 _maxCost`

- `Boolean _toggleIfMaxGameCost`

- `Int32 m_minCost`

- `Int32 m_maxCost`


## Methods

- `Boolean _CheckCondition()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class GameCostToggleChecker : Checker
{
	private Int32 _minCost; // 0x20
	private Int32 _maxCost; // 0x24
	private Boolean _toggleIfMaxGameCost; // 0x28
	private Int32 m_minCost; // 0x2c
	private Int32 m_maxCost; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x10
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e5c970 VA: 0x7594474970
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5ca28 VA: 0x7594474a28
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5cc10 VA: 0x7594474c10
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5cab0 VA: 0x7594474ab0
	private Boolean _CheckCondition() { }
	// RVA: 0x1e5cc78 VA: 0x7594474c78
	public Void .ctor() { }
	// RVA: 0x1e5ccec VA: 0x7594474cec
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
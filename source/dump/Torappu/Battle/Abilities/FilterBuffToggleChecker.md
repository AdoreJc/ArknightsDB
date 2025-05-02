# FilterBuffToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _excludeBuff`

- `String _buffKey`

- `PeriodicTicker m_checkerTicker`


## Methods

- `Boolean _CheckCondition()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class FilterBuffToggleChecker : Checker
{
	private const Int32 TOGGLE_CHECKER_TICK; // 0x0
	private Boolean _excludeBuff; // 0x20
	private String _buffKey; // 0x28
	private PeriodicTicker m_checkerTicker; // 0x30
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_OnAttached; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1e5c5ac VA: 0x75944745ac
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5c6fc VA: 0x75944746fc
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5c774 VA: 0x7594474774
	public override Void OnAttached() { }
	// RVA: 0x1e5c7f4 VA: 0x75944747f4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5c614 VA: 0x7594474614
	private Boolean _CheckCondition() { }
	// RVA: 0x1e5c8b4 VA: 0x75944748b4
	public Void .ctor() { }
	// RVA: 0x1e5c968 VA: 0x7594474968
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e5c96c VA: 0x759447496c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
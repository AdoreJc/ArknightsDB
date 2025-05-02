# RangeTileToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TargetSelector _selector`

- `PhysicsRange _rangeToLoad`

- `Int32 m_minCnt`


## Methods

- `Boolean _CheckCondition(Vector2)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RangeTileToggleChecker : Checker
{
	private TargetSelector _selector; // 0x20
	private PhysicsRange _rangeToLoad; // 0x28
	private Int32 m_minCnt; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_OnDetached; // 0x10
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x18
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1e5e8b8 VA: 0x75944768b8
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5eb7c VA: 0x7594476b7c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5ed30 VA: 0x7594476d30
	public override Void OnDetached() { }
	// RVA: 0x1e5ed9c VA: 0x7594476d9c
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5ec28 VA: 0x7594476c28
	private Boolean _CheckCondition(Vector2 pos) { }
	// RVA: 0x1e5ee74 VA: 0x7594476e74
	public Void .ctor() { }
	// RVA: 0x1e5eee0 VA: 0x7594476ee0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1e5eee4 VA: 0x7594476ee4
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```
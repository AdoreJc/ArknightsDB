# SpSkillAvailableCntChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _compCnt`

- `Single _restoreDelay`

- `Boolean _waitForSkillFinished`

- `CompareType _condType`

- `Single m_compCnt`

- `Single m_restoreDelay`


## Methods

- `Boolean _CheckCondition()`

- `Single <>xLuaBaseProxy_get_restoreDelay()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SpSkillAvailableCntChecker : Checker
{
	private Single _compCnt; // 0x20
	private Single _restoreDelay; // 0x24
	private Boolean _waitForSkillFinished; // 0x28
	private CompareType _condType; // 0x2c
	private Single m_compCnt; // 0x30
	private Single m_restoreDelay; // 0x34
	private static DelegateBridge __Hotfix0_get_restoreDelay; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Single restoreDelay { get; }

	// RVA: 0x1e60430 VA: 0x7594478430
	public override Single get_restoreDelay() { }
	// RVA: 0x1e60498 VA: 0x7594478498
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e6057c VA: 0x759447857c
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e60804 VA: 0x7594478804
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e605e4 VA: 0x75944785e4
	private Boolean _CheckCondition() { }
	// RVA: 0x1e6088c VA: 0x759447888c
	public Void .ctor() { }
	// RVA: 0x1e608f8 VA: 0x75944788f8
	private Single <>xLuaBaseProxy_get_restoreDelay() { }
	// RVA: 0x1e608fc VA: 0x75944788fc
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
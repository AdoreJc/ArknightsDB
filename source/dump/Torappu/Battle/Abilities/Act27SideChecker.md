# Act27SideChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `MechanismSideType _targetSideType`

- `Act27SideBattleManager m_manager`


## Methods

- `Boolean _CheckCondition()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class Act27SideChecker : Checker
{
	private MechanismSideType _targetSideType; // 0x20
	private Act27SideBattleManager m_manager; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e565f0 VA: 0x759446e5f0
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e56780 VA: 0x759446e780
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e568bc VA: 0x759446e8bc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e567e8 VA: 0x759446e7e8
	private Boolean _CheckCondition() { }
	// RVA: 0x1e569c8 VA: 0x759446e9c8
	public Void .ctor() { }
	// RVA: 0x1e56a34 VA: 0x759446ea34
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
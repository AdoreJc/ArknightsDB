# RoguelikeModeLifePointToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _minLifePoint`

- `Int32 _maxLifePoint`

- `Boolean _checkLifePointEqualMax`

- `Int32 m_minLifePoint`

- `Int32 m_maxLifePoint`


## Methods

- `Boolean _CheckCondition()`

- `Boolean _CheckGameMode()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RoguelikeModeLifePointToggleChecker : Checker
{
	private Int32 _minLifePoint; // 0x20
	private Int32 _maxLifePoint; // 0x24
	private Boolean _checkLifePointEqualMax; // 0x28
	private Int32 m_minLifePoint; // 0x2c
	private Int32 m_maxLifePoint; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x10
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x18
	private static DelegateBridge __Hotfix0__CheckGameMode; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1e5eee8 VA: 0x7594476ee8
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5f244 VA: 0x7594477244
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5f484 VA: 0x7594477484
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5f2e8 VA: 0x75944772e8
	private Boolean _CheckCondition() { }
	// RVA: 0x1e5f07c VA: 0x759447707c
	private Boolean _CheckGameMode() { }
	// RVA: 0x1e5f508 VA: 0x7594477508
	public Void .ctor() { }
	// RVA: 0x1e5f57c VA: 0x759447757c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
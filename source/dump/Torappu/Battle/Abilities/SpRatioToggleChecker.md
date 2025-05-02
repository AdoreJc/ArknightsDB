# SpRatioToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _minSpRatio`

- `Single _maxSpRatio`

- `Single _restoreDelay`

- `Boolean _waitForAttackFinished`

- `Single m_maxSpRatio`

- `Single m_restoreDelay`


## Methods

- `Boolean _CheckCondition()`

- `Single <>xLuaBaseProxy_get_restoreDelay()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SpRatioToggleChecker : Checker
{
	private Single _minSpRatio; // 0x20
	private Single _maxSpRatio; // 0x24
	private Single _restoreDelay; // 0x28
	private Boolean _waitForAttackFinished; // 0x2c
	private Single m_maxSpRatio; // 0x30
	private Single m_restoreDelay; // 0x34
	private static DelegateBridge __Hotfix0_get_restoreDelay; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Single restoreDelay { get; }

	// RVA: 0x1e5fe10 VA: 0x7594477e10
	public override Single get_restoreDelay() { }
	// RVA: 0x1e5fe78 VA: 0x7594477e78
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5ff5c VA: 0x7594477f5c
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e6032c VA: 0x759447832c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5ffc4 VA: 0x7594477fc4
	private Boolean _CheckCondition() { }
	// RVA: 0x1e603b4 VA: 0x75944783b4
	public Void .ctor() { }
	// RVA: 0x1e60428 VA: 0x7594478428
	private Single <>xLuaBaseProxy_get_restoreDelay() { }
	// RVA: 0x1e6042c VA: 0x759447842c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
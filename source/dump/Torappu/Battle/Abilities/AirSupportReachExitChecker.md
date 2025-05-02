# AirSupportReachExitChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _isInitToggled`

- `Single _restoreDelay`

- `Boolean _toggleWhenReached`

- `Single m_restoreDelay`


## Methods

- `Single <>xLuaBaseProxy_get_restoreDelay()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AirSupportReachExitChecker : Checker
{
	private Boolean _isInitToggled; // 0x20
	private Single _restoreDelay; // 0x24
	private Boolean _toggleWhenReached; // 0x28
	private Single m_restoreDelay; // 0x2c
	private static DelegateBridge __Hotfix0_get_restoreDelay; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Single restoreDelay { get; }

	// RVA: 0x1e5f908 VA: 0x7594477908
	public override Single get_restoreDelay() { }
	// RVA: 0x1e5f970 VA: 0x7594477970
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5fa24 VA: 0x7594477a24
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5fa8c VA: 0x7594477a8c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5fd90 VA: 0x7594477d90
	public Void .ctor() { }
	// RVA: 0x1e5fe08 VA: 0x7594477e08
	private Single <>xLuaBaseProxy_get_restoreDelay() { }
	// RVA: 0x1e5fe0c VA: 0x7594477e0c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
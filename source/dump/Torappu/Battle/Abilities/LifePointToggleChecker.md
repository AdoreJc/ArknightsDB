# LifePointToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _minLifePoint`

- `Int32 _maxLifePoint`

- `Int32 m_minLifePoint`

- `Int32 m_maxLifePoint`


## Methods

- `Boolean _CheckCondition()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class LifePointToggleChecker : Checker
{
	private Int32 _minLifePoint; // 0x20
	private Int32 _maxLifePoint; // 0x24
	private Int32 m_minLifePoint; // 0x28
	private Int32 m_maxLifePoint; // 0x2c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x10
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e5d428 VA: 0x7594475428
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5d4e0 VA: 0x75944754e0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5d628 VA: 0x7594475628
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5d568 VA: 0x7594475568
	private Boolean _CheckCondition() { }
	// RVA: 0x1e5d690 VA: 0x7594475690
	public Void .ctor() { }
	// RVA: 0x1e5d704 VA: 0x7594475704
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
# OverrideAttackOrCombatTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _overrideAttack`

- `Boolean _overrideCombat`

- `TargetTrigger _trigger`


## Methods

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class OverrideAttackOrCombatTalent : Talent
{
	private Boolean _overrideAttack; // 0x88
	private Boolean _overrideCombat; // 0x89
	private TargetTrigger _trigger; // 0x90
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_DoDetach; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b7cffc VA: 0x7594194ffc
	protected override Void DoAttach() { }
	// RVA: 0x1b7d0e0 VA: 0x75941950e0
	protected override Void DoDetach() { }
	// RVA: 0x1b7d1c4 VA: 0x75941951c4
	public Void .ctor() { }
	// RVA: 0x1b7d230 VA: 0x7594195230
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b7d234 VA: 0x7594195234
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```
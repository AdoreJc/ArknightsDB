# MainTargetMultiRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 m_remainTimes`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32)`

- `Boolean <>xLuaBaseProxy_UpdateTargets(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MainTargetMultiRangedAttack : MultiRangedAttack
{
	private Int32 m_remainTimes; // 0x2c8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_CheckAnotherSpell; // 0x8
	private static DelegateBridge __Hotfix0_UpdateTargets; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1e118c0 VA: 0x75944298c0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e11b24 VA: 0x7594429b24
	protected override Boolean CheckAnotherSpell(Int32 spellCnt) { }
	// RVA: 0x1e11df8 VA: 0x7594429df8
	protected override Boolean UpdateTargets(Boolean updateInputPos) { }
	// RVA: 0x1e11fec VA: 0x7594429fec
	public Void .ctor() { }
	// RVA: 0x1e12058 VA: 0x759442a058
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e1207c VA: 0x759442a07c
	private Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32 P0) { }
	// RVA: 0x1e12080 VA: 0x759442a080
	private Boolean <>xLuaBaseProxy_UpdateTargets(Boolean P0) { }
}
```
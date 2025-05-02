# MultiFunnelNormalAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `MultiFunnelTrait m_trait`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnOutputAttackOrHeal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiFunnelNormalAttack : RangedAttack
{
	private MultiFunnelTrait m_trait; // 0x260
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x8
	private static DelegateBridge __Hotfix0_OnOutputAttackOrHeal; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1e12f84 VA: 0x759442af84
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e13190 VA: 0x759442b190
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e132f0 VA: 0x759442b2f0
	protected override Void OnOutputAttackOrHeal() { }
	// RVA: 0x1e13354 VA: 0x759442b354
	public Void .ctor() { }
	// RVA: 0x1e133c0 VA: 0x759442b3c0
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e133e8 VA: 0x759442b3e8
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e133ec VA: 0x759442b3ec
	private Void <>xLuaBaseProxy_OnOutputAttackOrHeal() { }
}
```
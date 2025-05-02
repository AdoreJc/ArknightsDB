# RangedAttackWithConditionalActions

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RangedAttackWithConditionalActions : RangedAttack
{
	private ConditionalActions[] _conditionalActions; // 0x260
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1e17e4c VA: 0x759442fe4c
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e17fc8 VA: 0x759442ffc8
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e181bc VA: 0x75944301bc
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1e182c4 VA: 0x75944302c4
	public Void .ctor() { }
	// RVA: 0x1e18330 VA: 0x7594430330
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e18358 VA: 0x7594430358
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1e1835c VA: 0x759443035c
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```
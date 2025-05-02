# RangedAttackWithExtraActions

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Event _actionEvent`

- `ActionArray _actions`

- `Boolean _overwriteAbilityActions`


## Methods

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RangedAttackWithExtraActions : RangedAttack
{
	private Event _actionEvent; // 0x25c
	private ActionArray _actions; // 0x260
	private Boolean _overwriteAbilityActions; // 0x268
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x0
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e18878 VA: 0x7594430878
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e189ac VA: 0x75944309ac
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1e18a50 VA: 0x7594430a50
	public Void .ctor() { }
	// RVA: 0x1e18b04 VA: 0x7594430b04
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1e18b08 VA: 0x7594430b08
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```
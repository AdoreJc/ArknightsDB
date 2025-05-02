# ProjectileToTileWithExtraActionsAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Event _extraActionEvent`

- `ActionArray _extraActions`

- `Boolean _overwriteHitObjectActions`


## Properties

- `Boolean isHitObjectEvent`


## Methods

- `Boolean get_isHitObjectEvent()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ProjectileToTileWithExtraActionsAbility : ProjectileToTileAbility
{
	private String[] _extraProjectileKeys; // 0x250
	private Event _extraActionEvent; // 0x258
	private ActionArray _extraActions; // 0x260
	private Boolean _overwriteHitObjectActions; // 0x268
	private static DelegateBridge __Hotfix0_get_isHitObjectEvent; // 0x0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x8
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x10
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x18
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isHitObjectEvent { get; }

	// RVA: 0x1e2b780 VA: 0x7594443780
	public Boolean get_isHitObjectEvent() { }
	// RVA: 0x1e2b7f0 VA: 0x75944437f0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e2b918 VA: 0x7594443918
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e2ba98 VA: 0x7594443a98
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e2bbd4 VA: 0x7594443bd4
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1e2bc78 VA: 0x7594443c78
	public Void .ctor() { }
	// RVA: 0x1e2bd2c VA: 0x7594443d2c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e2bd50 VA: 0x7594443d50
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
	// RVA: 0x1e2bd54 VA: 0x7594443d54
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1e2bd58 VA: 0x7594443d58
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```
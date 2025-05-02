# AnimatedActionToOwnerAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ActionArray _actions`


## Methods

- `Boolean <>xLuaBaseProxy_OnSpellStart()`

- `ActionPurposeMask <>xLuaBaseProxy_GeneratePurposeMask()`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AnimatedActionToOwnerAbility : AbstractAnimatedAbility
{
	private ActionArray _actions; // 0x1c0
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x0
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x8
	private static DelegateBridge __Hotfix0_OnSpellStart; // 0x10
	private static DelegateBridge __Hotfix0_GeneratePurposeMask; // 0x18
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1e01d80 VA: 0x7594419d80
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e01e00 VA: 0x7594419e00
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e01e78 VA: 0x7594419e78
	protected override Boolean OnSpellStart() { }
	// RVA: 0x1e02144 VA: 0x759441a144
	protected override ActionPurposeMask GeneratePurposeMask() { }
	// RVA: 0x1e021d4 VA: 0x759441a1d4
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1e02278 VA: 0x759441a278
	public Void .ctor() { }
	// RVA: 0x1e02328 VA: 0x759441a328
	private Boolean <>xLuaBaseProxy_OnSpellStart() { }
	// RVA: 0x1e02330 VA: 0x759441a330
	private ActionPurposeMask <>xLuaBaseProxy_GeneratePurposeMask() { }
	// RVA: 0x1e02338 VA: 0x759441a338
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```
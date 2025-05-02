# ProjectileActionBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Event _ev`

- `ActionArray _actions`

- `Boolean _overwriteActions`

- `Boolean _preprocessActionsForProjectile`

- `Boolean _applyOnApplyAtkScaleToDamageNode`


## Methods

- `Void _AssignActionsInternal()`

- `Void GatherActionNodes(List`1)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_TryRegisterExtraActionNode()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ProjectileActionBehaviour : Behaviour, IActionNodeSource
{
	private Event _ev; // 0x24
	private ActionArray _actions; // 0x28
	private Boolean _overwriteActions; // 0x30
	private Boolean _preprocessActionsForProjectile; // 0x31
	private Boolean _applyOnApplyAtkScaleToDamageNode; // 0x32
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_TryRegisterExtraActionNode; // 0x8
	private static DelegateBridge __Hotfix0__AssignActionsInternal; // 0x10
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1d6cfec VA: 0x7594384fec
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d6d190 VA: 0x7594385190
	public override Void TryRegisterExtraActionNode() { }
	// RVA: 0x1d6d09c VA: 0x759438509c
	private Void _AssignActionsInternal() { }
	// RVA: 0x1d6d20c VA: 0x759438520c
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1d6d2c4 VA: 0x75943852c4
	public Void .ctor() { }
	// RVA: 0x1d6d334 VA: 0x7594385334
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d6d33c VA: 0x759438533c
	private Void <>xLuaBaseProxy_TryRegisterExtraActionNode() { }
}
```
# SimpleProjectileEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _projectileKey`

- `MountPointType _mountPointType`

- `Event _emitEvent`

- `Boolean _includeDeadTargets`

- `Boolean _manageProjectileByOwner`


## Properties

- `Boolean projectileValid`


## Methods

- `Boolean get_projectileValid()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SimpleProjectileEmitter : AbstractProjectileEmitter
{
	private String _projectileKey; // 0x20
	private MountPointType _mountPointType; // 0x28
	private Event _emitEvent; // 0x2c
	private Boolean _includeDeadTargets; // 0x30
	private Boolean _manageProjectileByOwner; // 0x31
	private static DelegateBridge __Hotfix0_get_projectileValid; // 0x0
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x8
	private static DelegateBridge __Hotfix0_OnEvent; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Boolean projectileValid { get; }

	// RVA: 0x1ed5ad4 VA: 0x75944edad4
	protected Boolean get_projectileValid() { }
	// RVA: 0x1ed5b4c VA: 0x75944edb4c
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1ed5c5c VA: 0x75944edc5c
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ed6134 VA: 0x75944ee134
	public Void .ctor() { }
	// RVA: 0x1ed61a8 VA: 0x75944ee1a8
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```
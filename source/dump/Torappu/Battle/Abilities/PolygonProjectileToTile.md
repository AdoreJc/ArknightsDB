# PolygonProjectileToTile

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _projectileKey`

- `MountPointType _mountPointType`


## Properties

- `Boolean projectileValid`


## Methods

- `Boolean get_projectileValid()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class PolygonProjectileToTile : AbstractProjectileEmitter
{
	private String _projectileKey; // 0x20
	private MountPointType _mountPointType; // 0x28
	protected List`1 m_targetTiles; // 0x30
	private static DelegateBridge __Hotfix0_get_projectileValid; // 0x0
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x8
	private static DelegateBridge __Hotfix0_OnEvent; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Boolean projectileValid { get; }

	// RVA: 0x1ed5444 VA: 0x75944ed444
	protected Boolean get_projectileValid() { }
	// RVA: 0x1ed54bc VA: 0x75944ed4bc
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1ed55cc VA: 0x75944ed5cc
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ed5a04 VA: 0x75944eda04
	public Void .ctor() { }
	// RVA: 0x1ed5acc VA: 0x75944edacc
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```
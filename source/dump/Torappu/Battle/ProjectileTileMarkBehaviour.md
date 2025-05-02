# ProjectileTileMarkBehaviour

**Namespace:** `Torappu.Battle`


## Fields

- `TileInfoMask _mask`

- `Tile m_tracedTile`


## Methods

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ProjectileTileMarkBehaviour : Behaviour
{
	private TileInfoMask _mask; // 0x24
	private Tile m_tracedTile; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x40a3688 VA: 0x75966bb688
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x40a3854 VA: 0x75966bb854
	public override Void OnProjectileStop() { }
	// RVA: 0x40a3934 VA: 0x75966bb934
	public Void .ctor() { }
	// RVA: 0x40a39ac VA: 0x75966bb9ac
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x40a39b4 VA: 0x75966bb9b4
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```
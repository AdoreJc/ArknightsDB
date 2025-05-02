# TileTargetMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Tile _targetTile`


## Methods

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class TileTargetMovement : AdvancedMovement
{
	private Tile _targetTile; // 0x118
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1dadbcc VA: 0x75943c5bcc
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1dadd74 VA: 0x75943c5d74
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1dae3b0 VA: 0x75943c63b0
	public Void .ctor() { }
	// RVA: 0x1dae420 VA: 0x75943c6420
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1dae428 VA: 0x75943c6428
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
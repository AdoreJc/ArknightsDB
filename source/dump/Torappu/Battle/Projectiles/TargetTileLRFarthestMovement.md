# TargetTileLRFarthestMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Boolean _isLeftToRight`

- `Boolean _overrideMovementAdjustable`


## Methods

- `Void OnDestroy()`

- `Boolean <>xLuaBaseProxy_get_movementAdjustable()`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Vector3 <>xLuaBaseProxy_GetTraceTargetMapPosition()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class TargetTileLRFarthestMovement : AdvancedMovement
{
	private Boolean _isLeftToRight; // 0x114
	private Boolean _overrideMovementAdjustable; // 0x115
	private ObjectPtr`1 m_targetTile; // 0x118
	private ObjectPtr`1 m_startTile; // 0x128
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x10
	private static DelegateBridge __Hotfix0_GetTraceTargetMapPosition; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Boolean movementAdjustable { get; }

	// RVA: 0x1daccb4 VA: 0x75943c4cb4
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1dacd1c VA: 0x75943c4d1c
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1dad0c8 VA: 0x75943c50c8
	public override Void OnProjectileStop() { }
	// RVA: 0x1dad188 VA: 0x75943c5188
	protected override Vector3 GetTraceTargetMapPosition() { }
	// RVA: 0x1dad254 VA: 0x75943c5254
	private Void OnDestroy() { }
	// RVA: 0x1dad304 VA: 0x75943c5304
	public Void .ctor() { }
	// RVA: 0x1dad37c VA: 0x75943c537c
	private Boolean <>xLuaBaseProxy_get_movementAdjustable() { }
	// RVA: 0x1dad384 VA: 0x75943c5384
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1dad38c VA: 0x75943c538c
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1dad394 VA: 0x75943c5394
	private Vector3 <>xLuaBaseProxy_GetTraceTargetMapPosition() { }
}
```
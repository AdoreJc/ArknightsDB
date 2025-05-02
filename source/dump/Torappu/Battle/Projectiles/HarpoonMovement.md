# HarpoonMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _speed`

- `Single _acceleration`

- `Boolean _stayWhenReached`

- `Boolean _keepUpdateDirection`

- `Boolean _independentUpdateAfterReached`

- `Single m_speed`


## Methods

- `Void Update()`

- `Void _UpdateSpeed(Single)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class HarpoonMovement : BasicMovement
{
	private Single _speed; // 0x94
	private Single _acceleration; // 0x98
	private Boolean _stayWhenReached; // 0x9c
	private Boolean _keepUpdateDirection; // 0x9d
	private Boolean _independentUpdateAfterReached; // 0x9e
	private Single m_speed; // 0xa0
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__UpdateSpeed; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Boolean movementAdjustable { get; }

	// RVA: 0x1da2200 VA: 0x75943ba200
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1da2264 VA: 0x75943ba264
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1da241c VA: 0x75943ba41c
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1da28f8 VA: 0x75943ba8f8
	private Void Update() { }
	// RVA: 0x1da286c VA: 0x75943ba86c
	private Void _UpdateSpeed(Single deltaTime) { }
	// RVA: 0x1da2994 VA: 0x75943ba994
	public Void .ctor() { }
	// RVA: 0x1da2a04 VA: 0x75943baa04
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1da2a0c VA: 0x75943baa0c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
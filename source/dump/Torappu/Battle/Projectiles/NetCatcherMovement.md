# NetCatcherMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _speed`

- `Single _acceleration`

- `Single m_speed`


## Methods

- `Void _UpdateSpeed(Single)`

- `Vector3 _GetAdsorptionPosition()`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class NetCatcherMovement : BasicMovement
{
	private Single _speed; // 0x94
	private Single _acceleration; // 0x98
	private Single m_speed; // 0x9c
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__UpdateSpeed; // 0x18
	private static DelegateBridge __Hotfix0__GetAdsorptionPosition; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Boolean movementAdjustable { get; }

	// RVA: 0x1da8ad0 VA: 0x75943c0ad0
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1da8b38 VA: 0x75943c0b38
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1da8e3c VA: 0x75943c0e3c
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1da9190 VA: 0x75943c1190
	private Void _UpdateSpeed(Single deltaTime) { }
	// RVA: 0x1da8ce4 VA: 0x75943c0ce4
	private Vector3 _GetAdsorptionPosition() { }
	// RVA: 0x1da9218 VA: 0x75943c1218
	public Void .ctor() { }
	// RVA: 0x1da9288 VA: 0x75943c1288
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1da9290 VA: 0x75943c1290
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
# AmiyaDefaultMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _startDistance`

- `Single _zOffset`

- `Single _startDuration`

- `Single _time`

- `Single m_velocityN`

- `Single m_remainingTime`

- `Boolean m_startPhaseFinished`


## Methods

- `Void <OnInit>b__10_0(Vector2)`

- `Void <OnInit>b__10_1()`

- `Void <OnInit>b__10_2()`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class AmiyaDefaultMovement : BasicMovement
{
	private const Single MIN_FULL_HEIGHT; // 0x0
	private Single _startDistance; // 0x94
	private Single _zOffset; // 0x98
	private Single _startDuration; // 0x9c
	private Single _time; // 0xa0
	private Single m_velocityN; // 0xa4
	private Single m_remainingTime; // 0xa8
	private Boolean m_startPhaseFinished; // 0xac
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Boolean movementAdjustable { get; }

	// RVA: 0x1d9b2fc VA: 0x75943b32fc
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1d9b360 VA: 0x75943b3360
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1d9b744 VA: 0x75943b3744
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d9ba0c VA: 0x75943b3a0c
	public Void .ctor() { }
	// RVA: 0x1d9ba88 VA: 0x75943b3a88
	private Void <OnInit>b__10_0(Vector2 pos) { }
	// RVA: 0x1d9bad0 VA: 0x75943b3ad0
	private Void <OnInit>b__10_1() { }
	// RVA: 0x1d9bae4 VA: 0x75943b3ae4
	private Void <OnInit>b__10_2() { }
	// RVA: 0x1d9baf8 VA: 0x75943b3af8
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1d9bb00 VA: 0x75943b3b00
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
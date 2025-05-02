# AmiyaS2Movement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _startDistance`

- `Single _zOffset`

- `Single _startDuration`

- `Single _time`

- `Single _yAnimateOffset`

- `Single _yAnimateSpeed`

- `Single m_velocityN`

- `Single m_remainingTime`

- `Boolean m_startPhaseFinished`

- `Single m_sinOffset`


## Methods

- `Void _UpdateBodyAnimation()`

- `Void <OnInit>b__13_0(Vector2)`

- `Void <OnInit>b__13_1()`

- `Void <OnInit>b__13_2()`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class AmiyaS2Movement : BasicMovement
{
	private const Single MIN_FULL_HEIGHT; // 0x0
	private Single _startDistance; // 0x94
	private Single _zOffset; // 0x98
	private Single _startDuration; // 0x9c
	private Single _time; // 0xa0
	private Single _yAnimateOffset; // 0xa4
	private Single _yAnimateSpeed; // 0xa8
	private Single m_velocityN; // 0xac
	private Single m_remainingTime; // 0xb0
	private Boolean m_startPhaseFinished; // 0xb4
	private Single m_sinOffset; // 0xb8
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__UpdateBodyAnimation; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Boolean movementAdjustable { get; }

	// RVA: 0x1d9bb08 VA: 0x75943b3b08
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1d9bb6c VA: 0x75943b3b6c
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1d9c000 VA: 0x75943b4000
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d9bf78 VA: 0x75943b3f78
	private Void _UpdateBodyAnimation() { }
	// RVA: 0x1d9c2f0 VA: 0x75943b42f0
	public Void .ctor() { }
	// RVA: 0x1d9c36c VA: 0x75943b436c
	private Void <OnInit>b__13_0(Vector2 pos) { }
	// RVA: 0x1d9c3b4 VA: 0x75943b43b4
	private Void <OnInit>b__13_1() { }
	// RVA: 0x1d9c3c8 VA: 0x75943b43c8
	private Void <OnInit>b__13_2() { }
	// RVA: 0x1d9c3dc VA: 0x75943b43dc
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1d9c3e4 VA: 0x75943b43e4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
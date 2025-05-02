# HoveringInPlaceMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _speed`

- `Single _radius`

- `Boolean _initKeepLastDirection`

- `Single m_moveSpeed`

- `Single m_angularSpeed`

- `Single m_radius`

- `Single m_angleCircle`

- `Single m_angleSemiCircle`

- `Vector3 m_initPosition`

- `Vector3 m_circleCenter`

- `Vector3 m_semicircleCenter`

- `Vector3 m_previousPosition`

- `Vector3 m_currentPosition`

- `Boolean m_inited`

- `HoveringStage m_hoveringStage`

- `Single m_semicircleStageTime`

- `Single m_curSpendTime`


## Methods

- `Void SetInitState()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class HoveringInPlaceMovement : BasicMovement
{
	private Single _speed; // 0x94
	private Single _radius; // 0x98
	private Boolean _initKeepLastDirection; // 0x9c
	private const Single PI; // 0x0
	private Single m_moveSpeed; // 0xa0
	private Single m_angularSpeed; // 0xa4
	private Single m_radius; // 0xa8
	private Single m_angleCircle; // 0xac
	private Single m_angleSemiCircle; // 0xb0
	private Vector3 m_initPosition; // 0xb4
	private Vector3 m_circleCenter; // 0xc0
	private Vector3 m_semicircleCenter; // 0xcc
	private Vector3 m_previousPosition; // 0xd8
	private Vector3 m_currentPosition; // 0xe4
	private Boolean m_inited; // 0xf0
	private HoveringStage m_hoveringStage; // 0xf4
	private Single m_semicircleStageTime; // 0xf8
	private Single m_curSpendTime; // 0xfc
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_SetInitState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Boolean movementAdjustable { get; }

	// RVA: 0x1da2a14 VA: 0x75943baa14
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1da2a78 VA: 0x75943baa78
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1da2bb0 VA: 0x75943babb0
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1da2fcc VA: 0x75943bafcc
	public Void SetInitState() { }
	// RVA: 0x1da3034 VA: 0x75943bb034
	public Void .ctor() { }
	// RVA: 0x1da30ac VA: 0x75943bb0ac
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1da30b4 VA: 0x75943bb0b4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
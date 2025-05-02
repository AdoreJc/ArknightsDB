# BouncedWithParacurveMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _raiseHeight`

- `Boolean _fixBaseOnTick`

- `Single m_gravity`

- `Single m_velocityN`

- `Boolean m_reachedTop`


## Methods

- `Vector3 _CalculateNextPosition(Single, Boolean)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnInitPose()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Boolean <>xLuaBaseProxy_DoCheckReachedInternal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class BouncedWithParacurveMovement : BouncedAdvancedMovement
{
	private const Single MIN_FULL_HEIGHT; // 0x0
	private const Single DIRECTION_ZERO_TOLERANCE; // 0x0
	private const Single TOO_CLOSE_THRESHOLD; // 0x0
	private Single _raiseHeight; // 0x120
	private Boolean _fixBaseOnTick; // 0x124
	private Single m_gravity; // 0x128
	private Single m_velocityN; // 0x12c
	private Boolean m_reachedTop; // 0x130
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnInitPose; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__CalculateNextPosition; // 0x18
	private static DelegateBridge __Hotfix0_DoCheckReachedInternal; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1d9edc8 VA: 0x75943b6dc8
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1d9f0e0 VA: 0x75943b70e0
	protected override Void OnInitPose() { }
	// RVA: 0x1d9f5cc VA: 0x75943b75cc
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d9f160 VA: 0x75943b7160
	private Vector3 _CalculateNextPosition(Single deltaTime, Boolean forceToResetDir) { }
	// RVA: 0x1d9f734 VA: 0x75943b7734
	protected override Boolean DoCheckReachedInternal() { }
	// RVA: 0x1d9f850 VA: 0x75943b7850
	public Void .ctor() { }
	// RVA: 0x1d9f8c4 VA: 0x75943b78c4
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1d9f8c8 VA: 0x75943b78c8
	private Void <>xLuaBaseProxy_OnInitPose() { }
	// RVA: 0x1d9f8d0 VA: 0x75943b78d0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d9f8d4 VA: 0x75943b78d4
	private Boolean <>xLuaBaseProxy_DoCheckReachedInternal() { }
}
```
# ArcCircleRange

**Namespace:** `Torappu.Battle`


## Fields

- `CircleCollider2D m_circleCollider`


## Methods

- `Boolean _CheckDegRangeValid()`

- `Boolean _CheckDegInRange(Single)`

- `Void <>xLuaBaseProxy_InitCollidersIfNot(Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ArcCircleRange : PhysicsRange
{
	private Vector2[] _degreeRanges; // 0x38
	private CircleCollider2D m_circleCollider; // 0x40
	private static DelegateBridge __Hotfix0_get_degreeRanges; // 0x0
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x8
	private static DelegateBridge __Hotfix0_InitCollidersIfNot; // 0x10
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x18
	private static DelegateBridge __Hotfix0_FindTiles; // 0x20
	private static DelegateBridge __Hotfix0__CheckDegRangeValid; // 0x28
	private static DelegateBridge __Hotfix0__CheckDegInRange; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Vector2[] degreeRanges { get; }

	// RVA: 0x1b8b348 VA: 0x75941a3348
	public Vector2[] get_degreeRanges() { }
	// RVA: 0x1b8b3b0 VA: 0x75941a33b0
	protected override Collider2D[] FetchColliders(Options options) { }
	// RVA: 0x1b8b620 VA: 0x75941a3620
	protected override Void InitCollidersIfNot(Options options) { }
	// RVA: 0x1b8bab0 VA: 0x75941a3ab0
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 mapPos, TargetOptions options, Func`2 validator) { }
	// RVA: 0x1b8c278 VA: 0x75941a4278
	public override List`1 FindTiles(Vector2 mapPos, Func`2 validator) { }
	// RVA: 0x1b8b94c VA: 0x75941a394c
	private Boolean _CheckDegRangeValid() { }
	// RVA: 0x1b8c70c VA: 0x75941a470c
	private Boolean _CheckDegInRange(Single angle) { }
	// RVA: 0x1b8c874 VA: 0x75941a4874
	public Void .ctor() { }
	// RVA: 0x1b8c988 VA: 0x75941a4988
	private Collider2D[] <>xLuaBaseProxy_FetchColliders(Options P0) { }
	// RVA: 0x1b8c9b4 VA: 0x75941a49b4
	private Void <>xLuaBaseProxy_InitCollidersIfNot(Options P0) { }
	// RVA: 0x1b8c9e0 VA: 0x75941a49e0
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0, TargetOptions P1, Func`2 P2) { }
	// RVA: 0x1b8ca38 VA: 0x75941a4a38
	private List`1 <>xLuaBaseProxy_FindTiles(Vector2 P0, Func`2 P1) { }
}
```
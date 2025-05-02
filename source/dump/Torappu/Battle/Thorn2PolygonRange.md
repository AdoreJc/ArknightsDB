# Thorn2PolygonRange

**Namespace:** `Torappu.Battle`


## Fields

- `Single _polygonLineColliderWide`

- `Single _polygonColliderOffset`

- `Vector2 m_boxCenter`

- `FP m_boxWidth`

- `FP m_boxLength`

- `BoxCollider2D m_boxCollider`


## Methods

- `Void InitPolygonCollidersIfNot(GridPosition)`

- `Void _DoCalculateHull(List`1, ref)`

- `Void _OptimizeLineCollider(ref)`

- `Single _Cross(Vector2, Vector2, Vector2)`

- `Void _GetBoxColliderData()`

- `Void _SetBoxCollider(GridPosition)`

- `Boolean <>xLuaBaseProxy_get_extendable()`

- `Boolean <>xLuaBaseProxy_CheckTargetIn(ILocatable)`

- `Void <>xLuaBaseProxy_UpdateExtend(FP, Boolean)`

- `Void <>xLuaBaseProxy_OnInit(Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Thorn2PolygonRange : PhysicsRange
{
	public static readonly Int32 MAX_POLYGON_POINT_COUNT; // 0x0
	private Single _polygonLineColliderWide; // 0x38
	private Single _polygonColliderOffset; // 0x3c
	private Vector2 m_boxCenter; // 0x40
	private FP m_boxWidth; // 0x48
	private FP m_boxLength; // 0x50
	private BoxCollider2D m_boxCollider; // 0x58
	private List`1 m_resultOrigin; // 0x60
	private List`1 m_inputTiles; // 0x68
	private List`1 m_input; // 0x70
	private List`1 m_result; // 0x78
	private List`1 m_stack; // 0x80
	private static DelegateBridge __Hotfix0_get_extendable; // 0x8
	private static DelegateBridge __Hotfix0_get_inputPoints; // 0x10
	private static DelegateBridge __Hotfix0_get_resultForEffect; // 0x18
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x20
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x28
	private static DelegateBridge __Hotfix0_UpdateExtend; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x38
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x40
	private static DelegateBridge __Hotfix0_InitPolygonCollidersIfNot; // 0x48
	private static DelegateBridge __Hotfix0__DoCalculateHull; // 0x50
	private static DelegateBridge __Hotfix0__OptimizeLineCollider; // 0x58
	private static DelegateBridge __Hotfix0__Cross; // 0x60
	private static DelegateBridge __Hotfix0__GetBoxColliderData; // 0x68
	private static DelegateBridge __Hotfix0__SetBoxCollider; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override Boolean extendable { get; }
	public List`1 inputPoints { get; }
	public List`1 resultForEffect { get; }

	// RVA: 0x1b95d00 VA: 0x75941add00
	public override Boolean get_extendable() { }
	// RVA: 0x1b95d74 VA: 0x75941add74
	public List`1 get_inputPoints() { }
	// RVA: 0x1b95dec VA: 0x75941addec
	public List`1 get_resultForEffect() { }
	// RVA: 0x1b95e64 VA: 0x75941ade64
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1b95eec VA: 0x75941adeec
	protected override Collider2D[] FetchColliders(Options options) { }
	// RVA: 0x1b960ac VA: 0x75941ae0ac
	protected override Void UpdateExtend(FP extend, Boolean force) { }
	// RVA: 0x1b9613c VA: 0x75941ae13c
	protected override Void OnInit(Options options) { }
	// RVA: 0x1b96238 VA: 0x75941ae238
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 mapPos, TargetOptions options, Func`2 validator) { }
	// RVA: 0x1b9662c VA: 0x75941ae62c
	public Void InitPolygonCollidersIfNot(GridPosition pos) { }
	// RVA: 0x1b96884 VA: 0x75941ae884
	private Void _DoCalculateHull(List`1 input, ref List`1 result) { }
	// RVA: 0x1b96ef0 VA: 0x75941aeef0
	private Void _OptimizeLineCollider(ref List`1 result) { }
	// RVA: 0x1b97b3c VA: 0x75941afb3c
	private Single _Cross(Vector2 a, Vector2 b, Vector2 c) { }
	// RVA: 0x1b974d4 VA: 0x75941af4d4
	private Void _GetBoxColliderData() { }
	// RVA: 0x1b979a0 VA: 0x75941af9a0
	private Void _SetBoxCollider(GridPosition pos) { }
	// RVA: 0x1b97c20 VA: 0x75941afc20
	public Void .ctor() { }
	// RVA: 0x1b97dd4 VA: 0x75941afdd4
	private static Void .cctor() { }
	// RVA: 0x1b97e20 VA: 0x75941afe20
	private Boolean <>xLuaBaseProxy_get_extendable() { }
	// RVA: 0x1b97e24 VA: 0x75941afe24
	private Boolean <>xLuaBaseProxy_CheckTargetIn(ILocatable P0) { }
	// RVA: 0x1b97e28 VA: 0x75941afe28
	private Collider2D[] <>xLuaBaseProxy_FetchColliders(Options P0) { }
	// RVA: 0x1b97e54 VA: 0x75941afe54
	private Void <>xLuaBaseProxy_UpdateExtend(FP P0, Boolean P1) { }
	// RVA: 0x1b97e5c VA: 0x75941afe5c
	private Void <>xLuaBaseProxy_OnInit(Options P0) { }
	// RVA: 0x1b97e88 VA: 0x75941afe88
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0, TargetOptions P1, Func`2 P2) { }
}
```
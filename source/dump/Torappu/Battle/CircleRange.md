# CircleRange

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _scaleble`

- `CircleCollider2D m_circleCollider`

- `Single m_originRadius`


## Properties

- `Single radius`


## Methods

- `Single get_radius()`

- `Void <>xLuaBaseProxy_UpdateExtend(FP, Boolean)`

- `Void <>xLuaBaseProxy_InitCollidersIfNot(Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CircleRange : PhysicsRange
{
	private Boolean _scaleble; // 0x38
	protected CircleCollider2D m_circleCollider; // 0x40
	protected Single m_originRadius; // 0x48
	private static DelegateBridge __Hotfix0_get_radius; // 0x0
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x8
	private static DelegateBridge __Hotfix0_UpdateExtend; // 0x10
	private static DelegateBridge __Hotfix0_InitCollidersIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Single radius { get; }

	// RVA: 0x1b8e224 VA: 0x75941a6224
	public Single get_radius() { }
	// RVA: 0x1b8e298 VA: 0x75941a6298
	protected override Collider2D[] FetchColliders(Options options) { }
	// RVA: 0x1b8e454 VA: 0x75941a6454
	protected override Void UpdateExtend(FP extend, Boolean force) { }
	// RVA: 0x1b8e5c4 VA: 0x75941a65c4
	protected override Void InitCollidersIfNot(Options options) { }
	// RVA: 0x1b8e874 VA: 0x75941a6874
	public Void .ctor() { }
	// RVA: 0x1b8e8e0 VA: 0x75941a68e0
	private Collider2D[] <>xLuaBaseProxy_FetchColliders(Options P0) { }
	// RVA: 0x1b8e90c VA: 0x75941a690c
	private Void <>xLuaBaseProxy_UpdateExtend(FP P0, Boolean P1) { }
	// RVA: 0x1b8eb88 VA: 0x75941a6b88
	private Void <>xLuaBaseProxy_InitCollidersIfNot(Options P0) { }
}
```
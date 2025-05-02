# AutoLoadBoxRange

**Namespace:** `Torappu.Battle`


## Fields

- `String m_loadedRangeId`


## Properties

- `String loadedRangeId`


## Methods

- `String get_loadedRangeId()`

- `Void InitColliderIfNotByRangeId(String, Options)`

- `Void <>xLuaBaseProxy_InitCollidersIfNot(Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AutoLoadBoxRange : PhysicsRange
{
	protected String m_loadedRangeId; // 0x38
	private static DelegateBridge __Hotfix0_get_loadedRangeId; // 0x0
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x8
	private static DelegateBridge __Hotfix0_InitCollidersIfNot; // 0x10
	private static DelegateBridge __Hotfix0_FetchCollidersByRangeId; // 0x18
	private static DelegateBridge __Hotfix0_InitColliderIfNotByRangeId; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String loadedRangeId { get; }

	// RVA: 0x1b8ca3c VA: 0x75941a4a3c
	public String get_loadedRangeId() { }
	// RVA: 0x1b8b2a0 VA: 0x75941a32a0
	protected override Collider2D[] FetchColliders(Options options) { }
	// RVA: 0x1b8b1cc VA: 0x75941a31cc
	protected override Void InitCollidersIfNot(Options options) { }
	// RVA: 0x1b8ad04 VA: 0x75941a2d04
	protected Collider2D[] FetchCollidersByRangeId(String rangeId, Options options) { }
	// RVA: 0x1b8a71c VA: 0x75941a271c
	protected Void InitColliderIfNotByRangeId(String rangeId, Options options) { }
	// RVA: 0x1b8b108 VA: 0x75941a3108
	public Void .ctor() { }
	// RVA: 0x1b8caa4 VA: 0x75941a4aa4
	private Collider2D[] <>xLuaBaseProxy_FetchColliders(Options P0) { }
	// RVA: 0x1b8cad0 VA: 0x75941a4ad0
	private Void <>xLuaBaseProxy_InitCollidersIfNot(Options P0) { }
}
```
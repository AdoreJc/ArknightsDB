# PhysicsRange

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _extendable`


## Methods

- `Void <>xLuaBaseProxy_UpdateRangeByOptions(Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class PhysicsRange : Range
{
	private Boolean _extendable; // 0x20
	protected Collider2D[] m_colliders; // 0x28
	private BoxColliderData[] m_originBoxColliderData; // 0x30
	private static DelegateBridge __Hotfix0_get_extendable; // 0x0
	private static DelegateBridge __Hotfix0_set_extendable; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_UpdateExtend; // 0x18
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x20
	private static DelegateBridge __Hotfix0_FindTiles; // 0x28
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x30
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x38
	private static DelegateBridge __Hotfix0_InitCollidersIfNot; // 0x40
	private static DelegateBridge __Hotfix0_UpdateRangeByOptions; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override Boolean extendable { get; set; }

	// RVA: 0x1b94d78 VA: 0x75941acd78
	public override Boolean get_extendable() { }
	// RVA: 0x1b94de0 VA: 0x75941acde0
	public override Void set_extendable(Boolean value) { }
	// RVA: 0x1b8a5bc VA: 0x75941a25bc
	protected override Void OnInit(Options options) { }
	// RVA: 0x1b8e914 VA: 0x75941a6914
	protected override Void UpdateExtend(FP extend, Boolean force) { }
	// RVA: 0x1b8bdd4 VA: 0x75941a3dd4
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 mapPos, TargetOptions options, Func`2 validator) { }
	// RVA: 0x1b8c584 VA: 0x75941a4584
	public override List`1 FindTiles(Vector2 mapPos, Func`2 validator) { }
	// RVA: 0x1b922b0 VA: 0x75941aa2b0
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1b8b56c VA: 0x75941a356c
	protected virtual Collider2D[] FetchColliders(Options options) { }
	// RVA: 0x1b8b724 VA: 0x75941a3724
	protected virtual Void InitCollidersIfNot(Options options) { }
	// RVA: 0x1b94e60 VA: 0x75941ace60
	public override Void UpdateRangeByOptions(Options options) { }
	// RVA: 0x1b8c91c VA: 0x75941a491c
	public Void .ctor() { }
	// RVA: 0x1b94fc0 VA: 0x75941acfc0
	private Void <>xLuaBaseProxy_UpdateRangeByOptions(Options P0) { }
}
```
# SimpleTraceTargetAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _updateDistSqrEps`

- `Boolean _findNearbyReachableTile`

- `Vector2 m_lastMapPosition`


## Methods

- `Boolean _CheckTarget(Entity)`

- `Void _UpdateTraceTarget()`

- `Void _CleanTraceTarget()`

- `Boolean _TryUpdateTraceTargetRoute(Entity)`

- `Boolean <>xLuaBaseProxy_get_enableTraceTarget()`

- `Category <>xLuaBaseProxy_get_category()`

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `Boolean <>xLuaBaseProxy_get_isReady()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_StopAffect()`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SimpleTraceTargetAbility : BaseTraceTargetAbility
{
	private Single _updateDistSqrEps; // 0x134
	private Boolean _findNearbyReachableTile; // 0x138
	private Vector2 m_lastMapPosition; // 0x13c
	private static DelegateBridge __Hotfix0_get_enableTraceTarget; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x10
	private static DelegateBridge __Hotfix0_get_isReady; // 0x18
	private static DelegateBridge __Hotfix0_OnAttached; // 0x20
	private static DelegateBridge __Hotfix0_OnDetached; // 0x28
	private static DelegateBridge __Hotfix0_StopAffect; // 0x30
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0__CheckTarget; // 0x48
	private static DelegateBridge __Hotfix0__UpdateTraceTarget; // 0x50
	private static DelegateBridge __Hotfix0__CleanTraceTarget; // 0x58
	private static DelegateBridge __Hotfix0__TryUpdateTraceTargetRoute; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override Boolean enableTraceTarget { get; }
	public override Category category { get; }
	public override Boolean isAffecting { get; }
	public override Boolean isReady { get; }

	// RVA: 0x1eb0404 VA: 0x75944c8404
	public override Boolean get_enableTraceTarget() { }
	// RVA: 0x1eb0488 VA: 0x75944c8488
	public override Category get_category() { }
	// RVA: 0x1eb04f0 VA: 0x75944c84f0
	public override Boolean get_isAffecting() { }
	// RVA: 0x1eb058c VA: 0x75944c858c
	public override Boolean get_isReady() { }
	// RVA: 0x1eb05f8 VA: 0x75944c85f8
	protected override Void OnAttached() { }
	// RVA: 0x1eb06a8 VA: 0x75944c86a8
	protected override Void OnDetached() { }
	// RVA: 0x1eb0728 VA: 0x75944c8728
	public override Void StopAffect() { }
	// RVA: 0x1eb08a8 VA: 0x75944c88a8
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1eb0cec VA: 0x75944c8cec
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1eb1040 VA: 0x75944c9040
	private Boolean _CheckTarget(Entity entity) { }
	// RVA: 0x1eb0de4 VA: 0x75944c8de4
	private Void _UpdateTraceTarget() { }
	// RVA: 0x1eb07f4 VA: 0x75944c87f4
	private Void _CleanTraceTarget() { }
	// RVA: 0x1eb0978 VA: 0x75944c8978
	private Boolean _TryUpdateTraceTargetRoute(Entity validTarget) { }
	// RVA: 0x1eb111c VA: 0x75944c911c
	public Void .ctor() { }
	// RVA: 0x1eb119c VA: 0x75944c919c
	private Boolean <>xLuaBaseProxy_get_enableTraceTarget() { }
	// RVA: 0x1eb11a4 VA: 0x75944c91a4
	private Category <>xLuaBaseProxy_get_category() { }
	// RVA: 0x1eb11ac VA: 0x75944c91ac
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x1eb11b4 VA: 0x75944c91b4
	private Boolean <>xLuaBaseProxy_get_isReady() { }
	// RVA: 0x1eb11bc VA: 0x75944c91bc
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1eb11c4 VA: 0x75944c91c4
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1eb11cc VA: 0x75944c91cc
	private Void <>xLuaBaseProxy_StopAffect() { }
	// RVA: 0x1eb11d4 VA: 0x75944c91d4
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1eb11dc VA: 0x75944c91dc
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
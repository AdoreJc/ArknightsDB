# EnemyTraceEnemyAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TeamSideEnemy m_ownerTs`


## Properties

- `TeamSideEnemy ownerTs`


## Methods

- `TeamSideEnemy get_ownerTs()`

- `Void _OnUnitFinish(Object)`

- `Boolean _CanTargetBeTraced(Entity)`

- `Boolean _IsTraceTileReachable()`

- `Void _UpdateTraceTarget()`

- `Boolean _CheckCurrentTraceTarget()`

- `Boolean _UpdateTraceTargetRoute(Entity)`

- `Boolean _CanUseAttack(Entity)`

- `Boolean _SelectorVerifyTarget(TargetSelector, Entity)`

- `TeamSideEnemy _SearchTraceTarget()`

- `Void _RegisterTraceTarget(TeamSideEnemy)`

- `Category <>xLuaBaseProxy_get_category()`

- `FP <>xLuaBaseProxy_get_cooldown()`

- `SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource()`

- `SelectTargetTiming <>xLuaBaseProxy_get_selectTargetTiming()`

- `Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget()`

- `Boolean <>xLuaBaseProxy_get_allowNoTarget()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay()`

- `Boolean <>xLuaBaseProxy_get_usingTraceCursor()`

- `Entity <>xLuaBaseProxy_get_traceTarget()`

- `Void <>xLuaBaseProxy_set_traceTarget(Entity)`

- `TracePositionCursor <>xLuaBaseProxy_get_tracePositionCursor()`

- `Boolean <>xLuaBaseProxy_get_hasTraceTarget()`

- `Boolean <>xLuaBaseProxy_get_enableTraceTarget()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class EnemyTraceEnemyAbility : BaseTraceTargetAbility
{
	private const Single DEFAULT_SEARCH_COOL_DOWN; // 0x0
	private TeamSideEnemy m_ownerTs; // 0x138
	private readonly List`1 m_candidateEntities; // 0x140
	private static DelegateBridge __Hotfix0_get_category; // 0x0
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetTiming; // 0x18
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x20
	private static DelegateBridge __Hotfix0_get_allowNoTarget; // 0x28
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x30
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x40
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x48
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x50
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x58
	private static DelegateBridge __Hotfix0_get_ownerTs; // 0x60
	private static DelegateBridge __Hotfix0_get_usingTraceCursor; // 0x68
	private static DelegateBridge __Hotfix0_get_traceTarget; // 0x70
	private static DelegateBridge __Hotfix0_set_traceTarget; // 0x78
	private static DelegateBridge __Hotfix0_get_tracePositionCursor; // 0x80
	private static DelegateBridge __Hotfix0_get_hasTraceTarget; // 0x88
	private static DelegateBridge __Hotfix0_get_enableTraceTarget; // 0x90
	private static DelegateBridge __Hotfix0_OnAttached; // 0x98
	private static DelegateBridge __Hotfix0_OnDetached; // 0xa0
	private static DelegateBridge __Hotfix0_CastDirectly; // 0xa8
	private static DelegateBridge __Hotfix0_CastToTarget; // 0xb0
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0xb8
	private static DelegateBridge __Hotfix0_DoSetData; // 0xc0
	private static DelegateBridge __Hotfix0_Reset; // 0xc8
	private static DelegateBridge __Hotfix0_OnTick; // 0xd0
	private static DelegateBridge __Hotfix0__CanTargetBeTraced; // 0xd8
	private static DelegateBridge __Hotfix0__IsTraceTileReachable; // 0xe0
	private static DelegateBridge __Hotfix0__UpdateTraceTarget; // 0xe8
	private static DelegateBridge __Hotfix0__CheckCurrentTraceTarget; // 0xf0
	private static DelegateBridge __Hotfix0__UpdateTraceTargetRoute; // 0xf8
	private static DelegateBridge __Hotfix0__CanUseAttack; // 0x100
	private static DelegateBridge __Hotfix0__SelectorVerifyTarget; // 0x108
	private static DelegateBridge __Hotfix0__SearchTraceTarget; // 0x110
	private static DelegateBridge __Hotfix0__RegisterTraceTarget; // 0x118
	private static DelegateBridge _c__Hotfix0_ctor; // 0x120

	public override Category category { get; }
	public override FP cooldown { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override SelectTargetTiming selectTargetTiming { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public override Boolean allowNoTarget { get; }
	private TeamSideEnemy ownerTs { get; }
	public override Boolean usingTraceCursor { get; }
	public override Entity traceTarget { get; set; }
	protected override TracePositionCursor tracePositionCursor { get; }
	public override Boolean hasTraceTarget { get; }
	public override Boolean enableTraceTarget { get; }

	// RVA: 0x1e70f6c VA: 0x7594488f6c
	public override Category get_category() { }
	// RVA: 0x1e70fd4 VA: 0x7594488fd4
	public override FP get_cooldown() { }
	// RVA: 0x1e71064 VA: 0x7594489064
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e710cc VA: 0x75944890cc
	public override SelectTargetTiming get_selectTargetTiming() { }
	// RVA: 0x1e71130 VA: 0x7594489130
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e71194 VA: 0x7594489194
	public override Boolean get_allowNoTarget() { }
	// RVA: 0x1e711f8 VA: 0x75944891f8
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e7125c VA: 0x759448925c
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e712c0 VA: 0x75944892c0
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e71338 VA: 0x7594489338
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e713b8 VA: 0x75944893b8
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e7147c VA: 0x759448947c
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e71540 VA: 0x7594489540
	private TeamSideEnemy get_ownerTs() { }
	// RVA: 0x1e71684 VA: 0x7594489684
	public override Boolean get_usingTraceCursor() { }
	// RVA: 0x1e7175c VA: 0x759448975c
	public override Entity get_traceTarget() { }
	// RVA: 0x1e71810 VA: 0x7594489810
	public override Void set_traceTarget(Entity value) { }
	// RVA: 0x1e71894 VA: 0x7594489894
	protected override TracePositionCursor get_tracePositionCursor() { }
	// RVA: 0x1e7197c VA: 0x759448997c
	public override Boolean get_hasTraceTarget() { }
	// RVA: 0x1e71a6c VA: 0x7594489a6c
	public override Boolean get_enableTraceTarget() { }
	// RVA: 0x1e71b08 VA: 0x7594489b08
	protected override Void OnAttached() { }
	// RVA: 0x1e71c30 VA: 0x7594489c30
	protected override Void OnDetached() { }
	// RVA: 0x1e71d58 VA: 0x7594489d58
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean isFirstAttack) { }
	// RVA: 0x1e71ebc VA: 0x7594489ebc
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean isFirstAttack) { }
	// RVA: 0x1e72028 VA: 0x759448a028
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x1e7228c VA: 0x759448a28c
	protected override Void DoSetData(Entity entity, Options option) { }
	// RVA: 0x1e72334 VA: 0x759448a334
	protected override Void Reset() { }
	// RVA: 0x1e723fc VA: 0x759448a3fc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e72624 VA: 0x759448a624
	private Boolean _CanTargetBeTraced(Entity entity) { }
	// RVA: 0x1e728ec VA: 0x759448a8ec
	private Boolean _IsTraceTileReachable() { }
	// RVA: 0x1e72520 VA: 0x759448a520
	private Void _UpdateTraceTarget() { }
	// RVA: 0x1e72a44 VA: 0x759448aa44
	private Boolean _CheckCurrentTraceTarget() { }
	// RVA: 0x1e72d64 VA: 0x759448ad64
	private Boolean _UpdateTraceTargetRoute(Entity candidate) { }
	// RVA: 0x1e72728 VA: 0x759448a728
	private Boolean _CanUseAttack(Entity entity) { }
	// RVA: 0x1e72ed0 VA: 0x759448aed0
	private Boolean _SelectorVerifyTarget(TargetSelector targetSelector, Entity entity) { }
	// RVA: 0x1e72c24 VA: 0x759448ac24
	private TeamSideEnemy _SearchTraceTarget() { }
	// RVA: 0x1e72198 VA: 0x759448a198
	private Void _RegisterTraceTarget(TeamSideEnemy entity) { }
	// RVA: 0x1e73024 VA: 0x759448b024
	public Void .ctor() { }
	// RVA: 0x1e730e4 VA: 0x759448b0e4
	private Category <>xLuaBaseProxy_get_category() { }
	// RVA: 0x1e730e8 VA: 0x759448b0e8
	private FP <>xLuaBaseProxy_get_cooldown() { }
	// RVA: 0x1e730ec VA: 0x759448b0ec
	private SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource() { }
	// RVA: 0x1e730f0 VA: 0x759448b0f0
	private SelectTargetTiming <>xLuaBaseProxy_get_selectTargetTiming() { }
	// RVA: 0x1e730f4 VA: 0x759448b0f4
	private Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget() { }
	// RVA: 0x1e730f8 VA: 0x759448b0f8
	private Boolean <>xLuaBaseProxy_get_allowNoTarget() { }
	// RVA: 0x1e730fc VA: 0x759448b0fc
	private IList`1 <>xLuaBaseProxy_GetPassiveBuffs() { }
	// RVA: 0x1e73100 VA: 0x759448b100
	private IList`1 <>xLuaBaseProxy_GetActiveBuffs() { }
	// RVA: 0x1e73104 VA: 0x759448b104
	private IList`1 <>xLuaBaseProxy_GetEventActions(Event P0) { }
	// RVA: 0x1e73108 VA: 0x759448b108
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1e7310c VA: 0x759448b10c
	private IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay() { }
	// RVA: 0x1e73110 VA: 0x759448b110
	private IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay() { }
	// RVA: 0x1e73114 VA: 0x759448b114
	private Boolean <>xLuaBaseProxy_get_usingTraceCursor() { }
	// RVA: 0x1e73118 VA: 0x759448b118
	private Entity <>xLuaBaseProxy_get_traceTarget() { }
	// RVA: 0x1e7311c VA: 0x759448b11c
	private Void <>xLuaBaseProxy_set_traceTarget(Entity P0) { }
	// RVA: 0x1e73120 VA: 0x759448b120
	private TracePositionCursor <>xLuaBaseProxy_get_tracePositionCursor() { }
	// RVA: 0x1e73124 VA: 0x759448b124
	private Boolean <>xLuaBaseProxy_get_hasTraceTarget() { }
	// RVA: 0x1e73128 VA: 0x759448b128
	private Boolean <>xLuaBaseProxy_get_enableTraceTarget() { }
	// RVA: 0x1e7312c VA: 0x759448b12c
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e73130 VA: 0x759448b130
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e73134 VA: 0x759448b134
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1e73140 VA: 0x759448b140
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e7314c VA: 0x759448b14c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e73170 VA: 0x759448b170
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e73178 VA: 0x759448b178
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
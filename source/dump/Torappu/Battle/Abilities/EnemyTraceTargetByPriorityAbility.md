# EnemyTraceTargetByPriorityAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _defaultSearchCoolDown`

- `String _defaultCooldownKey`

- `GroupSelector _traceTargetSelectors`

- `TileSelector _defaultTileSelector`

- `Boolean _removeTraceTargetWhenReached`

- `PeriodicTimer m_defaultTracingCooldownTimer`

- `Boolean isDefaultTracing`


## Methods

- `Boolean CheckTraceTargetInAttackRange()`

- `Void _DoFindTargetByPriority()`

- `Void _DoFindTileByDefault()`

- `Boolean _CheckCurrentTraceTile()`

- `Boolean _CheckCurrentTraceTarget()`

- `Boolean _CanUseAttack(Entity)`

- `Boolean _SelectorVerifyTarget(TargetSelector, Entity)`

- `Boolean _CanTargetBeTraced(Entity)`

- `Boolean _IsTraceTileReachable()`

- `Void _OnUnitFinish(Object)`

- `Void _RegisterTraceTarget(Entity)`

- `Boolean _UpdateTraceTargetRoute(Entity)`

- `TracePositionCursor <>xLuaBaseProxy_get_tracePositionCursor()`

- `Category <>xLuaBaseProxy_get_category()`

- `FP <>xLuaBaseProxy_get_cooldown()`

- `SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource()`

- `SelectTargetTiming <>xLuaBaseProxy_get_selectTargetTiming()`

- `Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget()`

- `Boolean <>xLuaBaseProxy_get_allowNoTarget()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class EnemyTraceTargetByPriorityAbility : BaseTraceTargetAbility
{
	private Single _defaultSearchCoolDown; // 0x134
	private String _defaultCooldownKey; // 0x138
	private GroupSelector _traceTargetSelectors; // 0x140
	private TileSelector _defaultTileSelector; // 0x148
	private Boolean _removeTraceTargetWhenReached; // 0x150
	protected PeriodicTimer m_defaultTracingCooldownTimer; // 0x158
	private readonly List`1 m_candidateEntities; // 0x160
	private Boolean isDefaultTracing; // 0x168
	private static DelegateBridge __Hotfix0_get_tracePositionCursor; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x18
	private static DelegateBridge __Hotfix0_get_selectTargetTiming; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x28
	private static DelegateBridge __Hotfix0_get_allowNoTarget; // 0x30
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x40
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x48
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x50
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x58
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x60
	private static DelegateBridge __Hotfix0_DoSetData; // 0x68
	private static DelegateBridge __Hotfix0_Reset; // 0x70
	private static DelegateBridge __Hotfix0_OnAttached; // 0x78
	private static DelegateBridge __Hotfix0_OnDetached; // 0x80
	private static DelegateBridge __Hotfix0_CastDirectly; // 0x88
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x90
	private static DelegateBridge __Hotfix0_OnTick; // 0x98
	private static DelegateBridge __Hotfix0_CheckTraceTargetInAttackRange; // 0xa0
	private static DelegateBridge __Hotfix0__DoFindTargetByPriority; // 0xa8
	private static DelegateBridge __Hotfix0__DoFindTileByDefault; // 0xb0
	private static DelegateBridge __Hotfix0__CheckCurrentTraceTile; // 0xb8
	private static DelegateBridge __Hotfix0__CheckCurrentTraceTarget; // 0xc0
	private static DelegateBridge __Hotfix0__CanUseAttack; // 0xc8
	private static DelegateBridge __Hotfix0__SelectorVerifyTarget; // 0xd0
	private static DelegateBridge __Hotfix0__CanTargetBeTraced; // 0xd8
	private static DelegateBridge __Hotfix0__IsTraceTileReachable; // 0xe0
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0xe8
	private static DelegateBridge __Hotfix0__RegisterTraceTarget; // 0xf0
	private static DelegateBridge __Hotfix0__UpdateTraceTargetRoute; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	protected override TracePositionCursor tracePositionCursor { get; }
	public override Category category { get; }
	public override FP cooldown { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override SelectTargetTiming selectTargetTiming { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public override Boolean allowNoTarget { get; }

	// RVA: 0x1e73358 VA: 0x759448b358
	protected override TracePositionCursor get_tracePositionCursor() { }
	// RVA: 0x1e73440 VA: 0x759448b440
	public override Category get_category() { }
	// RVA: 0x1e734a8 VA: 0x759448b4a8
	public override FP get_cooldown() { }
	// RVA: 0x1e73548 VA: 0x759448b548
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e735b0 VA: 0x759448b5b0
	public override SelectTargetTiming get_selectTargetTiming() { }
	// RVA: 0x1e73614 VA: 0x759448b614
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e73678 VA: 0x759448b678
	public override Boolean get_allowNoTarget() { }
	// RVA: 0x1e736dc VA: 0x759448b6dc
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e73740 VA: 0x759448b740
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e737a4 VA: 0x759448b7a4
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e7381c VA: 0x759448b81c
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e7389c VA: 0x759448b89c
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e73960 VA: 0x759448b960
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e73a24 VA: 0x759448ba24
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e73c18 VA: 0x759448bc18
	protected override Void Reset() { }
	// RVA: 0x1e73d40 VA: 0x759448bd40
	protected override Void OnAttached() { }
	// RVA: 0x1e73e50 VA: 0x759448be50
	protected override Void OnDetached() { }
	// RVA: 0x1e73f60 VA: 0x759448bf60
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean isFirstAttack) { }
	// RVA: 0x1e740c4 VA: 0x759448c0c4
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean isFirstAttack) { }
	// RVA: 0x1e74230 VA: 0x759448c230
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e74eb8 VA: 0x759448ceb8
	public Boolean CheckTraceTargetInAttackRange() { }
	// RVA: 0x1e74aa4 VA: 0x759448caa4
	private Void _DoFindTargetByPriority() { }
	// RVA: 0x1e74d38 VA: 0x759448cd38
	private Void _DoFindTileByDefault() { }
	// RVA: 0x1e74540 VA: 0x759448c540
	private Boolean _CheckCurrentTraceTile() { }
	// RVA: 0x1e7460c VA: 0x759448c60c
	private Boolean _CheckCurrentTraceTarget() { }
	// RVA: 0x1e75558 VA: 0x759448d558
	private Boolean _CanUseAttack(Entity entity) { }
	// RVA: 0x1e7571c VA: 0x759448d71c
	private Boolean _SelectorVerifyTarget(TargetSelector targetSelector, Entity entity) { }
	// RVA: 0x1e75218 VA: 0x759448d218
	private Boolean _CanTargetBeTraced(Entity entity) { }
	// RVA: 0x1e750c0 VA: 0x759448d0c0
	private Boolean _IsTraceTileReachable() { }
	// RVA: 0x1e75870 VA: 0x759448d870
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x1e74fc0 VA: 0x759448cfc0
	private Void _RegisterTraceTarget(Entity entity) { }
	// RVA: 0x1e752f4 VA: 0x759448d2f4
	private Boolean _UpdateTraceTargetRoute(Entity candidate) { }
	// RVA: 0x1e759e0 VA: 0x759448d9e0
	public Void .ctor() { }
	// RVA: 0x1e75ad8 VA: 0x759448dad8
	private TracePositionCursor <>xLuaBaseProxy_get_tracePositionCursor() { }
	// RVA: 0x1e75adc VA: 0x759448dadc
	private Category <>xLuaBaseProxy_get_category() { }
	// RVA: 0x1e75ae0 VA: 0x759448dae0
	private FP <>xLuaBaseProxy_get_cooldown() { }
	// RVA: 0x1e75ae4 VA: 0x759448dae4
	private SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource() { }
	// RVA: 0x1e75ae8 VA: 0x759448dae8
	private SelectTargetTiming <>xLuaBaseProxy_get_selectTargetTiming() { }
	// RVA: 0x1e75aec VA: 0x759448daec
	private Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget() { }
	// RVA: 0x1e75af0 VA: 0x759448daf0
	private Boolean <>xLuaBaseProxy_get_allowNoTarget() { }
	// RVA: 0x1e75af4 VA: 0x759448daf4
	private IList`1 <>xLuaBaseProxy_GetPassiveBuffs() { }
	// RVA: 0x1e75af8 VA: 0x759448daf8
	private IList`1 <>xLuaBaseProxy_GetActiveBuffs() { }
	// RVA: 0x1e75afc VA: 0x759448dafc
	private IList`1 <>xLuaBaseProxy_GetEventActions(Event P0) { }
	// RVA: 0x1e75b00 VA: 0x759448db00
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1e75b04 VA: 0x759448db04
	private IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay() { }
	// RVA: 0x1e75b08 VA: 0x759448db08
	private IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay() { }
	// RVA: 0x1e75b0c VA: 0x759448db0c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e75b30 VA: 0x759448db30
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e75b38 VA: 0x759448db38
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e75b3c VA: 0x759448db3c
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e75b40 VA: 0x759448db40
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1e75b4c VA: 0x759448db4c
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e75b58 VA: 0x759448db58
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
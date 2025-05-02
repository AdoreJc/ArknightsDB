# TraceTargetAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `HeightType _priorTraceHeightType`

- `TileSelector _traceTileSelector`

- `Boolean _useHostTarget`

- `Single _minTargetSeletorRange`

- `Single _minTileSeletorRange`

- `Boolean _traceEnemy`

- `Single m_tileSelectorRange`

- `Single m_targetSelectorRange`


## Methods

- `Void _OnCharacterLocate(Object)`

- `Void _OnCharacterFinish(Object)`

- `Void _OnCharacterChanged(Object)`

- `Boolean CanTargetBeTraced(Entity)`

- `Boolean IsTraceTileReachable()`

- `Boolean UpdateTraceTarget()`

- `Boolean CheckCurrentTraceTarget()`

- `Boolean UpdateTraceTargetRoute(Entity)`

- `Boolean _CanUseAttack(Entity)`

- `Boolean _SelectorVerifyTarget(TargetSelector, Entity)`

- `Boolean TryGetTraceTilesBySelector(Entity, ref)`

- `Boolean RegisterTraceTarget(Entity)`

- `Category <>xLuaBaseProxy_get_category()`

- `FP <>xLuaBaseProxy_get_cooldown()`

- `SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource()`

- `SelectTargetTiming <>xLuaBaseProxy_get_selectTargetTiming()`

- `Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget()`

- `Boolean <>xLuaBaseProxy_get_allowNoTarget()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay()`

- `Boolean <>xLuaBaseProxy_get_enableTraceTarget()`

- `Boolean <>xLuaBaseProxy_get_usingTraceCursor()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Entity <>xLuaBaseProxy_SearchTraceTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class TraceTargetAbility : BaseTraceTargetAbility
{
	private HeightType _priorTraceHeightType; // 0x134
	private TileSelector _traceTileSelector; // 0x138
	private Boolean _useHostTarget; // 0x140
	private Single _minTargetSeletorRange; // 0x144
	private Single _minTileSeletorRange; // 0x148
	private Boolean _traceEnemy; // 0x14c
	private List`1 s_candidateTiles; // 0x150
	private List`1 s_candidateEntities; // 0x158
	private Single m_tileSelectorRange; // 0x160
	private Single m_targetSelectorRange; // 0x164
	private ObjectPtr`1 m_host; // 0x168
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
	private static DelegateBridge __Hotfix0_get_enableTraceTarget; // 0x60
	private static DelegateBridge __Hotfix0_get_host; // 0x68
	private static DelegateBridge __Hotfix0_get_usingTraceCursor; // 0x70
	private static DelegateBridge __Hotfix0_OnAttached; // 0x78
	private static DelegateBridge __Hotfix0_OnDetached; // 0x80
	private static DelegateBridge __Hotfix0_CastDirectly; // 0x88
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x90
	private static DelegateBridge __Hotfix0__OnCharacterLocate; // 0x98
	private static DelegateBridge __Hotfix0__OnCharacterFinish; // 0xa0
	private static DelegateBridge __Hotfix0__OnCharacterChanged; // 0xa8
	private static DelegateBridge __Hotfix0_DoSetData; // 0xb0
	private static DelegateBridge __Hotfix0_Reset; // 0xb8
	private static DelegateBridge __Hotfix0_OnTick; // 0xc0
	private static DelegateBridge __Hotfix0_CanTargetBeTraced; // 0xc8
	private static DelegateBridge __Hotfix0_IsTraceTileReachable; // 0xd0
	private static DelegateBridge __Hotfix0_UpdateTraceTarget; // 0xd8
	private static DelegateBridge __Hotfix0_CheckCurrentTraceTarget; // 0xe0
	private static DelegateBridge __Hotfix0_UpdateTraceTargetRoute; // 0xe8
	private static DelegateBridge __Hotfix0__CanUseAttack; // 0xf0
	private static DelegateBridge __Hotfix0__SelectorVerifyTarget; // 0xf8
	private static DelegateBridge __Hotfix0_TryGetTraceTilesBySelector; // 0x100
	private static DelegateBridge __Hotfix0_SearchTraceTarget; // 0x108
	private static DelegateBridge __Hotfix0_RegisterTraceTarget; // 0x110
	private static DelegateBridge _c__Hotfix0_ctor; // 0x118

	public override Category category { get; }
	public override FP cooldown { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override SelectTargetTiming selectTargetTiming { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public override Boolean allowNoTarget { get; }
	public override Boolean enableTraceTarget { get; }
	private ObjectPtr`1 host { get; }
	public override Boolean usingTraceCursor { get; }

	// RVA: 0x1eb2a64 VA: 0x75944caa64
	public override Category get_category() { }
	// RVA: 0x1eb2acc VA: 0x75944caacc
	public override FP get_cooldown() { }
	// RVA: 0x1eb2b6c VA: 0x75944cab6c
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1eb2bd4 VA: 0x75944cabd4
	public override SelectTargetTiming get_selectTargetTiming() { }
	// RVA: 0x1eb2c38 VA: 0x75944cac38
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1eb2c9c VA: 0x75944cac9c
	public override Boolean get_allowNoTarget() { }
	// RVA: 0x1eb2d00 VA: 0x75944cad00
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1eb2d64 VA: 0x75944cad64
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1eb2dc8 VA: 0x75944cadc8
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1eb2e40 VA: 0x75944cae40
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1eb2ec0 VA: 0x75944caec0
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1eb2f84 VA: 0x75944caf84
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1eb3048 VA: 0x75944cb048
	public override Boolean get_enableTraceTarget() { }
	// RVA: 0x1eb3138 VA: 0x75944cb138
	private ObjectPtr`1 get_host() { }
	// RVA: 0x1eb3254 VA: 0x75944cb254
	public override Boolean get_usingTraceCursor() { }
	// RVA: 0x1eb334c VA: 0x75944cb34c
	protected override Void OnAttached() { }
	// RVA: 0x1eb3548 VA: 0x75944cb548
	protected override Void OnDetached() { }
	// RVA: 0x1eb3744 VA: 0x75944cb744
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1eb3cc8 VA: 0x75944cbcc8
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1eb3f30 VA: 0x75944cbf30
	private Void _OnCharacterLocate(Object arg) { }
	// RVA: 0x1eb4488 VA: 0x75944cc488
	private Void _OnCharacterFinish(Object arg) { }
	// RVA: 0x1eb45d0 VA: 0x75944cc5d0
	private Void _OnCharacterChanged(Object arg) { }
	// RVA: 0x1eb4afc VA: 0x75944ccafc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1eb4e08 VA: 0x75944cce08
	protected override Void Reset() { }
	// RVA: 0x1eb4f68 VA: 0x75944ccf68
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1eb479c VA: 0x75944cc79c
	public Boolean CanTargetBeTraced(Entity entity) { }
	// RVA: 0x1eb5370 VA: 0x75944cd370
	public Boolean IsTraceTileReachable() { }
	// RVA: 0x1eb3b0c VA: 0x75944cbb0c
	public Boolean UpdateTraceTarget() { }
	// RVA: 0x1eb5540 VA: 0x75944cd540
	public Boolean CheckCurrentTraceTarget() { }
	// RVA: 0x1eb4158 VA: 0x75944cc158
	public Boolean UpdateTraceTargetRoute(Entity candidate) { }
	// RVA: 0x1eb5048 VA: 0x75944cd048
	private Boolean _CanUseAttack(Entity entity) { }
	// RVA: 0x1eb521c VA: 0x75944cd21c
	private Boolean _SelectorVerifyTarget(TargetSelector selector, Entity entity) { }
	// RVA: 0x1eb39e8 VA: 0x75944cb9e8
	public Boolean TryGetTraceTilesBySelector(Entity target, ref List`1 tiles) { }
	// RVA: 0x1eb57ac VA: 0x75944cd7ac
	public override Entity SearchTraceTarget() { }
	// RVA: 0x1eb3e10 VA: 0x75944cbe10
	public Boolean RegisterTraceTarget(Entity entity) { }
	// RVA: 0x1eb5d1c VA: 0x75944cdd1c
	public Void .ctor() { }
	// RVA: 0x1eb5e4c VA: 0x75944cde4c
	private Category <>xLuaBaseProxy_get_category() { }
	// RVA: 0x1eb5e54 VA: 0x75944cde54
	private FP <>xLuaBaseProxy_get_cooldown() { }
	// RVA: 0x1eb5e5c VA: 0x75944cde5c
	private SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource() { }
	// RVA: 0x1eb5e64 VA: 0x75944cde64
	private SelectTargetTiming <>xLuaBaseProxy_get_selectTargetTiming() { }
	// RVA: 0x1eb5e6c VA: 0x75944cde6c
	private Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget() { }
	// RVA: 0x1eb5e74 VA: 0x75944cde74
	private Boolean <>xLuaBaseProxy_get_allowNoTarget() { }
	// RVA: 0x1eb5e7c VA: 0x75944cde7c
	private IList`1 <>xLuaBaseProxy_GetPassiveBuffs() { }
	// RVA: 0x1eb5e84 VA: 0x75944cde84
	private IList`1 <>xLuaBaseProxy_GetActiveBuffs() { }
	// RVA: 0x1eb5e8c VA: 0x75944cde8c
	private IList`1 <>xLuaBaseProxy_GetEventActions(Event P0) { }
	// RVA: 0x1eb5e94 VA: 0x75944cde94
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1eb5e9c VA: 0x75944cde9c
	private IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay() { }
	// RVA: 0x1eb5ea4 VA: 0x75944cdea4
	private IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay() { }
	// RVA: 0x1eb5eac VA: 0x75944cdeac
	private Boolean <>xLuaBaseProxy_get_enableTraceTarget() { }
	// RVA: 0x1eb5eb4 VA: 0x75944cdeb4
	private Boolean <>xLuaBaseProxy_get_usingTraceCursor() { }
	// RVA: 0x1eb5ebc VA: 0x75944cdebc
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1eb5ec4 VA: 0x75944cdec4
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1eb5ecc VA: 0x75944cdecc
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1eb5ed8 VA: 0x75944cded8
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1eb5ee4 VA: 0x75944cdee4
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1eb5f0c VA: 0x75944cdf0c
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1eb5f14 VA: 0x75944cdf14
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1eb5f1c VA: 0x75944cdf1c
	private Entity <>xLuaBaseProxy_SearchTraceTarget() { }
}
```
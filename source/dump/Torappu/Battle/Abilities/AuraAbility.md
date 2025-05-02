# AuraAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `SelfOption _selfOption`

- `Boolean _removeBuffWhenTargetLeave`

- `Boolean _removeBuffWhenAbilityDetached`

- `Boolean _onlyAddBuffOnceForEachTarget`

- `TargetValidator _targetValidator`

- `Boolean _ignoreOwnerFakeDeath`

- `Range m_range`

- `Int32 m_layerMask`

- `TargetEnterExitHandler m_eeHandler`

- `Rigidbody2D <rigidbody2D>k__BackingField`


## Properties

- `TargetEnterExitHandler eeHandler`

- `Rigidbody2D rigidbody2D`

- `Single radius`


## Methods

- `TargetEnterExitHandler get_eeHandler()`

- `Rigidbody2D get_rigidbody2D()`

- `Void set_rigidbody2D(Rigidbody2D)`

- `Single get_radius()`

- `Void _ClearEffects()`

- `Boolean _DoTargetCheckAndEnter(Entity)`

- `Void _DoTargetExit(Entity)`

- `Void OnTriggerEnter2D(Collider2D)`

- `Void OnTriggerExit2D(Collider2D)`

- `IDrawableRange <>xLuaBaseProxy_get_rangeToShow()`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_OnAbilityExtendUpdated(FP)`

- `Void <>xLuaBaseProxy_Awake()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AuraAbility : AbilityStandard
{
	private const Int32 TRIGGER_TICK; // 0x0
	protected BuffData[] _buffs; // 0x108
	protected BuffData[] _passiveBuffs; // 0x110
	protected SelfOption _selfOption; // 0x118
	private Boolean _removeBuffWhenTargetLeave; // 0x11c
	private Boolean _removeBuffWhenAbilityDetached; // 0x11d
	private Boolean _onlyAddBuffOnceForEachTarget; // 0x11e
	private String[] _effects; // 0x120
	private TargetValidator _targetValidator; // 0x128
	private Boolean _ignoreOwnerFakeDeath; // 0x130
	private Range m_range; // 0x138
	private Int32 m_layerMask; // 0x140
	protected Dictionary`2 m_targetMap; // 0x148
	private HashSet`1 m_targetHashSet; // 0x150
	protected Collider2D[] m_colliders; // 0x158
	private List`1 m_effects; // 0x160
	private TargetEnterExitHandler m_eeHandler; // 0x168
	private Rigidbody2D <rigidbody2D>k__BackingField; // 0x170
	private static DelegateBridge __Hotfix0_get_eeHandler; // 0x0
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x8
	private static DelegateBridge __Hotfix0_get_category; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x18
	private static DelegateBridge __Hotfix0_get_rangeToShow; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x28
	private static DelegateBridge __Hotfix0_get_rigidbody2D; // 0x30
	private static DelegateBridge __Hotfix0_set_rigidbody2D; // 0x38
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x40
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x48
	private static DelegateBridge __Hotfix0_get_radius; // 0x50
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x58
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x60
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x68
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x70
	private static DelegateBridge __Hotfix0_Reset; // 0x78
	private static DelegateBridge __Hotfix0_DoSetData; // 0x80
	private static DelegateBridge __Hotfix0_DoAttach; // 0x88
	private static DelegateBridge __Hotfix0_DoDetach; // 0x90
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x98
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0xa0
	private static DelegateBridge __Hotfix0_OnAbilityExtendUpdated; // 0xa8
	private static DelegateBridge __Hotfix0_DealTargetTouched; // 0xb0
	private static DelegateBridge __Hotfix0_DealTargetLeft; // 0xb8
	private static DelegateBridge __Hotfix0__ClearEffects; // 0xc0
	private static DelegateBridge __Hotfix0__DoTargetCheckAndEnter; // 0xc8
	private static DelegateBridge __Hotfix0__DoTargetExit; // 0xd0
	private static DelegateBridge __Hotfix0_VerifyTarget; // 0xd8
	private static DelegateBridge __Hotfix0_OnTriggerEnter2D; // 0xe0
	private static DelegateBridge __Hotfix0_OnTriggerExit2D; // 0xe8
	private static DelegateBridge __Hotfix0_Awake; // 0xf0
	private static DelegateBridge __Hotfix0_OnTick; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	protected TargetEnterExitHandler eeHandler { get; }
	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override IDrawableRange rangeToShow { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	protected Rigidbody2D rigidbody2D { get; set; }
	public Single radius { get; }

	// RVA: 0x1e3cd60 VA: 0x7594454d60
	protected TargetEnterExitHandler get_eeHandler() { }
	// RVA: 0x1e3d050 VA: 0x7594455050
	public override FP get_cooldown() { }
	// RVA: 0x1e3d0e0 VA: 0x75944550e0
	public override Category get_category() { }
	// RVA: 0x1e3d148 VA: 0x7594455148
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e3d1ac VA: 0x75944551ac
	public override IDrawableRange get_rangeToShow() { }
	// RVA: 0x1e3d238 VA: 0x7594455238
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e3d29c VA: 0x759445529c
	protected Rigidbody2D get_rigidbody2D() { }
	// RVA: 0x1e3d304 VA: 0x7594455304
	private Void set_rigidbody2D(Rigidbody2D value) { }
	// RVA: 0x1e3d388 VA: 0x7594455388
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e3d400 VA: 0x7594455400
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e3d480 VA: 0x7594455480
	public Single get_radius() { }
	// RVA: 0x1e3d58c VA: 0x759445558c
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e3d5f4 VA: 0x75944555f4
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e3d658 VA: 0x7594455658
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e3d71c VA: 0x759445571c
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e3d7e0 VA: 0x75944557e0
	protected override Void Reset() { }
	// RVA: 0x1e3d8dc VA: 0x75944558dc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e3db20 VA: 0x7594455b20
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e3e1b8 VA: 0x75944561b8
	protected override Void DoDetach() { }
	// RVA: 0x1e3e514 VA: 0x7594456514
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e3e5c4 VA: 0x75944565c4
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e3e674 VA: 0x7594456674
	public override Void OnAbilityExtendUpdated(FP extend) { }
	// RVA: 0x1e3e75c VA: 0x759445675c
	protected virtual Boolean DealTargetTouched(Entity target, TargetMeta meta) { }
	// RVA: 0x1e3e8a4 VA: 0x75944568a4
	protected virtual Void DealTargetLeft(Entity target, TargetMeta meta) { }
	// RVA: 0x1e3e048 VA: 0x7594456048
	private Void _ClearEffects() { }
	// RVA: 0x1e3e968 VA: 0x7594456968
	private Boolean _DoTargetCheckAndEnter(Entity target) { }
	// RVA: 0x1e3eb90 VA: 0x7594456b90
	private Void _DoTargetExit(Entity target) { }
	// RVA: 0x1e3ed1c VA: 0x7594456d1c
	protected virtual Boolean VerifyTarget(Entity target) { }
	// RVA: 0x1e3ee68 VA: 0x7594456e68
	private Void OnTriggerEnter2D(Collider2D collision) { }
	// RVA: 0x1e3f120 VA: 0x7594457120
	private Void OnTriggerExit2D(Collider2D collision) { }
	// RVA: 0x1e3f3d8 VA: 0x75944573d8
	protected override Void Awake() { }
	// RVA: 0x1e3f558 VA: 0x7594457558
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e3f6a8 VA: 0x75944576a8
	public Void .ctor() { }
	// RVA: 0x1e3f84c VA: 0x759445784c
	private IDrawableRange <>xLuaBaseProxy_get_rangeToShow() { }
	// RVA: 0x1e3f854 VA: 0x7594457854
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e3f85c VA: 0x759445785c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e3f884 VA: 0x7594457884
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e3f88c VA: 0x759445788c
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e3f894 VA: 0x7594457894
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1e3f89c VA: 0x759445789c
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e3f8a4 VA: 0x75944578a4
	private Void <>xLuaBaseProxy_OnAbilityExtendUpdated(FP P0) { }
	// RVA: 0x1e3f8ac VA: 0x75944578ac
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x1e3f8b4 VA: 0x75944578b4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
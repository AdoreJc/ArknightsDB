# ActiveAbilityWrapper

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _isInfinity`

- `String _durationKey`

- `Single _preDelay`

- `FP m_lifeTime`


## Methods

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `IDrawableRange <>xLuaBaseProxy_get_rangeToShow()`

- `Boolean <>xLuaBaseProxy_get_allowNoTarget()`

- `Void <>xLuaBaseProxy_StopAffect()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_OnSpellStart()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ActiveAbilityWrapper : EasyToStartAbility
{
	private Ability[] _wrappedAbilities; // 0x128
	private Boolean _isInfinity; // 0x130
	private String _durationKey; // 0x138
	private Single _preDelay; // 0x140
	private FP m_lifeTime; // 0x148
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x18
	private static DelegateBridge __Hotfix0_get_rangeToShow; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x28
	private static DelegateBridge __Hotfix0_get_allowNoTarget; // 0x30
	private static DelegateBridge __Hotfix0_get_preDelay; // 0x38
	private static DelegateBridge __Hotfix0_StopAffect; // 0x40
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x48
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x50
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x58
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x60
	private static DelegateBridge __Hotfix0_DoSetData; // 0x68
	private static DelegateBridge __Hotfix0_GetDuration; // 0x70
	private static DelegateBridge __Hotfix0_OnSpellStart; // 0x78
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override Boolean isAffecting { get; }
	public override IDrawableRange rangeToShow { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public override Boolean allowNoTarget { get; }
	public override FP preDelay { get; }

	// RVA: 0x1e3b2ac VA: 0x75944532ac
	public override FP get_cooldown() { }
	// RVA: 0x1e3b314 VA: 0x7594453314
	public override Category get_category() { }
	// RVA: 0x1e3b37c VA: 0x759445337c
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e3b3e4 VA: 0x75944533e4
	public override Boolean get_isAffecting() { }
	// RVA: 0x1e3b480 VA: 0x7594453480
	public override IDrawableRange get_rangeToShow() { }
	// RVA: 0x1e3b54c VA: 0x759445354c
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e3b5b0 VA: 0x75944535b0
	public override Boolean get_allowNoTarget() { }
	// RVA: 0x1e3b618 VA: 0x7594453618
	public override FP get_preDelay() { }
	// RVA: 0x1e3b6b8 VA: 0x75944536b8
	public override Void StopAffect() { }
	// RVA: 0x1e3b810 VA: 0x7594453810
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e3b888 VA: 0x7594453888
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e3b908 VA: 0x7594453908
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e3b96c VA: 0x759445396c
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e3b9d0 VA: 0x75944539d0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e3bbdc VA: 0x7594453bdc
	protected override FP GetDuration() { }
	// RVA: 0x1e3bc50 VA: 0x7594453c50
	protected override Boolean OnSpellStart() { }
	// RVA: 0x1e3bdd4 VA: 0x7594453dd4
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e3bec4 VA: 0x7594453ec4
	public Void .ctor() { }
	// RVA: 0x1e3bf64 VA: 0x7594453f64
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x1e3bf6c VA: 0x7594453f6c
	private IDrawableRange <>xLuaBaseProxy_get_rangeToShow() { }
	// RVA: 0x1e3bf74 VA: 0x7594453f74
	private Boolean <>xLuaBaseProxy_get_allowNoTarget() { }
	// RVA: 0x1e3bf7c VA: 0x7594453f7c
	private Void <>xLuaBaseProxy_StopAffect() { }
	// RVA: 0x1e3bf84 VA: 0x7594453f84
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e3bfac VA: 0x7594453fac
	private Boolean <>xLuaBaseProxy_OnSpellStart() { }
	// RVA: 0x1e3bfb4 VA: 0x7594453fb4
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
}
```
# ReloadAnimatedAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Ability m_traitAbility`

- `FP m_reloadCooldown`

- `FP m_defaultBaseAttackTime`


## Properties

- `Ability traitAbiliy`


## Methods

- `Ability get_traitAbiliy()`

- `FP _CalculateCooldown()`

- `FP <>xLuaBaseProxy_get_cooldown()`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ReloadAnimatedAbility : AbstractAnimatedAbility
{
	private Ability m_traitAbility; // 0x1c0
	private FP m_reloadCooldown; // 0x1c8
	private FP m_defaultBaseAttackTime; // 0x1d0
	private static DelegateBridge __Hotfix0_get_traitAbiliy; // 0x0
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_DoSetData; // 0x18
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x20
	private static DelegateBridge __Hotfix0_UpdatePlaybackSpeed; // 0x28
	private static DelegateBridge __Hotfix0__CalculateCooldown; // 0x30
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x38
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Ability traitAbiliy { get; }
	public override FP cooldown { get; }

	// RVA: 0x1eafb24 VA: 0x75944c7b24
	private Ability get_traitAbiliy() { }
	// RVA: 0x1eafc88 VA: 0x75944c7c88
	public override FP get_cooldown() { }
	// RVA: 0x1eafcf0 VA: 0x75944c7cf0
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1eaff3c VA: 0x75944c7f3c
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1eb00dc VA: 0x75944c80dc
	protected override Void OnCastStart() { }
	// RVA: 0x1eb0154 VA: 0x75944c8154
	protected override Boolean UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming timing, out Single animSpeed) { }
	// RVA: 0x1eafd80 VA: 0x75944c7d80
	private FP _CalculateCooldown() { }
	// RVA: 0x1eb0254 VA: 0x75944c8254
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1eb02d4 VA: 0x75944c82d4
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1eb034c VA: 0x75944c834c
	public Void .ctor() { }
	// RVA: 0x1eb03bc VA: 0x75944c83bc
	private FP <>xLuaBaseProxy_get_cooldown() { }
	// RVA: 0x1eb03c4 VA: 0x75944c83c4
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1eb03cc VA: 0x75944c83cc
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1eb03f4 VA: 0x75944c83f4
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1eb03fc VA: 0x75944c83fc
	private Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming P0, out Single P1) { }
}
```
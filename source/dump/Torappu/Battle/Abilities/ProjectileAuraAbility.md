# ProjectileAuraAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ProjectileValidator _projectileValidator`

- `Range m_range`


## Methods

- `Void _ClearEffects()`

- `Void _CheckProjectilesInAura()`

- `Void _CheckProjectileValid()`

- `Void _DoProjectileEnter(Projectile)`

- `Void _DoProjectileExit(Projectile)`

- `IDrawableRange <>xLuaBaseProxy_get_rangeToShow()`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_Awake()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ProjectileAuraAbility : AbilityStandard
{
	private String[] _effects; // 0x108
	private ProjectileValidator _projectileValidator; // 0x110
	private HashSet`1 m_projectiles; // 0x118
	private List`1 m_effects; // 0x120
	private List`1 m_invalidProjectiles; // 0x128
	private Range m_range; // 0x130
	private static DelegateBridge __Hotfix0_get_projectiles; // 0x0
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x8
	private static DelegateBridge __Hotfix0_get_category; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x18
	private static DelegateBridge __Hotfix0_get_rangeToShow; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x28
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x30
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x38
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x40
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x48
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x50
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x58
	private static DelegateBridge __Hotfix0_Reset; // 0x60
	private static DelegateBridge __Hotfix0_DoSetData; // 0x68
	private static DelegateBridge __Hotfix0_DoAttach; // 0x70
	private static DelegateBridge __Hotfix0_DoDetach; // 0x78
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x80
	private static DelegateBridge __Hotfix0_Awake; // 0x88
	private static DelegateBridge __Hotfix0_OnTick; // 0x90
	private static DelegateBridge __Hotfix0__ClearEffects; // 0x98
	private static DelegateBridge __Hotfix0__CheckProjectilesInAura; // 0xa0
	private static DelegateBridge __Hotfix0__CheckProjectileValid; // 0xa8
	private static DelegateBridge __Hotfix0__DoProjectileEnter; // 0xb0
	private static DelegateBridge __Hotfix0__DoProjectileExit; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public HashSet`1 projectiles { get; }
	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override IDrawableRange rangeToShow { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e4b788 VA: 0x7594463788
	public HashSet`1 get_projectiles() { }
	// RVA: 0x1e4b7f0 VA: 0x75944637f0
	public override FP get_cooldown() { }
	// RVA: 0x1e4b880 VA: 0x7594463880
	public override Category get_category() { }
	// RVA: 0x1e4b8e8 VA: 0x75944638e8
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e4b94c VA: 0x759446394c
	public override IDrawableRange get_rangeToShow() { }
	// RVA: 0x1e4b9d8 VA: 0x75944639d8
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e4ba3c VA: 0x7594463a3c
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e4bab4 VA: 0x7594463ab4
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e4bb34 VA: 0x7594463b34
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e4bb98 VA: 0x7594463b98
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e4bbfc VA: 0x7594463bfc
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e4bc98 VA: 0x7594463c98
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e4bd34 VA: 0x7594463d34
	protected override Void Reset() { }
	// RVA: 0x1e4bdc8 VA: 0x7594463dc8
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e4bfd0 VA: 0x7594463fd0
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e4c378 VA: 0x7594464378
	protected override Void DoDetach() { }
	// RVA: 0x1e4c728 VA: 0x7594464728
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e4c7d8 VA: 0x75944647d8
	protected override Void Awake() { }
	// RVA: 0x1e4c874 VA: 0x7594464874
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e4c208 VA: 0x7594464208
	private Void _ClearEffects() { }
	// RVA: 0x1e4c908 VA: 0x7594464908
	private Void _CheckProjectilesInAura() { }
	// RVA: 0x1e4cda0 VA: 0x7594464da0
	private Void _CheckProjectileValid() { }
	// RVA: 0x1e4d15c VA: 0x759446515c
	private Void _DoProjectileEnter(Projectile projectile) { }
	// RVA: 0x1e4c578 VA: 0x7594464578
	private Void _DoProjectileExit(Projectile projectile) { }
	// RVA: 0x1e4d30c VA: 0x759446530c
	public Void .ctor() { }
	// RVA: 0x1e4d420 VA: 0x7594465420
	private IDrawableRange <>xLuaBaseProxy_get_rangeToShow() { }
	// RVA: 0x1e4d428 VA: 0x7594465428
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e4d430 VA: 0x7594465430
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e4d458 VA: 0x7594465458
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e4d460 VA: 0x7594465460
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e4d468 VA: 0x7594465468
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1e4d470 VA: 0x7594465470
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x1e4d478 VA: 0x7594465478
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
# MeleeAttackWithSplashDmg

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _splashAtkScale`

- `String _splashAtkScaleKey`

- `Boolean _interruptSpellIfInputTargetDead`

- `FP m_atkScaleSplash`


## Properties

- `TargetSelector splashSelector`


## Methods

- `TargetSelector get_splashSelector()`

- `Boolean <>xLuaBaseProxy_get_useDynamicAttackType()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MeleeAttackWithSplashDmg : MeleeAttack
{
	private Single _splashAtkScale; // 0x20c
	private String _splashAtkScaleKey; // 0x210
	private Boolean _interruptSpellIfInputTargetDead; // 0x218
	private BuffData[] _activeBuffsToMainTarget; // 0x220
	private BuffData[] _activeBuffsToSplashTarget; // 0x228
	protected FP m_atkScaleSplash; // 0x230
	protected List`1 m_actionsToSplashTargets; // 0x238
	private static DelegateBridge __Hotfix0_get_splashSelector; // 0x0
	private static DelegateBridge __Hotfix0_get_useDynamicAttackType; // 0x8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x10
	private static DelegateBridge __Hotfix0_GetActiveBuffsToMainTarget; // 0x18
	private static DelegateBridge __Hotfix0_GetActiveBuffsToSplashTarget; // 0x20
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x28
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x30
	private static DelegateBridge __Hotfix0_GetActionsToSplashTarget; // 0x38
	private static DelegateBridge __Hotfix0_IsMainTarget; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected TargetSelector splashSelector { get; }
	protected override Boolean useDynamicAttackType { get; }

	// RVA: 0x1e056dc VA: 0x759441d6dc
	protected TargetSelector get_splashSelector() { }
	// RVA: 0x1e05750 VA: 0x759441d750
	protected override Boolean get_useDynamicAttackType() { }
	// RVA: 0x1e057b8 VA: 0x759441d7b8
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e05ccc VA: 0x759441dccc
	protected virtual IList`1 GetActiveBuffsToMainTarget() { }
	// RVA: 0x1e05d34 VA: 0x759441dd34
	protected virtual IList`1 GetActiveBuffsToSplashTarget() { }
	// RVA: 0x1e05d9c VA: 0x759441dd9c
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e05e94 VA: 0x759441de94
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e05fb0 VA: 0x759441dfb0
	protected IList`1 GetActionsToSplashTarget(Event ev) { }
	// RVA: 0x1e0603c VA: 0x759441e03c
	protected virtual Boolean IsMainTarget(Entity target) { }
	// RVA: 0x1e0612c VA: 0x759441e12c
	public Void .ctor() { }
	// RVA: 0x1e06278 VA: 0x759441e278
	private Boolean <>xLuaBaseProxy_get_useDynamicAttackType() { }
	// RVA: 0x1e0627c VA: 0x759441e27c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e062a0 VA: 0x759441e2a0
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e062a8 VA: 0x759441e2a8
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
}
```
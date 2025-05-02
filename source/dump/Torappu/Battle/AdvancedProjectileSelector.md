# AdvancedProjectileSelector

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _targetSide`

- `SideType m_sideTypeMask`


## Methods

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedProjectileSelector : RangeSelector
{
	private SideType _targetSide; // 0xa0
	private SideType m_sideTypeMask; // 0xa4
	private List`1 m_projectileCache; // 0xa8
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x0
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x8
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x10
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x28
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x30
	private static DelegateBridge __Hotfix0_FindProjectiles_CLEAR; // 0x38
	private static DelegateBridge __Hotfix0__ValidateProjectile; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1bb6020 VA: 0x75941ce020
	public override SideType get_targetSide() { }
	// RVA: 0x1bb6088 VA: 0x75941ce088
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1bb60ec VA: 0x75941ce0ec
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bb6150 VA: 0x75941ce150
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bb61b4 VA: 0x75941ce1b4
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bb62c4 VA: 0x75941ce2c4
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb633c VA: 0x75941ce33c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb63b4 VA: 0x75941ce3b4
	public override List`1 FindProjectiles_CLEAR(Vector2 pos) { }
	// RVA: 0x1bb67e8 VA: 0x75941ce7e8
	protected virtual Boolean _ValidateProjectile(Projectile projectile) { }
	// RVA: 0x1bb68b8 VA: 0x75941ce8b8
	public Void .ctor() { }
	// RVA: 0x1bb6984 VA: 0x75941ce984
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bb698c VA: 0x75941ce98c
	private List`1 <>xLuaBaseProxy_FindProjectiles_CLEAR(Vector2 P0) { }
}
```
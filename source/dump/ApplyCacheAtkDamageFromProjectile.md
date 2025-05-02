# ApplyCacheAtkDamageFromProjectile

**Namespace:** ` `


## Fields

- `Boolean _transferSource`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Modifier <>xLuaBaseProxy_CreateDamageModifier(Entity, Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyCacheAtkDamageFromProjectile : ApplyDamage
{
	protected Boolean _transferSource; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_CreateDamageModifier; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f3a9a0 VA: 0x75945529a0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3aa08 VA: 0x7594552a08
	public Void .ctor(DamageType damageType, SourceApplyWay applyWay, FP atkScale, SourceAttackType attackType, Boolean useDynamicAttackType, Boolean transferSource) { }
	// RVA: 0x1f3aae4 VA: 0x7594552ae4
	public override Modifier CreateDamageModifier(Entity source, Entity target) { }
	// RVA: 0x1f3abd0 VA: 0x7594552bd0
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f3abd4 VA: 0x7594552bd4
	private Modifier <>xLuaBaseProxy_CreateDamageModifier(Entity P0, Entity P1) { }
}
```
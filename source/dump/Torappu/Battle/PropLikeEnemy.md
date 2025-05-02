# PropLikeEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _acceptSpecificDamageType`

- `DamageType _acceptDamageType`

- `Boolean _onlyAffectSpecificModeIndex`

- `Int32 _specificModeIndex`


## Properties

- `Boolean acceptSpecificDamageType`

- `Boolean onlyAffectSpecificModeIndex`


## Methods

- `Boolean get_acceptSpecificDamageType()`

- `Boolean get_onlyAffectSpecificModeIndex()`

- `Boolean CheckIsInPropLikeState()`

- `Boolean <>xLuaBaseProxy_DoApplyModifier(ref, Boolean)`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class PropLikeEnemy : Enemy
{
	private Boolean _acceptSpecificDamageType; // 0x4b8
	private DamageType _acceptDamageType; // 0x4bc
	private List`1 _basicEffects; // 0x4c0
	private Boolean _onlyAffectSpecificModeIndex; // 0x4c8
	private Int32 _specificModeIndex; // 0x4cc
	private static DelegateBridge __Hotfix0_get_acceptSpecificDamageType; // 0x0
	private static DelegateBridge __Hotfix0_get_onlyAffectSpecificModeIndex; // 0x8
	private static DelegateBridge __Hotfix0_DoApplyModifier; // 0x10
	private static DelegateBridge __Hotfix0_OnBorn; // 0x18
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x20
	private static DelegateBridge __Hotfix0_CheckIsInPropLikeState; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Boolean acceptSpecificDamageType { get; }
	private Boolean onlyAffectSpecificModeIndex { get; }

	// RVA: 0x1c24470 VA: 0x759423c470
	private Boolean get_acceptSpecificDamageType() { }
	// RVA: 0x1c244d8 VA: 0x759423c4d8
	private Boolean get_onlyAffectSpecificModeIndex() { }
	// RVA: 0x1c24540 VA: 0x759423c540
	protected override Boolean DoApplyModifier(ref Modifier modifier, Boolean force) { }
	// RVA: 0x1c247e0 VA: 0x759423c7e0
	protected override Void OnBorn() { }
	// RVA: 0x1c24884 VA: 0x759423c884
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1c24aa8 VA: 0x759423caa8
	public Boolean CheckIsInPropLikeState() { }
	// RVA: 0x1c24b3c VA: 0x759423cb3c
	public Void .ctor() { }
	// RVA: 0x1c24bd0 VA: 0x759423cbd0
	private Boolean <>xLuaBaseProxy_DoApplyModifier(ref Modifier P0, Boolean P1) { }
	// RVA: 0x1c24bdc VA: 0x759423cbdc
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x1c24be4 VA: 0x759423cbe4
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```
# BrownbTalent_1

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `BuffData _stackBuff`

- `FamilyGroupMask _targetFamilyMask`

- `Boolean _onlyApplyOnFirstSpell`

- `Boolean _ignoreOwnerAsTarget`

- `String m_overrideKey`

- `Int32 m_additionalStackCnt`

- `OverrideGroup m_lastOverrideGroup`


## Methods

- `Void Apply(Entity, Entity, Ability, Blackboard)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BrownbTalent_1 : PassiveBuffAbility, IAbilityAttachment
{
	protected BuffData _stackBuff; // 0x110
	private FamilyGroupMask _targetFamilyMask; // 0x118
	private Boolean _onlyApplyOnFirstSpell; // 0x11c
	private Boolean _ignoreOwnerAsTarget; // 0x11d
	private String m_overrideKey; // 0x120
	private Int32 m_additionalStackCnt; // 0x128
	private ObjectPtr`1 m_lastTarget; // 0x130
	private OverrideGroup m_lastOverrideGroup; // 0x140
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_Apply; // 0x18
	private static DelegateBridge __Hotfix0_OnAttached; // 0x20
	private static DelegateBridge __Hotfix0_OnDetached; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1e6b910 VA: 0x7594483910
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e6b974 VA: 0x7594483974
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e6ba40 VA: 0x7594483a40
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e6bbf4 VA: 0x7594483bf4
	public Void Apply(Entity target, Entity owner, Ability ability, Blackboard externalBlackboard) { }
	// RVA: 0x1e6be8c VA: 0x7594483e8c
	protected override Void OnAttached() { }
	// RVA: 0x1e6bf1c VA: 0x7594483f1c
	protected override Void OnDetached() { }
	// RVA: 0x1e6bfa8 VA: 0x7594483fa8
	public Void .ctor() { }
	// RVA: 0x1e6c060 VA: 0x7594484060
	private IList`1 <>xLuaBaseProxy_GetPassiveBuffs() { }
	// RVA: 0x1e6c068 VA: 0x7594484068
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e6c090 VA: 0x7594484090
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e6c098 VA: 0x7594484098
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e6c0a0 VA: 0x75944840a0
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```
# StealAttributeAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `AttributeType _attributeType`

- `FormulaItemType _formulaType`

- `String _stealOnceBBKey`

- `String _stealMaxBBKey`

- `Boolean _finishTargetBuffWhenInvalid`

- `Boolean _finishOwnerBuffWhenTargetInvalid`

- `Single m_stealOnceValue`

- `Single m_stealMaxValue`

- `Single m_stealedTotalValue`

- `String m_stealTargetBuffKey`

- `String m_stealSelfBuffKey`

- `String m_stealTargetBBKey`


## Properties

- `Buff ownerStealBuff`


## Methods

- `Buff get_ownerStealBuff()`

- `Void _ResetParamKeys()`

- `String _SetStealTargetBuffStr(String, AttrTargetType)`

- `Void TriggerByTarget(Entity, Buff)`

- `Void _VerifyCachedStatus()`

- `Void _RefreshOwnerStatus()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class StealAttributeAbility : EmptyAbility
{
	private AttributeType _attributeType; // 0x108
	private FormulaItemType _formulaType; // 0x10c
	private String _stealOnceBBKey; // 0x110
	private String _stealMaxBBKey; // 0x118
	private Boolean _finishTargetBuffWhenInvalid; // 0x120
	private Boolean _finishOwnerBuffWhenTargetInvalid; // 0x121
	protected BuffData[] _passiveBuffs; // 0x128
	private Single m_stealOnceValue; // 0x130
	private Single m_stealMaxValue; // 0x134
	private Single m_stealedTotalValue; // 0x138
	private String m_stealTargetBuffKey; // 0x140
	private String m_stealSelfBuffKey; // 0x148
	private String m_stealTargetBBKey; // 0x150
	private const String STEAL_ONCE_BB_KEY; // 0x0
	private const String STEAL_MAX_BB_KEY; // 0x0
	private const String STEAL_ATTR_TARGET; // 0x0
	private const String STEAL_ATTR_SELF; // 0x0
	private Dictionary`2 m_stealStatus; // 0x158
	private List`1 m_stealCacheStatus; // 0x160
	private ObjectPtr`1 m_ownerStealBuff; // 0x168
	private static DelegateBridge __Hotfix0_get_ownerStealBuff; // 0x0
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0__ResetParamKeys; // 0x20
	private static DelegateBridge __Hotfix0__SetStealTargetBuffStr; // 0x28
	private static DelegateBridge __Hotfix0_OnAttached; // 0x30
	private static DelegateBridge __Hotfix0_OnDetached; // 0x38
	private static DelegateBridge __Hotfix0_TriggerByTarget; // 0x40
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x48
	private static DelegateBridge __Hotfix0_CastDirectly; // 0x50
	private static DelegateBridge __Hotfix0_OnTick; // 0x58
	private static DelegateBridge __Hotfix0__VerifyCachedStatus; // 0x60
	private static DelegateBridge __Hotfix0__RefreshOwnerStatus; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	private Buff ownerStealBuff { get; }

	// RVA: 0x1eb11e4 VA: 0x75944c91e4
	private Buff get_ownerStealBuff() { }
	// RVA: 0x1eb1308 VA: 0x75944c9308
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1eb1370 VA: 0x75944c9370
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1eb17b4 VA: 0x75944c97b4
	protected override Void Reset() { }
	// RVA: 0x1eb1590 VA: 0x75944c9590
	private Void _ResetParamKeys() { }
	// RVA: 0x1eb184c VA: 0x75944c984c
	private String _SetStealTargetBuffStr(String attr, AttrTargetType type) { }
	// RVA: 0x1eb19f8 VA: 0x75944c99f8
	protected override Void OnAttached() { }
	// RVA: 0x1eb1ae4 VA: 0x75944c9ae4
	protected override Void OnDetached() { }
	// RVA: 0x1eb1c28 VA: 0x75944c9c28
	public Void TriggerByTarget(Entity target, Buff targetBuff) { }
	// RVA: 0x1eb1f10 VA: 0x75944c9f10
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1eb240c VA: 0x75944ca40c
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1eb2500 VA: 0x75944ca500
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1eb258c VA: 0x75944ca58c
	private Void _VerifyCachedStatus() { }
	// RVA: 0x1eb1e10 VA: 0x75944c9e10
	private Void _RefreshOwnerStatus() { }
	// RVA: 0x1eb2814 VA: 0x75944ca814
	public Void .ctor() { }
	// RVA: 0x1eb29fc VA: 0x75944ca9fc
	private IList`1 <>xLuaBaseProxy_GetPassiveBuffs() { }
	// RVA: 0x1eb2a04 VA: 0x75944caa04
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1eb2a2c VA: 0x75944caa2c
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1eb2a34 VA: 0x75944caa34
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1eb2a3c VA: 0x75944caa3c
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1eb2a44 VA: 0x75944caa44
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1eb2a50 VA: 0x75944caa50
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1eb2a5c VA: 0x75944caa5c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
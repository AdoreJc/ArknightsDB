# EnemySkill

**Namespace:** `Torappu.Battle`


## Fields

- `FamilyGroupMask _familyMask`

- `TargetTrigger _trigger`

- `Boolean _checkParentActive`

- `Int32 _maxTriggerTime`

- `Boolean _resetMainAbilityCdWhenCastEnd`

- `Int32 _overwriteInitCooldown`

- `Boolean _ignoreSilence`

- `Boolean _immuneStunWhenAffecting`

- `Boolean _addEnemyIdToSignalId`

- `Int32 m_spCost`

- `Int32 m_triggerCnt`

- `PeriodicTimer m_cooldownTimer`

- `FinishCallbackDelegate m_finishCb`

- `Ability m_mainAbility`

- `Boolean m_registeredAsModifier`

- `Ability <ability>k__BackingField`

- `UnitMode <parentMode>k__BackingField`

- `ESkillData <data>k__BackingField`

- `Enemy <owner>k__BackingField`


## Properties

- `Boolean isEnabled`

- `Int32 priority`

- `Ability ability`

- `TargetTrigger trigger`

- `PeriodicTimer cooldownTimer`

- `Boolean isUsedUp`

- `Boolean resetMainAbilityCdWhenCastEnd`

- `UnitMode parentMode`

- `Boolean isRoot`

- `ESkillData data`

- `Enemy owner`

- `Boolean ownerSkillActivatable`

- `Boolean registeredAsModifier`

- `Boolean isSpCostSkill`

- `Int64 attributeMask`

- `Int64 abnormalFlagMask`

- `Int64 abnormalImmuneMask`

- `Int64 abnormalAntiMask`

- `Int64 abnormalComboMask`

- `Int64 abnormalComboImmuneMask`


## Methods

- `Boolean get_isEnabled()`

- `Void set_isEnabled(Boolean)`

- `Int32 get_priority()`

- `Ability get_ability()`

- `Void set_ability(Ability)`

- `TargetTrigger get_trigger()`

- `PeriodicTimer get_cooldownTimer()`

- `Boolean get_isUsedUp()`

- `Boolean get_resetMainAbilityCdWhenCastEnd()`

- `UnitMode get_parentMode()`

- `Void set_parentMode(UnitMode)`

- `Boolean get_isRoot()`

- `ESkillData get_data()`

- `Void set_data(ESkillData)`

- `Enemy get_owner()`

- `Void set_owner(Enemy)`

- `Boolean get_ownerSkillActivatable()`

- `Boolean get_registeredAsModifier()`

- `Void set_registeredAsModifier(Boolean)`

- `Boolean get_isSpCostSkill()`

- `Int64 get_attributeMask()`

- `Int64 get_abnormalFlagMask()`

- `Int64 get_abnormalImmuneMask()`

- `Int64 get_abnormalAntiMask()`

- `Int64 get_abnormalComboMask()`

- `Int64 get_abnormalComboImmuneMask()`

- `Boolean GetValue(AttributeType, out, out, out, out)`

- `Void Init()`

- `Void Attach()`

- `Void Detach()`

- `Boolean CastToTarget(Entity, Ability, FinishCallbackDelegate, Boolean)`

- `Boolean CheckFamilyMask(FamilyGroup)`

- `Void SetParentMode(UnitMode)`

- `Void GatherEffects(List`1)`

- `Void Tick(FP)`

- `Void OnCastSucceed()`

- `Boolean SetEnabledInternal(Boolean, Boolean)`

- `Boolean TryReduceSp(Int32)`

- `Void _OnCastStart()`

- `Void _OnCastFinish(Ability, FinishReason, Boolean)`

- `Void _UpdateRegisterAsModifier(Boolean, Boolean)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnemySkill : MonoBehaviour, IAttributesModifier, IEffectSource, IHotfixable
{
	private FamilyGroupMask _familyMask; // 0x18
	private TargetTrigger _trigger; // 0x20
	private Boolean _checkParentActive; // 0x28
	private Int32 _maxTriggerTime; // 0x2c
	private Boolean _resetMainAbilityCdWhenCastEnd; // 0x30
	private Int32 _overwriteInitCooldown; // 0x34
	private Boolean _ignoreSilence; // 0x38
	private Boolean _immuneStunWhenAffecting; // 0x39
	private Boolean _addEnemyIdToSignalId; // 0x3a
	private Int32 m_spCost; // 0x3c
	private Int32 m_triggerCnt; // 0x40
	protected PeriodicTimer m_cooldownTimer; // 0x48
	private FinishCallbackDelegate m_finishCb; // 0x50
	private Ability m_mainAbility; // 0x58
	private Boolean m_registeredAsModifier; // 0x60
	protected Behaviour[] m_behaviours; // 0x68
	private Ability <ability>k__BackingField; // 0x70
	private UnitMode <parentMode>k__BackingField; // 0x78
	private ESkillData <data>k__BackingField; // 0x80
	private Enemy <owner>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_isEnabled; // 0x0
	private static DelegateBridge __Hotfix0_set_isEnabled; // 0x8
	private static DelegateBridge __Hotfix0_get_skillKey; // 0x10
	private static DelegateBridge __Hotfix0_get_priority; // 0x18
	private static DelegateBridge __Hotfix0_get_ability; // 0x20
	private static DelegateBridge __Hotfix0_set_ability; // 0x28
	private static DelegateBridge __Hotfix0_get_trigger; // 0x30
	private static DelegateBridge __Hotfix0_get_cooldownTimer; // 0x38
	private static DelegateBridge __Hotfix0_get_isUsedUp; // 0x40
	private static DelegateBridge __Hotfix0_get_resetMainAbilityCdWhenCastEnd; // 0x48
	private static DelegateBridge __Hotfix0_get_parentMode; // 0x50
	private static DelegateBridge __Hotfix0_set_parentMode; // 0x58
	private static DelegateBridge __Hotfix0_get_isRoot; // 0x60
	private static DelegateBridge __Hotfix0_get_data; // 0x68
	private static DelegateBridge __Hotfix0_set_data; // 0x70
	private static DelegateBridge __Hotfix0_get_owner; // 0x78
	private static DelegateBridge __Hotfix0_set_owner; // 0x80
	private static DelegateBridge __Hotfix0_get_recoverSpWhenAffecting; // 0x88
	private static DelegateBridge __Hotfix0_get_immuneStunWhenAffecting; // 0x90
	private static DelegateBridge __Hotfix0_get_ownerSkillActivatable; // 0x98
	private static DelegateBridge __Hotfix0_get_registeredAsModifier; // 0xa0
	private static DelegateBridge __Hotfix0_set_registeredAsModifier; // 0xa8
	private static DelegateBridge __Hotfix0_get_isSpCostSkill; // 0xb0
	private static DelegateBridge __Hotfix0_get_attributeMask; // 0xb8
	private static DelegateBridge __Hotfix0_get_abnormalFlagMask; // 0xc0
	private static DelegateBridge __Hotfix0_get_abnormalImmuneMask; // 0xc8
	private static DelegateBridge __Hotfix0_get_abnormalAntiMask; // 0xd0
	private static DelegateBridge __Hotfix0_get_abnormalComboMask; // 0xd8
	private static DelegateBridge __Hotfix0_get_abnormalComboImmuneMask; // 0xe0
	private static DelegateBridge __Hotfix0_GetValue; // 0xe8
	private static DelegateBridge __Hotfix0_AssignData; // 0xf0
	private static DelegateBridge __Hotfix0_Init; // 0xf8
	private static DelegateBridge __Hotfix0_Attach; // 0x100
	private static DelegateBridge __Hotfix0_Detach; // 0x108
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x110
	private static DelegateBridge __Hotfix0_ResetSkillCooldownIfNeeded; // 0x118
	private static DelegateBridge __Hotfix0_CheckFamilyMask; // 0x120
	private static DelegateBridge __Hotfix0_SetParentMode; // 0x128
	private static DelegateBridge __Hotfix0_CheckTrigger; // 0x130
	private static DelegateBridge __Hotfix0_CheckAvailable; // 0x138
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x140
	private static DelegateBridge __Hotfix0_Tick; // 0x148
	private static DelegateBridge __Hotfix0_OnTick; // 0x150
	private static DelegateBridge __Hotfix0_OnCastSucceed; // 0x158
	private static DelegateBridge __Hotfix0_SetEnabledInternal; // 0x160
	private static DelegateBridge __Hotfix0_TryReduceSp; // 0x168
	private static DelegateBridge __Hotfix0__GetRangeRadius; // 0x170
	private static DelegateBridge __Hotfix0__OnCastStart; // 0x178
	private static DelegateBridge __Hotfix0__OnCastFinish; // 0x180
	private static DelegateBridge __Hotfix0__UpdateRegisterAsModifier; // 0x188
	private static DelegateBridge __Hotfix0_Awake; // 0x190
	private static DelegateBridge _c__Hotfix0_ctor; // 0x198

	public Boolean isEnabled { get; set; }
	public virtual String skillKey { get; }
	public Int32 priority { get; }
	public Ability ability { get; set; }
	public TargetTrigger trigger { get; }
	public PeriodicTimer cooldownTimer { get; }
	public Boolean isUsedUp { get; }
	public Boolean resetMainAbilityCdWhenCastEnd { get; }
	public UnitMode parentMode { get; set; }
	public Boolean isRoot { get; }
	protected ESkillData data { get; set; }
	protected Enemy owner { get; set; }
	protected virtual Boolean recoverSpWhenAffecting { get; }
	protected virtual Boolean immuneStunWhenAffecting { get; }
	private Boolean ownerSkillActivatable { get; }
	protected Boolean registeredAsModifier { get; set; }
	public Boolean isSpCostSkill { get; }
	public Int64 attributeMask { get; }
	public Int64 abnormalFlagMask { get; }
	public Int64 abnormalImmuneMask { get; }
	public Int64 abnormalAntiMask { get; }
	public Int64 abnormalComboMask { get; }
	public Int64 abnormalComboImmuneMask { get; }

	// RVA: 0x3fbb704 VA: 0x75965d3704
	public Boolean get_isEnabled() { }
	// RVA: 0x3fbb794 VA: 0x75965d3794
	public Void set_isEnabled(Boolean value) { }
	// RVA: 0x3fbb8d0 VA: 0x75965d38d0
	public virtual String get_skillKey() { }
	// RVA: 0x3fbb93c VA: 0x75965d393c
	public Int32 get_priority() { }
	// RVA: 0x3fbba1c VA: 0x75965d3a1c
	public Ability get_ability() { }
	// RVA: 0x3fbba84 VA: 0x75965d3a84
	private Void set_ability(Ability value) { }
	// RVA: 0x3fbbb08 VA: 0x75965d3b08
	public TargetTrigger get_trigger() { }
	// RVA: 0x3fbbb70 VA: 0x75965d3b70
	public PeriodicTimer get_cooldownTimer() { }
	// RVA: 0x3fbbbd8 VA: 0x75965d3bd8
	public Boolean get_isUsedUp() { }
	// RVA: 0x3fbbc58 VA: 0x75965d3c58
	public Boolean get_resetMainAbilityCdWhenCastEnd() { }
	// RVA: 0x3fbbcc0 VA: 0x75965d3cc0
	public UnitMode get_parentMode() { }
	// RVA: 0x3fbbd28 VA: 0x75965d3d28
	private Void set_parentMode(UnitMode value) { }
	// RVA: 0x3fbbdac VA: 0x75965d3dac
	public Boolean get_isRoot() { }
	// RVA: 0x3fbb9b4 VA: 0x75965d39b4
	protected ESkillData get_data() { }
	// RVA: 0x3fbbe50 VA: 0x75965d3e50
	private Void set_data(ESkillData value) { }
	// RVA: 0x3fbbed4 VA: 0x75965d3ed4
	protected Enemy get_owner() { }
	// RVA: 0x3fbbf3c VA: 0x75965d3f3c
	private Void set_owner(Enemy value) { }
	// RVA: 0x3fbbfc0 VA: 0x75965d3fc0
	protected virtual Boolean get_recoverSpWhenAffecting() { }
	// RVA: 0x3fbc024 VA: 0x75965d4024
	protected virtual Boolean get_immuneStunWhenAffecting() { }
	// RVA: 0x3fbc08c VA: 0x75965d408c
	private Boolean get_ownerSkillActivatable() { }
	// RVA: 0x3fbc198 VA: 0x75965d4198
	protected Boolean get_registeredAsModifier() { }
	// RVA: 0x3fbc200 VA: 0x75965d4200
	protected Void set_registeredAsModifier(Boolean value) { }
	// RVA: 0x3fbc440 VA: 0x75965d4440
	public Boolean get_isSpCostSkill() { }
	// RVA: 0x3fbc4b0 VA: 0x75965d44b0
	public Int64 get_attributeMask() { }
	// RVA: 0x3fbc514 VA: 0x75965d4514
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x3fbc598 VA: 0x75965d4598
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x3fbc614 VA: 0x75965d4614
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x3fbc678 VA: 0x75965d4678
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x3fbc6dc VA: 0x75965d46dc
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x3fbc740 VA: 0x75965d4740
	public Boolean GetValue(AttributeType attribute, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x3fbc834 VA: 0x75965d4834
	public virtual Void AssignData(ESkillData data, Enemy owner) { }
	// RVA: 0x3fbcc7c VA: 0x75965d4c7c
	public Void Init() { }
	// RVA: 0x3fbcdf4 VA: 0x75965d4df4
	public Void Attach() { }
	// RVA: 0x3fbcf24 VA: 0x75965d4f24
	public Void Detach() { }
	// RVA: 0x3fbd038 VA: 0x75965d5038
	public Boolean CastToTarget(Entity target, Ability mainAbility, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x3fbd3e0 VA: 0x75965d53e0
	public virtual Void ResetSkillCooldownIfNeeded() { }
	// RVA: 0x3fbd4c8 VA: 0x75965d54c8
	public Boolean CheckFamilyMask(FamilyGroup familyGroup) { }
	// RVA: 0x3fbd54c VA: 0x75965d554c
	public Void SetParentMode(UnitMode parentMode) { }
	// RVA: 0x3fbd5cc VA: 0x75965d55cc
	public virtual Boolean CheckTrigger(Boolean allowNoTrigger, Boolean forceRefresh) { }
	// RVA: 0x3fbd700 VA: 0x75965d5700
	public virtual Boolean CheckAvailable() { }
	// RVA: 0x3fbd978 VA: 0x75965d5978
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x3fbdae0 VA: 0x75965d5ae0
	public Void Tick(FP deltaTime) { }
	// RVA: 0x3fbdc2c VA: 0x75965d5c2c
	protected virtual Void OnTick(FP deltaTime) { }
	// RVA: 0x3fbd374 VA: 0x75965d5374
	protected Void OnCastSucceed() { }
	// RVA: 0x3fbb818 VA: 0x75965d3818
	protected Boolean SetEnabledInternal(Boolean value, Boolean force) { }
	// RVA: 0x3fbd21c VA: 0x75965d521c
	protected Boolean TryReduceSp(Int32 spCost) { }
	// RVA: 0x3fbcba8 VA: 0x75965d4ba8
	private static Single _GetRangeRadius(ESkillData data, Enemy owner) { }
	// RVA: 0x3fbdce4 VA: 0x75965d5ce4
	private Void _OnCastStart() { }
	// RVA: 0x3fbddb8 VA: 0x75965d5db8
	private Void _OnCastFinish(Ability ability, FinishReason reason, Boolean firstAttack) { }
	// RVA: 0x3fbc284 VA: 0x75965d4284
	private Void _UpdateRegisterAsModifier(Boolean value, Boolean force) { }
	// RVA: 0x3fbdf8c VA: 0x75965d5f8c
	private Void Awake() { }
	// RVA: 0x3fbe0d0 VA: 0x75965d60d0
	public Void .ctor() { }
}
```
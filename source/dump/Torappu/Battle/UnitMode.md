# UnitMode

**Namespace:** `Torappu.Battle`


## Fields

- `Transform _bodyTransform`

- `UnitAnimatorHooker _animatorHooker`

- `String _overrideStartEffect`

- `String _overrideDeadEffect`

- `Ability _combat`

- `Ability _attack`

- `TargetTrigger _attackTrigger`

- `Boolean _hideUIAttackRange`

- `TargetSelector _rangeToShow`

- `Boolean _addIndexToSignalId`

- `Boolean _includeIndexZero`

- `SerializedBool _alwaysHideHp`

- `Boolean m_inited`

- `String m_rangeId`

- `Unit <host>k__BackingField`

- `Int32 <index>k__BackingField`

- `SourceApplyWay <allApplyWay>k__BackingField`


## Properties

- `Unit host`

- `Int32 index`

- `Transform bodyTransform`

- `Ability combat`

- `Boolean hasCombat`

- `Ability attack`

- `Boolean hasAttack`

- `TargetTrigger attackTrigger`

- `String rangeId`

- `IDrawableRange rangeToShow`

- `Boolean hideUIAttackRange`

- `SourceApplyWay allApplyWay`

- `UnitAnimatorHooker animatorHooker`

- `String overrideStartEffect`

- `String overrideDeadEffect`


## Methods

- `Unit get_host()`

- `Void set_host(Unit)`

- `Int32 get_index()`

- `Void set_index(Int32)`

- `Transform get_bodyTransform()`

- `Ability get_combat()`

- `Boolean get_hasCombat()`

- `Ability get_attack()`

- `Boolean get_hasAttack()`

- `TargetTrigger get_attackTrigger()`

- `String get_rangeId()`

- `IDrawableRange get_rangeToShow()`

- `Boolean get_hideUIAttackRange()`

- `SourceApplyWay get_allApplyWay()`

- `Void set_allApplyWay(SourceApplyWay)`

- `UnitAnimatorHooker get_animatorHooker()`

- `String get_overrideStartEffect()`

- `String get_overrideDeadEffect()`

- `Void set_talents(BasicTalent[])`

- `String GenerateSignalId(String, String, String, Int32)`

- `Void RegisterDynamicAbility(Ability, Blackboard)`

- `Void ClearDynamicAbilities()`

- `Void _InitAbilities()`

- `Void _InitTalents()`

- `Void RecollectTalents()`

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UnitMode : MonoBehaviour, ITalentOwner, IEffectSource
{
	public const String COMBAT_DESCRIPTION_SUFFIX; // 0x0
	public const String ATTACK_DESCRIPTION_SUFFIX; // 0x0
	private Transform _bodyTransform; // 0x18
	private UnitAnimatorHooker _animatorHooker; // 0x20
	private String _overrideStartEffect; // 0x28
	private String _overrideDeadEffect; // 0x30
	private Ability _combat; // 0x38
	private Ability _attack; // 0x40
	private TargetTrigger _attackTrigger; // 0x48
	private Boolean _hideUIAttackRange; // 0x50
	private TargetSelector _rangeToShow; // 0x58
	private TargetSelector[] _extraRangesToShow; // 0x60
	private Ability[] _generalAbilities; // 0x68
	private Boolean _addIndexToSignalId; // 0x70
	private Boolean _includeIndexZero; // 0x71
	private SerializedBool _alwaysHideHp; // 0x78
	private Boolean m_inited; // 0x80
	private List`1 m_abilities; // 0x88
	private List`1 m_dynaimcAbilites; // 0x90
	private String m_rangeId; // 0x98
	private Unit <host>k__BackingField; // 0xa0
	private Int32 <index>k__BackingField; // 0xa8
	private IDrawableRange[] m_extraRangesToShow; // 0xb0
	private SourceApplyWay <allApplyWay>k__BackingField; // 0xb8
	private BasicTalent[] <talents>k__BackingField; // 0xc0

	public Unit host { get; set; }
	public Int32 index { get; set; }
	public Transform bodyTransform { get; }
	public Ability combat { get; }
	public Boolean hasCombat { get; }
	public Ability attack { get; }
	public Boolean hasAttack { get; }
	public TargetTrigger attackTrigger { get; }
	public Nullable`1 alwaysHideHp { get; }
	public String rangeId { get; }
	public IDrawableRange rangeToShow { get; }
	public IDrawableRange[] extraRangesToShow { get; }
	public Boolean hideUIAttackRange { get; }
	public SourceApplyWay allApplyWay { get; set; }
	public List`1 abilities { get; }
	public UnitAnimatorHooker animatorHooker { get; }
	public String overrideStartEffect { get; }
	public String overrideDeadEffect { get; }
	public BasicTalent[] talents { get; set; }

	// RVA: 0x1c37908 VA: 0x759424f908
	public Unit get_host() { }
	// RVA: 0x1c37910 VA: 0x759424f910
	private Void set_host(Unit value) { }
	// RVA: 0x1c37918 VA: 0x759424f918
	public Int32 get_index() { }
	// RVA: 0x1c37920 VA: 0x759424f920
	private Void set_index(Int32 value) { }
	// RVA: 0x1c37928 VA: 0x759424f928
	public Transform get_bodyTransform() { }
	// RVA: 0x1c37930 VA: 0x759424f930
	public Ability get_combat() { }
	// RVA: 0x1c2d258 VA: 0x7594245258
	public Boolean get_hasCombat() { }
	// RVA: 0x1c37938 VA: 0x759424f938
	public Ability get_attack() { }
	// RVA: 0x1c2d3e0 VA: 0x75942453e0
	public Boolean get_hasAttack() { }
	// RVA: 0x1c37940 VA: 0x759424f940
	public TargetTrigger get_attackTrigger() { }
	// RVA: 0x1c29db8 VA: 0x7594241db8
	public Nullable`1 get_alwaysHideHp() { }
	// RVA: 0x1c37948 VA: 0x759424f948
	public String get_rangeId() { }
	// RVA: 0x1c2d8f8 VA: 0x75942458f8
	public IDrawableRange get_rangeToShow() { }
	// RVA: 0x1c2da64 VA: 0x7594245a64
	public IDrawableRange[] get_extraRangesToShow() { }
	// RVA: 0x1c37950 VA: 0x759424f950
	public Boolean get_hideUIAttackRange() { }
	// RVA: 0x1c37958 VA: 0x759424f958
	public SourceApplyWay get_allApplyWay() { }
	// RVA: 0x1c37960 VA: 0x759424f960
	private Void set_allApplyWay(SourceApplyWay value) { }
	// RVA: 0x1c37968 VA: 0x759424f968
	public List`1 get_abilities() { }
	// RVA: 0x1c37970 VA: 0x759424f970
	public UnitAnimatorHooker get_animatorHooker() { }
	// RVA: 0x1c37978 VA: 0x759424f978
	public String get_overrideStartEffect() { }
	// RVA: 0x1c37980 VA: 0x759424f980
	public String get_overrideDeadEffect() { }
	// RVA: 0x1c37988 VA: 0x759424f988
	public BasicTalent[] get_talents() { }
	// RVA: 0x1c37990 VA: 0x759424f990
	private Void set_talents(BasicTalent[] value) { }
	// RVA: 0x1c37998 VA: 0x759424f998
	public virtual Boolean InitOnce(Unit host, Int32 index) { }
	// RVA: 0x1c37d98 VA: 0x759424fd98
	public virtual Void OnInit() { }
	// RVA: 0x1c38438 VA: 0x7594250438
	public virtual Void OnActivate(UnitMode oldMode, Boolean isInit) { }
	// RVA: 0x1c3859c VA: 0x759425059c
	public virtual Void OnInactivate() { }
	// RVA: 0x1c31424 VA: 0x7594249424
	public String GenerateSignalId(String hostId, String tmplId, String suffix, Int32 index) { }
	// RVA: 0x1c32c88 VA: 0x759424ac88
	public Void RegisterDynamicAbility(Ability ability, Blackboard blackboard) { }
	// RVA: 0x1c34280 VA: 0x759424c280
	public Void ClearDynamicAbilities() { }
	// RVA: 0x1c37b28 VA: 0x759424fb28
	private Void _InitAbilities() { }
	// RVA: 0x1c37a78 VA: 0x759424fa78
	private Void _InitTalents() { }
	// RVA: 0x1c386c4 VA: 0x75942506c4
	public Void RecollectTalents() { }
	// RVA: 0x1c30dbc VA: 0x7594248dbc
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1c2c990 VA: 0x7594244990
	public Void .ctor() { }
}
```
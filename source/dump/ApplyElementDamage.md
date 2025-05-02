# ApplyElementDamage

**Namespace:** ` `


## Fields

- `ElementType _elementDamageType`

- `ActionTargetType _sourceType`

- `Boolean _isFixedEpDamage`

- `Boolean _baseOnHostAtk`

- `Boolean _baseOnEnemyHostAtk`

- `String _fixedEpDamageKey`

- `Single _fixedEpDamage`

- `Boolean _noSource`

- `Boolean _forceUseProjectileCachedAtk`

- `Boolean _multiplyWithBuffValidStackCnt`

- `String _buffKey`

- `ActionTargetType _buffSourceType`

- `ActionTargetType _targetType`

- `Boolean _isEnvElementDamage`

- `Boolean _loadElementTypeFromBb`

- `String _fixedEpDamageScale`

- `String _epDamageScale`

- `FP m_cachedAtkEp`

- `SideType m_cacheSideType`

- `FP m_epDamageRatio`

- `FP m_epDamageScale`


## Properties

- `Boolean multiplyWithBuffValidStackCnt`

- `Boolean isFixedEpDamage`

- `FP epDamageScale`

- `FP epDamageRatio`

- `ActionPurposeMask purposeMask`


## Methods

- `Boolean get_multiplyWithBuffValidStackCnt()`

- `Boolean get_isFixedEpDamage()`

- `FP get_epDamageScale()`

- `Void set_epDamageScale(FP)`

- `FP get_epDamageRatio()`

- `ActionPurposeMask get_purposeMask()`

- `Boolean _CheckNodeInvalid(Entity, Entity)`

- `Void PreprocessForProjectile(Entity)`

- `Void DeliverPreprocessPara(ApplyElementDamage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyElementDamage : ActionNode, IDamageOrHealSourceNode
{
	protected ElementType _elementDamageType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private Boolean _isFixedEpDamage; // 0x18
	private Boolean _baseOnHostAtk; // 0x19
	private Boolean _baseOnEnemyHostAtk; // 0x1a
	private String _fixedEpDamageKey; // 0x20
	private Single _fixedEpDamage; // 0x28
	private Boolean _noSource; // 0x2c
	private Boolean _forceUseProjectileCachedAtk; // 0x2d
	private Boolean _multiplyWithBuffValidStackCnt; // 0x2e
	private String _buffKey; // 0x30
	private ActionTargetType _buffSourceType; // 0x38
	private ActionTargetType _targetType; // 0x3c
	private Boolean _isEnvElementDamage; // 0x40
	private Boolean _loadElementTypeFromBb; // 0x41
	private String _fixedEpDamageScale; // 0x48
	private String _epDamageScale; // 0x50
	protected FP m_cachedAtkEp; // 0x58
	protected SideType m_cacheSideType; // 0x60
	private FP m_epDamageRatio; // 0x68
	private FP m_epDamageScale; // 0x70
	private static DelegateBridge __Hotfix0_get_multiplyWithBuffValidStackCnt; // 0x0
	private static DelegateBridge __Hotfix0_get_isFixedEpDamage; // 0x8
	private static DelegateBridge __Hotfix0_get_epDamageScale; // 0x10
	private static DelegateBridge __Hotfix0_set_epDamageScale; // 0x18
	private static DelegateBridge __Hotfix0_get_epDamageRatio; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x28
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x30
	private static DelegateBridge __Hotfix0__CheckNodeInvalid; // 0x38
	private static DelegateBridge __Hotfix0_Execute; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48
	private static DelegateBridge _c__Hotfix1_ctor; // 0x50
	private static DelegateBridge __Hotfix0_CreateElementDamageModifier; // 0x58
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x60
	private static DelegateBridge __Hotfix0_DeliverPreprocessPara; // 0x68

	protected Boolean multiplyWithBuffValidStackCnt { get; }
	protected Boolean isFixedEpDamage { get; }
	public FP epDamageScale { get; set; }
	public FP epDamageRatio { get; }
	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f4a288 VA: 0x7594562288
	protected Boolean get_multiplyWithBuffValidStackCnt() { }
	// RVA: 0x1f4a2f0 VA: 0x75945622f0
	protected Boolean get_isFixedEpDamage() { }
	// RVA: 0x1f4a358 VA: 0x7594562358
	public FP get_epDamageScale() { }
	// RVA: 0x1f4a3c0 VA: 0x75945623c0
	public Void set_epDamageScale(FP value) { }
	// RVA: 0x1f4a43c VA: 0x759456243c
	public FP get_epDamageRatio() { }
	// RVA: 0x1f4a4a4 VA: 0x75945624a4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4a50c VA: 0x759456250c
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f4a574 VA: 0x7594562574
	private Boolean _CheckNodeInvalid(Entity source, Entity target) { }
	// RVA: 0x1f4a6f8 VA: 0x75945626f8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4aba4 VA: 0x7594562ba4
	public Void .ctor() { }
	// RVA: 0x1f4acc4 VA: 0x7594562cc4
	public Void .ctor(ElementType elementType, FP epDamageRatio) { }
	// RVA: 0x1f4ae08 VA: 0x7594562e08
	public virtual Modifier CreateElementDamageModifier(Entity source, Entity target) { }
	// RVA: 0x1f4b1e0 VA: 0x75945631e0
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f4b31c VA: 0x759456331c
	public Void DeliverPreprocessPara(ApplyElementDamage anotherNode) { }
}
```
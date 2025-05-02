# ApplyElementHeal

**Namespace:** ` `


## Fields

- `Boolean _isCont`

- `ActionTargetType _healTarget`

- `Boolean _maxEpHeal`

- `Boolean m_forceUseCacheAtk`

- `FP m_epHealRatio`

- `Boolean m_ignoreHealFree`

- `FP m_cachedAtk`


## Properties

- `ActionPurposeMask purposeMask`

- `FP elementHealScale`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `FP get_elementHealScale()`

- `Void set_elementHealScale(FP)`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyElementHeal : ActionNode, IDamageOrHealSourceNode
{
	private Boolean _isCont; // 0x10
	private ActionTargetType _healTarget; // 0x14
	private Boolean _maxEpHeal; // 0x18
	private Boolean m_forceUseCacheAtk; // 0x19
	private FP m_epHealRatio; // 0x20
	private Boolean m_ignoreHealFree; // 0x28
	private FP m_cachedAtk; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_get_elementHealScale; // 0x18
	private static DelegateBridge __Hotfix0_set_elementHealScale; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28
	private static DelegateBridge _c__Hotfix1_ctor; // 0x30
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x38

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }
	public FP elementHealScale { get; set; }

	// RVA: 0x1f5e8c0 VA: 0x75945768c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5e928 VA: 0x7594576928
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5e990 VA: 0x7594576990
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5ec9c VA: 0x7594576c9c
	public FP get_elementHealScale() { }
	// RVA: 0x1f5ed04 VA: 0x7594576d04
	public Void set_elementHealScale(FP value) { }
	// RVA: 0x1f5ed80 VA: 0x7594576d80
	public Void .ctor() { }
	// RVA: 0x1f5ee34 VA: 0x7594576e34
	public Void .ctor(FP epHealScale, Boolean isCont, Boolean ignoreHealFree) { }
	// RVA: 0x1f5ef38 VA: 0x7594576f38
	public Void PreprocessForProjectile(Entity source) { }
}
```
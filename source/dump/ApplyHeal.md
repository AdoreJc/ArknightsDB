# ApplyHeal

**Namespace:** ` `


## Fields

- `Boolean _isCont`

- `Boolean _isHpRatio`

- `Boolean m_forceUseCacheAtk`

- `FP m_healScale`

- `Boolean m_ignoreHealFree`

- `FP m_cachedAtk`


## Properties

- `ActionPurposeMask purposeMask`

- `FP healScale`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `FP get_healScale()`

- `Void set_healScale(FP)`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyHeal : ActionNode, IDamageOrHealSourceNode
{
	private Boolean _isCont; // 0x10
	private Boolean _isHpRatio; // 0x11
	private Boolean m_forceUseCacheAtk; // 0x12
	private FP m_healScale; // 0x18
	private Boolean m_ignoreHealFree; // 0x20
	private FP m_cachedAtk; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_get_healScale; // 0x10
	private static DelegateBridge __Hotfix0_set_healScale; // 0x18
	private static DelegateBridge __Hotfix0_Execute; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28
	private static DelegateBridge _c__Hotfix1_ctor; // 0x30
	private static DelegateBridge _c__Hotfix2_ctor; // 0x38
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x40

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }
	public FP healScale { get; set; }

	// RVA: 0x1f5ae00 VA: 0x7594572e00
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5ae68 VA: 0x7594572e68
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5aed0 VA: 0x7594572ed0
	public FP get_healScale() { }
	// RVA: 0x1f5af38 VA: 0x7594572f38
	public Void set_healScale(FP value) { }
	// RVA: 0x1f5afb4 VA: 0x7594572fb4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5b280 VA: 0x7594573280
	public Void .ctor() { }
	// RVA: 0x1f5b334 VA: 0x7594573334
	public Void .ctor(FP healScale, Boolean isCont, Boolean isHpRatio, Boolean ignoreHealFree) { }
	// RVA: 0x1f5b454 VA: 0x7594573454
	public Void .ctor(FP healScale, Boolean isCont, Boolean isHpRatio, Boolean ignoreHealFree, Boolean forceUseCacheAtk) { }
	// RVA: 0x1f5b58c VA: 0x759457358c
	public Void PreprocessForProjectile(Entity source) { }
}
```
# DamageScaleAccordingToHpRatio

**Namespace:** ` `


## Fields

- `Boolean _filterDamageType`

- `DamageTypeMask _damageMask`

- `Boolean _filterApplyWay`

- `SourceApplyWay _applyWayFilter`

- `Single _minHpRatio`

- `Single _maxHpRatio`

- `String _minAddOnScaleKey`

- `String _maxAddOnScaleKey`

- `ActionTargetType _hpRatioSource`


## Methods

- `Boolean CalculateFinalValue(Blackboard, ref, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageScaleAccordingToHpRatio : ActionNode
{
	private Boolean _filterDamageType; // 0x10
	private DamageTypeMask _damageMask; // 0x14
	private Boolean _filterApplyWay; // 0x18
	private SourceApplyWay _applyWayFilter; // 0x1c
	private Single _minHpRatio; // 0x20
	private Single _maxHpRatio; // 0x24
	private String _minAddOnScaleKey; // 0x28
	private String _maxAddOnScaleKey; // 0x30
	private ActionTargetType _hpRatioSource; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_CalculateFinalValue; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f43894 VA: 0x759455b894
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f438fc VA: 0x759455b8fc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f43b38 VA: 0x759455bb38
	protected Boolean CalculateFinalValue(Blackboard blackboard, ref Snapshot snapshot, out FP finalValue) { }
	// RVA: 0x1f43e38 VA: 0x759455be38
	public Void .ctor() { }
}
```
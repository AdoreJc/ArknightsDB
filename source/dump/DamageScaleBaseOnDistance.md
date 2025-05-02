# DamageScaleBaseOnDistance

**Namespace:** ` `


## Fields

- `Boolean _filterDamageType`

- `DamageTypeMask _damageMask`

- `Boolean _filterApplyWay`

- `SourceApplyWay _applyWayFilter`

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Single _maxScale`

- `Single _minTriggerDistance`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageScaleBaseOnDistance : ActionNode
{
	private Boolean _filterDamageType; // 0x10
	private DamageTypeMask _damageMask; // 0x14
	private Boolean _filterApplyWay; // 0x18
	private SourceApplyWay _applyWayFilter; // 0x1c
	private ActionTargetType _sourceType; // 0x20
	private ActionTargetType _targetType; // 0x24
	private Single _maxScale; // 0x28
	private Single _minTriggerDistance; // 0x2c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f432b4 VA: 0x759455b2b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4331c VA: 0x759455b31c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f43818 VA: 0x759455b818
	public Void .ctor() { }
}
```
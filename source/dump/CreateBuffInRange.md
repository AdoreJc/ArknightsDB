# CreateBuffInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `TargetOptions _targetOptions`

- `Boolean _excludeTarget`

- `Boolean _excludeCurAtkTarget`

- `Boolean _alwaysIncudeCurAtkTarget`

- `Boolean _randomTarget`

- `Boolean _limitMaxTarget`

- `Boolean _useAttackRange`

- `Boolean _useCurrentModeRange`

- `Boolean _useRangeToShow`

- `String _rangeId`

- `Boolean _useRadius`

- `Boolean _useGlobalRange`

- `Single _radius`

- `Boolean _filterByBuildableType`

- `BuildableType _allowedBuildableType`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Properties

- `Boolean isNotUseAttackRange`


## Methods

- `Boolean get_isNotUseAttackRange()`

- `Void _DoAddBuffToTargets(Entity, Entity, Blackboard, ref, ReusableList`1)`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffInRange : ActionNode, IBuffSource
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private TargetOptions _targetOptions; // 0x18
	private Boolean _excludeTarget; // 0x78
	private Boolean _excludeCurAtkTarget; // 0x79
	private Boolean _alwaysIncudeCurAtkTarget; // 0x7a
	private Boolean _randomTarget; // 0x7b
	private Boolean _limitMaxTarget; // 0x7c
	private Boolean _useAttackRange; // 0x7d
	private Boolean _useCurrentModeRange; // 0x7e
	private Boolean _useRangeToShow; // 0x7f
	private String _rangeId; // 0x80
	private Boolean _useRadius; // 0x88
	private Boolean _useGlobalRange; // 0x89
	private Single _radius; // 0x8c
	private Boolean _filterByBuildableType; // 0x90
	private BuildableType _allowedBuildableType; // 0x94
	private BuffData[] _buffs; // 0x98
	private Boolean _isDerivedBuff; // 0xa0
	private Boolean _finishDerivedBuffIfParentFinish; // 0xa1
	private List`1 m_excludeTargets; // 0xa8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_isNotUseAttackRange; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0__DoAddBuffToTargets; // 0x18
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }
	private Boolean isNotUseAttackRange { get; }

	// RVA: 0x1efaa68 VA: 0x7594512a68
	public override SourceType get_allowedSource() { }
	// RVA: 0x1efaad0 VA: 0x7594512ad0
	private Boolean get_isNotUseAttackRange() { }
	// RVA: 0x1efab40 VA: 0x7594512b40
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1efbd0c VA: 0x7594513d0c
	private Void _DoAddBuffToTargets(Entity source, Entity target, Blackboard blackboard, ref Snapshot snapshot, ReusableList`1 targets) { }
	// RVA: 0x1efc5bc VA: 0x75945145bc
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1efc670 VA: 0x7594514670
	public Void .ctor() { }
}
```
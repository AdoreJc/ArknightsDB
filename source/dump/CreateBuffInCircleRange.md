# CreateBuffInCircleRange

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `TargetOptions _targetOptions`

- `Boolean _excludeTarget`

- `Single _rangeRadius`

- `Boolean _checkInArcCircle`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Properties

- `Boolean checkInArcCircle`


## Methods

- `Boolean get_checkInArcCircle()`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffInCircleRange : ActionNode, IBuffSource
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private TargetOptions _targetOptions; // 0x18
	private Boolean _excludeTarget; // 0x78
	private Single _rangeRadius; // 0x7c
	private Boolean _checkInArcCircle; // 0x80
	private Vector2[] _degreeRanges; // 0x88
	private BuffData[] _buffs; // 0x90
	private Boolean _isDerivedBuff; // 0x98
	private Boolean _finishDerivedBuffIfParentFinish; // 0x99
	private List`1 m_excludeTargets; // 0xa0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_checkInArcCircle; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	private Boolean checkInArcCircle { get; }

	// RVA: 0x1f059b0 VA: 0x759451d9b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f05a18 VA: 0x759451da18
	private Boolean get_checkInArcCircle() { }
	// RVA: 0x1f05a80 VA: 0x759451da80
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f063e4 VA: 0x759451e3e4
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f06498 VA: 0x759451e498
	public Void .ctor() { }
}
```
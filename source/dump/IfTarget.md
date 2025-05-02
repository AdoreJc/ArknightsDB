# IfTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `MotionMask _motionMask`

- `Boolean _checkTargetAlive`

- `Boolean _checkApplyWay`

- `Boolean _checkTargetUnitType`

- `UnitType _unitType`

- `SourceApplyWay _applyWay`

- `Boolean _checkTargetFree`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IfTarget : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private MotionMask _motionMask; // 0x14
	private Boolean _checkTargetAlive; // 0x18
	private Boolean _checkApplyWay; // 0x19
	private Boolean _checkTargetUnitType; // 0x1a
	private UnitType _unitType; // 0x1c
	private SourceApplyWay _applyWay; // 0x20
	private Boolean _checkTargetFree; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f140d4 VA: 0x759452c0d4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1413c VA: 0x759452c13c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f14384 VA: 0x759452c384
	public Void .ctor() { }
}
```
# SandboxRecordUnitState

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _additionHpRatioKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxRecordUnitState : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _additionHpRatioKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f881f8 VA: 0x75945a01f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f88260 VA: 0x75945a0260
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f88878 VA: 0x75945a0878
	public Void .ctor() { }
}
```
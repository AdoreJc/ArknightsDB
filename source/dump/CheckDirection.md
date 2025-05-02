# CheckDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `JudgeType _judgeType`


## Methods

- `Vector2 _GetDirectionVector(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckDirection : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private JudgeType _judgeType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__GetDirectionVector; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1e648 VA: 0x7594536648
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1e6b0 VA: 0x75945366b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1e978 VA: 0x7594536978
	private Vector2 _GetDirectionVector(Entity entity) { }
	// RVA: 0x1f1eaf0 VA: 0x7594536af0
	public Void .ctor() { }
}
```
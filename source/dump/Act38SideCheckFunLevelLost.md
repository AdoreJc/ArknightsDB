# Act38SideCheckFunLevelLost

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act38SideCheckFunLevelLost : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee12a0 VA: 0x75944f92a0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee1308 VA: 0x75944f9308
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee14a0 VA: 0x75944f94a0
	public Void .ctor() { }
}
```
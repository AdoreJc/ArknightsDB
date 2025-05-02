# CharSearchBlockeeImmediate

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharSearchBlockeeImmediate : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc64c8 VA: 0x75945de4c8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc6530 VA: 0x75945de530
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc66a0 VA: 0x75945de6a0
	public Void .ctor() { }
}
```
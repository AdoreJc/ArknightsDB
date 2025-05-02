# FilterByOccupiedRemainingCharacterCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByOccupiedRemainingCharacterCnt : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fdaf10 VA: 0x75945f2f10
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fdaf78 VA: 0x75945f2f78
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdb0f8 VA: 0x75945f30f8
	public Void .ctor() { }
}
```
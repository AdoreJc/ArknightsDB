# AssignBuffExistingTimeIntoBlackboard

**Namespace:** ` `


## Fields

- `String _extraDurationKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignBuffExistingTimeIntoBlackboard : ActionNode
{
	private String _extraDurationKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eec780 VA: 0x7594504780
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eec7e8 VA: 0x75945047e8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eec8cc VA: 0x75945048cc
	public Void .ctor() { }
}
```
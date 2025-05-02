# AssignGlobalBlackboardToBlackboard

**Namespace:** ` `


## Fields

- `String _globalblackboardKey`

- `String _blackboardKey`

- `BlackboardChannel _channel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignGlobalBlackboardToBlackboard : ActionNode
{
	private String _globalblackboardKey; // 0x10
	private String _blackboardKey; // 0x18
	private BlackboardChannel _channel; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef453c VA: 0x759450c53c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef45a4 VA: 0x759450c5a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef4704 VA: 0x759450c704
	public Void .ctor() { }
}
```
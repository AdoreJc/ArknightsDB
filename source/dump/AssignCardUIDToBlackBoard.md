# AssignCardUIDToBlackBoard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackBoardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignCardUIDToBlackBoard : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackBoardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eef384 VA: 0x7594507384
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eef3ec VA: 0x75945073ec
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eef598 VA: 0x7594507598
	public Void .ctor() { }
}
```
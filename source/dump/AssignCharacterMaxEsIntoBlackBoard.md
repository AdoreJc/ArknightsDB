# AssignCharacterMaxEsIntoBlackBoard

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignCharacterMaxEsIntoBlackBoard : ActionNode
{
	private String _blackboardKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eee948 VA: 0x7594506948
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eee9b0 VA: 0x75945069b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eeeb3c VA: 0x7594506b3c
	public Void .ctor() { }
}
```
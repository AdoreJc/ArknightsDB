# AssignCharacterCostIntoBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignCharacterCostIntoBlackboard : ActionNode
{
	private String _blackboardKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef2200 VA: 0x759450a200
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef2268 VA: 0x759450a268
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef2458 VA: 0x759450a458
	public Void .ctor() { }
}
```
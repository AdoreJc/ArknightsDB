# AssignCurSpToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `Boolean _isRatio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignCurSpToBB : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private Boolean _isRatio; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef24d0 VA: 0x759450a4d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef2538 VA: 0x759450a538
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef26a0 VA: 0x759450a6a0
	public Void .ctor() { }
}
```
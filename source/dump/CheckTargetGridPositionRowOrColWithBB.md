# CheckTargetGridPositionRowOrColWithBB

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _checkRow`

- `String _blackboardKey`

- `CompareType _compareType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTargetGridPositionRowOrColWithBB : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _checkRow; // 0x14
	private String _blackboardKey; // 0x18
	private CompareType _compareType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f336b0 VA: 0x759454b6b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f33718 VA: 0x759454b718
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f33914 VA: 0x759454b914
	public Void .ctor() { }
}
```
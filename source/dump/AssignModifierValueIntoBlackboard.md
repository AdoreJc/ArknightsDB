# AssignModifierValueIntoBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `Boolean _filterModifierCancelled`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignModifierValueIntoBlackboard : ActionNode
{
	private String _blackboardKey; // 0x10
	private Boolean _filterModifierCancelled; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eec93c VA: 0x759450493c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eec9a4 VA: 0x75945049a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eecae0 VA: 0x7594504ae0
	public Void .ctor() { }
}
```
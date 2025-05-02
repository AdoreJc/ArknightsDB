# AssignModifierRealDeltaToBB

**Namespace:** ` `


## Fields

- `TargetType _modifierTargetType`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignModifierRealDeltaToBB : ActionNode
{
	private TargetType _modifierTargetType; // 0x10
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f74af0 VA: 0x759458caf0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f74b58 VA: 0x759458cb58
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f74c74 VA: 0x759458cc74
	public Void .ctor() { }
}
```
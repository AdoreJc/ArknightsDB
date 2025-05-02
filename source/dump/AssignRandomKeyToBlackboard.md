# AssignRandomKeyToBlackboard

**Namespace:** ` `


## Fields

- `String _targetBB`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignRandomKeyToBlackboard : ActionNode
{
	private String _targetBB; // 0x10
	private List`1 _keys; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef3bf0 VA: 0x759450bbf0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef3c58 VA: 0x759450bc58
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef3f74 VA: 0x759450bf74
	public Void .ctor() { }
}
```
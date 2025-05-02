# AssignCharacterSharedBBToBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _character`

- `String _sourceBBKey`

- `String _targetBBKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignCharacterSharedBBToBlackboard : ActionNode
{
	private ActionTargetType _character; // 0x10
	private String _sourceBBKey; // 0x18
	private String _targetBBKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef4038 VA: 0x759450c038
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef40a0 VA: 0x759450c0a0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef4268 VA: 0x759450c268
	public Void .ctor() { }
}
```
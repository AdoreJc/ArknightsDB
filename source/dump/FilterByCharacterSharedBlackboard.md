# FilterByCharacterSharedBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _blackboardKey`

- `Single _valueToCompare`

- `String _valueToCompareKey`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByCharacterSharedBlackboard : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _blackboardKey; // 0x18
	private Single _valueToCompare; // 0x20
	private String _valueToCompareKey; // 0x28
	private CompareType _condType; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f32038 VA: 0x759454a038
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f320a0 VA: 0x759454a0a0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f32318 VA: 0x759454a318
	public Void .ctor() { }
}
```
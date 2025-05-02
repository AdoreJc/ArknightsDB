# FilterTileBlackboard

**Namespace:** ` `


## Fields

- `Boolean _useTargetRoottile`

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `Int32 _valueToCompare`

- `String _anotherKeyToCompare`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterTileBlackboard : ActionNode
{
	private Boolean _useTargetRoottile; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _blackboardKey; // 0x18
	private Int32 _valueToCompare; // 0x20
	private String _anotherKeyToCompare; // 0x28
	private CompareType _condType; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f217f0 VA: 0x75945397f0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f21858 VA: 0x7594539858
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f21afc VA: 0x7594539afc
	public Void .ctor() { }
}
```
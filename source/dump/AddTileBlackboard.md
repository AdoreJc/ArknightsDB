# AddTileBlackboard

**Namespace:** ` `


## Fields

- `Boolean _useTargetRootTile`

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `Single _addition`

- `String _additionKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddTileBlackboard : ActionNode
{
	private Boolean _useTargetRootTile; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _blackboardKey; // 0x18
	private Single _addition; // 0x20
	private String _additionKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe80f8 VA: 0x75946000f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe8160 VA: 0x7594600160
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe8378 VA: 0x7594600378
	public Void .ctor() { }
}
```
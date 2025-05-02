# ModifyTileBlackboard

**Namespace:** ` `


## Fields

- `Boolean _useTargetRoottile`

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `Single _value`

- `String _valueKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyTileBlackboard : ActionNode
{
	private Boolean _useTargetRoottile; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _blackboardKey; // 0x18
	private Single _value; // 0x20
	private String _valueKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe7e60 VA: 0x75945ffe60
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe7ec8 VA: 0x75945ffec8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe8080 VA: 0x7594600080
	public Void .ctor() { }
}
```
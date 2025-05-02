# AddGlobalBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `BlackboardChannel _channel`

- `Single _value`

- `String _valueBlackboardKey`

- `Boolean _addString`

- `String _valueStr`

- `Boolean _overwrite`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddGlobalBlackboard : ActionNode
{
	private String _blackboardKey; // 0x10
	private BlackboardChannel _channel; // 0x18
	private Single _value; // 0x1c
	private String _valueBlackboardKey; // 0x20
	private Boolean _addString; // 0x28
	private String _valueStr; // 0x30
	private Boolean _overwrite; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f13a2c VA: 0x759452ba2c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f13a94 VA: 0x759452ba94
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f13c68 VA: 0x759452bc68
	public Void .ctor() { }
}
```
# ModifyBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKeys`

- `String _fromBlackboardKeys`

- `Single _value`

- `Boolean _addBasedOriginValue`

- `Boolean _checkFromBlackboardValue`


## Properties

- `Boolean fromBlackboardKeysValid`


## Methods

- `Boolean get_fromBlackboardKeysValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyBlackboard : ActionNode
{
	private String _blackboardKeys; // 0x10
	private String _fromBlackboardKeys; // 0x18
	private Single _value; // 0x20
	private Boolean _addBasedOriginValue; // 0x24
	private Boolean _checkFromBlackboardValue; // 0x25
	private static DelegateBridge __Hotfix0_get_fromBlackboardKeysValid; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Boolean fromBlackboardKeysValid { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f99070 VA: 0x75945b1070
	protected Boolean get_fromBlackboardKeysValid() { }
	// RVA: 0x1f990e8 VA: 0x75945b10e8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f99150 VA: 0x75945b1150
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f99304 VA: 0x75945b1304
	public Void .ctor() { }
}
```
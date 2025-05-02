# ModifyBlackboardStr

**Namespace:** ` `


## Fields

- `String _blackboardKeys`

- `String _fromBlackboardKeys`

- `String _value`

- `Boolean _checkFromBlackboardValue`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyBlackboardStr : ActionNode
{
	private String _blackboardKeys; // 0x10
	private String _fromBlackboardKeys; // 0x18
	private String _value; // 0x20
	private Boolean _checkFromBlackboardValue; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f99374 VA: 0x75945b1374
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f993dc VA: 0x75945b13dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f99510 VA: 0x75945b1510
	public Void .ctor() { }
}
```
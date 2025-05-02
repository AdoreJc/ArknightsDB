# AutoChessAddGlobalBlackboardWithInstId

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `BlackboardChannel _channel`

- `Single _value`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessAddGlobalBlackboardWithInstId : ActionNode
{
	private String _blackboardKey; // 0x10
	private BlackboardChannel _channel; // 0x18
	private Single _value; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee6d70 VA: 0x75944fed70
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee6dd8 VA: 0x75944fedd8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee6fb0 VA: 0x75944fefb0
	public Void .ctor() { }
}
```
# FilterByGlobalBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `BlackboardChannel _channel`

- `Single _valueToCompare`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByGlobalBlackboard : ActionNode
{
	private String _blackboardKey; // 0x10
	private BlackboardChannel _channel; // 0x18
	private Single _valueToCompare; // 0x1c
	private CompareType _condType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f323b8 VA: 0x759454a3b8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f32420 VA: 0x759454a420
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f32618 VA: 0x759454a618
	public Void .ctor() { }
}
```
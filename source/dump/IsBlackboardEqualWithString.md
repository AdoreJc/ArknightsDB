# IsBlackboardEqualWithString

**Namespace:** ` `


## Fields

- `String _var`

- `String _compareValue`

- `Boolean _useBuffBlackboard`

- `String _buffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IsBlackboardEqualWithString : ActionNode
{
	private String _var; // 0x10
	private String _compareValue; // 0x18
	private Boolean _useBuffBlackboard; // 0x20
	private String _buffKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eebfe8 VA: 0x7594503fe8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eec050 VA: 0x7594504050
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eec210 VA: 0x7594504210
	public Void .ctor() { }
}
```
# RistarMove

**Namespace:** ` `


## Fields

- `Boolean _isAllyTrigger`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RistarMove : ActionNode
{
	private Boolean _isAllyTrigger; // 0x10
	private List`1 _tileKeyList; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f59cac VA: 0x7594571cac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f59d14 VA: 0x7594571d14
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5a1cc VA: 0x75945721cc
	public Void .ctor() { }
}
```
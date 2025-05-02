# PickRandomBranchPhase

**Namespace:** ` `


## Fields

- `Boolean _notRepeatInOneLoop`

- `Boolean _blockGameFinish`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PickRandomBranchPhase : ActionNode
{
	private Boolean _notRepeatInOneLoop; // 0x10
	private Boolean _blockGameFinish; // 0x11
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f95fec VA: 0x75945adfec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f96054 VA: 0x75945ae054
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f96194 VA: 0x75945ae194
	public Void .ctor() { }
}
```
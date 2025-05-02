# IsBlackboardZero

**Namespace:** ` `


## Fields

- `String _var`

- `Boolean _noVarShowWarning`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IsBlackboardZero : ActionNode
{
	private String _var; // 0x10
	private Boolean _noVarShowWarning; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eebdec VA: 0x7594503dec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eebe54 VA: 0x7594503e54
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eebf70 VA: 0x7594503f70
	public Void .ctor() { }
}
```
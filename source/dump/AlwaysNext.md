# AlwaysNext

**Namespace:** ` `


## Methods

- `ExecuteCondition <>xLuaBaseProxy_get_executeCondition()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AlwaysNext : ActionNode
{
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_executeCondition; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public override ExecuteCondition executeCondition { get; }

	// RVA: 0x1f13ef8 VA: 0x759452bef8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f13f60 VA: 0x759452bf60
	public override ExecuteCondition get_executeCondition() { }
	// RVA: 0x1f13fc4 VA: 0x759452bfc4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1405c VA: 0x759452c05c
	public Void .ctor() { }
	// RVA: 0x1f140cc VA: 0x759452c0cc
	private ExecuteCondition <>xLuaBaseProxy_get_executeCondition() { }
}
```
# IfNot

**Namespace:** ` `


## Methods

- `ExecuteCondition <>xLuaBaseProxy_get_executeCondition()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IfNot : ActionNode
{
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_executeCondition; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public override ExecuteCondition executeCondition { get; }

	// RVA: 0x1f13d18 VA: 0x759452bd18
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f13d80 VA: 0x759452bd80
	public override ExecuteCondition get_executeCondition() { }
	// RVA: 0x1f13de8 VA: 0x759452bde8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f13e80 VA: 0x759452be80
	public Void .ctor() { }
	// RVA: 0x1f13ef0 VA: 0x759452bef0
	private ExecuteCondition <>xLuaBaseProxy_get_executeCondition() { }
}
```
# LuaNode

**Namespace:** ` `


## Fields

- `String _luaActionName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LuaNode : ActionNode
{
	private String _luaActionName; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6cdcc VA: 0x7594584dcc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6ce34 VA: 0x7594584e34
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6cf00 VA: 0x7594584f00
	public Void .ctor() { }
}
```
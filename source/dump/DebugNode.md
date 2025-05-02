# DebugNode

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DebugNode : ActionNode
{
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee8f6c VA: 0x7594500f6c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee8fd4 VA: 0x7594500fd4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee90ec VA: 0x75945010ec
	public Void .ctor() { }
}
```
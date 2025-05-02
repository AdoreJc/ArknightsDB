# ModifyDynamicVar

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyDynamicVar : ActionNode
{
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f009c0 VA: 0x75945189c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f00a28 VA: 0x7594518a28
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f00bf8 VA: 0x7594518bf8
	public Void .ctor() { }
}
```
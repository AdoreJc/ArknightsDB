# CheckTriggerable

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTriggerable : ActionNode
{
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1effb40 VA: 0x7594517b40
	public override SourceType get_allowedSource() { }
	// RVA: 0x1effba8 VA: 0x7594517ba8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1effc5c VA: 0x7594517c5c
	public Void .ctor() { }
}
```
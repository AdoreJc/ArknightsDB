# SkipStage

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SkipStage : ActionNode
{
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f36e20 VA: 0x759454ee20
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f36e88 VA: 0x759454ee88
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f37784 VA: 0x759454f784
	public Void .ctor() { }
}
```
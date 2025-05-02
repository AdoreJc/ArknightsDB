# FilterDeathReason

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `FinishReason _finishReason`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterDeathReason : ActionNode
{
	private ActionTargetType _source; // 0x10
	private FinishReason _finishReason; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1ff30 VA: 0x7594537f30
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1ff98 VA: 0x7594537f98
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f200cc VA: 0x75945380cc
	public Void .ctor() { }
}
```
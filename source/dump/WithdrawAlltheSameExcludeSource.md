# WithdrawAlltheSameExcludeSource

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `Boolean _skipReborn`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class WithdrawAlltheSameExcludeSource : ActionNode
{
	private ActionTargetType _source; // 0x10
	private Boolean _skipReborn; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0ed4c VA: 0x7594526d4c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0edb4 VA: 0x7594526db4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0f1e8 VA: 0x75945271e8
	public Void .ctor() { }
}
```
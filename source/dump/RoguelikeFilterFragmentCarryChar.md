# RoguelikeFilterFragmentCarryChar

**Namespace:** ` `


## Fields

- `ActionTargetType _source`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoguelikeFilterFragmentCarryChar : ActionNode
{
	private ActionTargetType _source; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f80abc VA: 0x7594598abc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f80b24 VA: 0x7594598b24
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f80e14 VA: 0x7594598e14
	public Void .ctor() { }
}
```
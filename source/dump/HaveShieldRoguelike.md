# HaveShieldRoguelike

**Namespace:** ` `


## Fields

- `Boolean _onlyCheckWhetherHaveShieldWhenEnteringBattle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HaveShieldRoguelike : ActionNode
{
	private Boolean _onlyCheckWhetherHaveShieldWhenEnteringBattle; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7e830 VA: 0x7594596830
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7e898 VA: 0x7594596898
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7e9fc VA: 0x75945969fc
	public Void .ctor() { }
}
```
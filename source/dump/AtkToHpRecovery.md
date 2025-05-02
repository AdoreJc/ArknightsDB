# AtkToHpRecovery

**Namespace:** ` `


## Fields

- `Boolean _getAtkFromTarget`

- `ActionTargetType _getAtkTargetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AtkToHpRecovery : ActionNode
{
	private Boolean _getAtkFromTarget; // 0x10
	private ActionTargetType _getAtkTargetType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f34614 VA: 0x759454c614
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3467c VA: 0x759454c67c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f348d8 VA: 0x759454c8d8
	public Void .ctor() { }
}
```
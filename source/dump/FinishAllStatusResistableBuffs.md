# FinishAllStatusResistableBuffs

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishAllStatusResistableBuffs : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f03238 VA: 0x759451b238
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f032a0 VA: 0x759451b2a0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f033c4 VA: 0x759451b3c4
	public Void .ctor() { }
}
```
# UnregisterMagicCircuitSpAffect

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UnregisterMagicCircuitSpAffect : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6d954 VA: 0x7594585954
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6d9bc VA: 0x75945859bc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6db84 VA: 0x7594585b84
	public Void .ctor() { }
}
```
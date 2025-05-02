# UnregisterMagicCircuitRoute

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UnregisterMagicCircuitRoute : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6d1d4 VA: 0x75945851d4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6d23c VA: 0x759458523c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6d3f4 VA: 0x75945853f4
	public Void .ctor() { }
}
```
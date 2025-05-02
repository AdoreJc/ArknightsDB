# FilterModifierByRealDelta

**Namespace:** ` `


## Fields

- `TargetType _modifierTargetType`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterModifierByRealDelta : ActionNode
{
	private TargetType _modifierTargetType; // 0x10
	private CompareType _condType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f748b8 VA: 0x759458c8b8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f74920 VA: 0x759458c920
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f74a80 VA: 0x759458ca80
	public Void .ctor() { }
}
```
# AssignAbilityBlackboardFromOthers

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _sourceAbilityName`

- `ActionTargetType _targetType`

- `String _targetAbilityName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignAbilityBlackboardFromOthers : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _sourceAbilityName; // 0x18
	private ActionTargetType _targetType; // 0x20
	private String _targetAbilityName; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcd7d4 VA: 0x75945e57d4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcd83c VA: 0x75945e583c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcdb48 VA: 0x75945e5b48
	public Void .ctor() { }
}
```
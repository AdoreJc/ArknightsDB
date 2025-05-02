# AutochessFilterByChessLevel

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `CompareType _condType`

- `Int32 _levelToCompare`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutochessFilterByChessLevel : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private CompareType _condType; // 0x14
	private Int32 _levelToCompare; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee4448 VA: 0x75944fc448
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee44b0 VA: 0x75944fc4b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee4734 VA: 0x75944fc734
	public Void .ctor() { }
}
```
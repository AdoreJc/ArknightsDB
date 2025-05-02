# AutoChessCheckCharacterByDefaultFaction

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessCheckCharacterByDefaultFaction : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee35dc VA: 0x75944fb5dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee3644 VA: 0x75944fb644
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee3820 VA: 0x75944fb820
	public Void .ctor() { }
}
```
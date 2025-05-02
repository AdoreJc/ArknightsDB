# RegisterMagicCircuitRoute

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RegisterMagicCircuitRoute : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6cf70 VA: 0x7594584f70
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6cfd8 VA: 0x7594584fd8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6d15c VA: 0x759458515c
	public Void .ctor() { }
}
```
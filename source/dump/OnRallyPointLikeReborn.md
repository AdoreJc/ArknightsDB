# OnRallyPointLikeReborn

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class OnRallyPointLikeReborn : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc3ffc VA: 0x75945dbffc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc4064 VA: 0x75945dc064
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc4250 VA: 0x75945dc250
	public Void .ctor() { }
}
```
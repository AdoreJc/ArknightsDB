# NecromancerAssignTargetTileToSelector

**Namespace:** ` `


## Fields

- `ActionTargetType _tileTargetType`

- `ActionTargetType _selectorOwnerType`

- `String _abilityName`

- `Boolean _useFirstActiveAbility`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NecromancerAssignTargetTileToSelector : ActionNode
{
	private ActionTargetType _tileTargetType; // 0x10
	private ActionTargetType _selectorOwnerType; // 0x14
	private String _abilityName; // 0x18
	private Boolean _useFirstActiveAbility; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8fe70 VA: 0x75945a7e70
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8fed8 VA: 0x75945a7ed8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f90170 VA: 0x75945a8170
	public Void .ctor() { }
}
```
# SetCharacterDontOccupyDeployCntFlag

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isUnset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetCharacterDontOccupyDeployCntFlag : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isUnset; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc42c0 VA: 0x75945dc2c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc4328 VA: 0x75945dc328
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc44a4 VA: 0x75945dc4a4
	public Void .ctor() { }
}
```
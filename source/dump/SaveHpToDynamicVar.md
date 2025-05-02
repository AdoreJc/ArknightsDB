# SaveHpToDynamicVar

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `SaveType _saveType`

- `String _buffNameOfBlackboard`

- `Boolean _alwaysAssign`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SaveHpToDynamicVar : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private SaveType _saveType; // 0x14
	private String _buffNameOfBlackboard; // 0x18
	private Boolean _alwaysAssign; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcf988 VA: 0x75945e7988
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcf9f0 VA: 0x75945e79f0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcfc50 VA: 0x75945e7c50
	public Void .ctor() { }
}
```
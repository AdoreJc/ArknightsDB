# ModifyAttackBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _modeIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyAttackBlackboard : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _modeIndex; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fced54 VA: 0x75945e6d54
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcedbc VA: 0x75945e6dbc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcef6c VA: 0x75945e6f6c
	public Void .ctor() { }
}
```
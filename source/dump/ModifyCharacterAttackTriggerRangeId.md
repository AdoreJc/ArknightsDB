# ModifyCharacterAttackTriggerRangeId

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ActionTargetType _source`

- `Boolean _useSpecifiedModeRangeId`

- `Int32 _sourceMode`

- `Boolean _useCurrentModeRangeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyCharacterAttackTriggerRangeId : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ActionTargetType _source; // 0x14
	private Boolean _useSpecifiedModeRangeId; // 0x18
	private Int32 _sourceMode; // 0x1c
	private Int32[] _modes; // 0x20
	private Boolean _useCurrentModeRangeId; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc5c44 VA: 0x75945ddc44
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc5cac VA: 0x75945ddcac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc5f38 VA: 0x75945ddf38
	public Void .ctor() { }
}
```
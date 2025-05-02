# SwitchSkillRangeIdModeIndex

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _mode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchSkillRangeIdModeIndex : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _mode; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8eeec VA: 0x75945a6eec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8ef54 VA: 0x75945a6f54
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8f10c VA: 0x75945a710c
	public Void .ctor() { }
}
```
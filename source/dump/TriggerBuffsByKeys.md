# TriggerBuffsByKeys

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _excludeThisBuff`

- `Boolean _forceTrigger`

- `Boolean _triggerAllBuffs`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerBuffsByKeys : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _excludeThisBuff; // 0x14
	private String[] _buffKeys; // 0x18
	private Boolean _forceTrigger; // 0x20
	private Boolean _triggerAllBuffs; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eff5ec VA: 0x75945175ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eff654 VA: 0x7594517654
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eff7fc VA: 0x75945177fc
	public Void .ctor() { }
}
```
# TriggerHostsBuffsByKeys

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerHostsBuffsByKeys : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String[] _buffKeys; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eff874 VA: 0x7594517874
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eff8dc VA: 0x75945178dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1effac8 VA: 0x7594517ac8
	public Void .ctor() { }
}
```
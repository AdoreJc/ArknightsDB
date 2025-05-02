# TriggerEnvSystem

**Namespace:** ` `


## Fields

- `String _envKey`

- `ActionTargetType _target`

- `Boolean _triggerWithEvent`

- `String _eventName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerEnvSystem : ActionNode
{
	private String _envKey; // 0x10
	private ActionTargetType _target; // 0x18
	private Boolean _triggerWithEvent; // 0x1c
	private String _eventName; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd0830 VA: 0x75945e8830
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd0898 VA: 0x75945e8898
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd0a84 VA: 0x75945e8a84
	public Void .ctor() { }
}
```
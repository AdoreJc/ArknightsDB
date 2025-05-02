# Mainline14TriggerSkill

**Namespace:** ` `


## Fields

- `String _evnSysKey`

- `Boolean _isTriggeredByBoss`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Mainline14TriggerSkill : ActionNode
{
	private String _evnSysKey; // 0x10
	private Boolean _isTriggeredByBoss; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd2f9c VA: 0x75945eaf9c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd3004 VA: 0x75945eb004
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd3198 VA: 0x75945eb198
	public Void .ctor() { }
}
```
# DynamicChangeUnitShadow

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _enableShadow`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DynamicChangeUnitShadow : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _enableShadow; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd5eec VA: 0x75945edeec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd5f54 VA: 0x75945edf54
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd60c8 VA: 0x75945ee0c8
	public Void .ctor() { }
}
```
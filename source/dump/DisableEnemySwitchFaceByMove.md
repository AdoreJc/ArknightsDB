# DisableEnemySwitchFaceByMove

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _disabled`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DisableEnemySwitchFaceByMove : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _disabled; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd3d6c VA: 0x75945ebd6c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd3dd4 VA: 0x75945ebdd4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd3f48 VA: 0x75945ebf48
	public Void .ctor() { }
}
```
# ModifyEnemySpUIFlag

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isShow`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyEnemySpUIFlag : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isShow; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd5850 VA: 0x75945ed850
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd58b8 VA: 0x75945ed8b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd5a2c VA: 0x75945eda2c
	public Void .ctor() { }
}
```
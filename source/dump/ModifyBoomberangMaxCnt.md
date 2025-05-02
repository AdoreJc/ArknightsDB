# ModifyBoomberangMaxCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _reset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyBoomberangMaxCnt : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _reset; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd54f8 VA: 0x75945ed4f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd5560 VA: 0x75945ed560
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd57d8 VA: 0x75945ed7d8
	public Void .ctor() { }
}
```
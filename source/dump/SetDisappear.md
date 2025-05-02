# SetDisappear

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isDisappear`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetDisappear : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isDisappear; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd1b54 VA: 0x75945e9b54
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd1bbc VA: 0x75945e9bbc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd1d30 VA: 0x75945e9d30
	public Void .ctor() { }
}
```
# ReturnDeployCost

**Namespace:** ` `


## Fields

- `Boolean _forceToDisplayNumber`

- `Boolean _forceToDisplayNegativeNumber`

- `String _blackboardKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ReturnDeployCost : ActionNode
{
	private Boolean _forceToDisplayNumber; // 0x10
	private Boolean _forceToDisplayNegativeNumber; // 0x11
	private String _blackboardKey; // 0x18
	private ActionTargetType _targetType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd1da8 VA: 0x75945e9da8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd1e10 VA: 0x75945e9e10
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd202c VA: 0x75945ea02c
	public Void .ctor() { }
}
```
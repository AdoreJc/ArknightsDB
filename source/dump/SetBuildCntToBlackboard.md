# SetBuildCntToBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `Boolean _force`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetBuildCntToBlackboard : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private Boolean _force; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcdc10 VA: 0x75945e5c10
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcdc78 VA: 0x75945e5c78
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcde3c VA: 0x75945e5e3c
	public Void .ctor() { }
}
```
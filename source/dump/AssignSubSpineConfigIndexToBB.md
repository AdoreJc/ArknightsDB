# AssignSubSpineConfigIndexToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _indexKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignSubSpineConfigIndexToBB : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _indexKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd8638 VA: 0x75945f0638
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd86a0 VA: 0x75945f06a0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd88b4 VA: 0x75945f08b4
	public Void .ctor() { }
}
```
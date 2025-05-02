# AddFearTargetTiles

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Single _rangeRadius`

- `Single _maxDegree`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddFearTargetTiles : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Single _rangeRadius; // 0x18
	private Single _maxDegree; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd70f8 VA: 0x75945ef0f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd7160 VA: 0x75945ef160
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd76d4 VA: 0x75945ef6d4
	public Void .ctor() { }
}
```
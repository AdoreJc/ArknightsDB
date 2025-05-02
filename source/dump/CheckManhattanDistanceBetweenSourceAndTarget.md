# CheckManhattanDistanceBetweenSourceAndTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Int32 _minDist`

- `Int32 _maxDist`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckManhattanDistanceBetweenSourceAndTarget : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Int32 _minDist; // 0x18
	private Int32 _maxDist; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1875c VA: 0x759453075c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f187c4 VA: 0x75945307c4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f189dc VA: 0x75945309dc
	public Void .ctor() { }
}
```
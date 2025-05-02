# AssignHpRatioToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignHpRatioToBB : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef42d8 VA: 0x759450c2d8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef4340 VA: 0x759450c340
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef449c VA: 0x759450c49c
	public Void .ctor() { }
}
```
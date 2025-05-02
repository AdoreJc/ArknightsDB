# LegionModeOnlyFilterByProfessionBuffMaxCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _valueToCompare`

- `String _valueToCompareKey`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyFilterByProfessionBuffMaxCnt : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _valueToCompare; // 0x14
	private String _valueToCompareKey; // 0x18
	private CompareType _condType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f674f0 VA: 0x759457f4f0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f67558 VA: 0x759457f558
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f67818 VA: 0x759457f818
	public Void .ctor() { }
}
```
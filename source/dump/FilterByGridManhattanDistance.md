# FilterByGridManhattanDistance

**Namespace:** ` `


## Fields

- `String _firstGridRowKey`

- `String _firstGridColKey`

- `String _secondGridRowKey`

- `String _secondGridColKey`

- `CompareType _condType`

- `String _compareValueKey`

- `Int32 _compareValue`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByGridManhattanDistance : ActionNode
{
	private String _firstGridRowKey; // 0x10
	private String _firstGridColKey; // 0x18
	private String _secondGridRowKey; // 0x20
	private String _secondGridColKey; // 0x28
	private CompareType _condType; // 0x30
	private String _compareValueKey; // 0x38
	private Int32 _compareValue; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f94518 VA: 0x75945ac518
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f94580 VA: 0x75945ac580
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f947e8 VA: 0x75945ac7e8
	public Void .ctor() { }
}
```
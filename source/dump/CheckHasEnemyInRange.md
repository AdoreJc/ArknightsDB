# CheckHasEnemyInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _soureceType`

- `String _rangeId`

- `Boolean _needCheckCount`

- `Boolean _assignToBB`

- `String _assignBBKey`

- `CompareType _condType`

- `String _countKey`

- `Boolean _checkRadius`

- `Single _rangeRadius`

- `Boolean _excludeSource`

- `Boolean _checkId`


## Properties

- `Boolean needCheckCount`

- `Boolean assignToBB`


## Methods

- `Boolean get_needCheckCount()`

- `Boolean get_assignToBB()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckHasEnemyInRange : ActionNode
{
	private ActionTargetType _soureceType; // 0x10
	private String _rangeId; // 0x18
	private Boolean _needCheckCount; // 0x20
	private Boolean _assignToBB; // 0x21
	private String _assignBBKey; // 0x28
	private CompareType _condType; // 0x30
	private String _countKey; // 0x38
	private Boolean _checkRadius; // 0x40
	private Single _rangeRadius; // 0x44
	private Boolean _excludeSource; // 0x48
	private Boolean _checkId; // 0x49
	private List`1 _includedBuffIds; // 0x50
	private List`1 _excludedBuffIds; // 0x58
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_needCheckCount; // 0x8
	private static DelegateBridge __Hotfix0_get_assignToBB; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public Boolean needCheckCount { get; }
	public Boolean assignToBB { get; }

	// RVA: 0x1f1b7e8 VA: 0x75945337e8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1b850 VA: 0x7594533850
	public Boolean get_needCheckCount() { }
	// RVA: 0x1f1b8b8 VA: 0x75945338b8
	public Boolean get_assignToBB() { }
	// RVA: 0x1f1b920 VA: 0x7594533920
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1c524 VA: 0x7594534524
	public Void .ctor() { }
}
```
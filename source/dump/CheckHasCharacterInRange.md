# CheckHasCharacterInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _rangeId`

- `Boolean _checkRadius`

- `Single _rangeRadius`

- `Boolean _globalRange`

- `Boolean _filterByGroupId`

- `String _filterGroupId`

- `Boolean _excludeTarget`

- `Boolean _excludeTrapAndToken`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckHasCharacterInRange : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _rangeId; // 0x18
	private Boolean _checkRadius; // 0x20
	private Single _rangeRadius; // 0x24
	private Boolean _globalRange; // 0x28
	private Boolean _filterByGroupId; // 0x29
	private String _filterGroupId; // 0x30
	private Boolean _excludeTarget; // 0x38
	private Boolean _excludeTrapAndToken; // 0x39
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2b0c0 VA: 0x75945430c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2b128 VA: 0x7594543128
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2b74c VA: 0x759454374c
	public Void .ctor() { }
}
```
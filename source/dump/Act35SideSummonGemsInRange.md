# Act35SideSummonGemsInRange

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`

- `Boolean _useInProjectile`

- `GemsType _gemsType`

- `String _rangeId`

- `Direction direction`

- `Boolean _isCircleRange`

- `Single _rangeRadius`


## Properties

- `Boolean isCircleRange`


## Methods

- `Boolean get_isCircleRange()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act35SideSummonGemsInRange : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private Boolean _useInProjectile; // 0x1c
	private GemsType _gemsType; // 0x20
	private String _rangeId; // 0x28
	private Direction direction; // 0x30
	private Boolean _isCircleRange; // 0x34
	private Single _rangeRadius; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_isCircleRange; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public Boolean isCircleRange { get; }

	// RVA: 0x1ee03fc VA: 0x75944f83fc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee0464 VA: 0x75944f8464
	public Boolean get_isCircleRange() { }
	// RVA: 0x1ee04cc VA: 0x75944f84cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee0900 VA: 0x75944f8900
	public Void .ctor() { }
}
```
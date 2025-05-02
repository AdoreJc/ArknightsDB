# MarkFogView

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `Boolean _globalRange`

- `String _rangeId`

- `ActionTargetType _targetType`

- `Boolean _markInView`

- `Boolean _markOldTilePos`


## Properties

- `Boolean useRangeId`


## Methods

- `Boolean get_useRangeId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MarkFogView : ActionNode
{
	private String _envSystemKey; // 0x10
	private Boolean _globalRange; // 0x18
	private String _rangeId; // 0x20
	private ActionTargetType _targetType; // 0x28
	private Boolean _markInView; // 0x2c
	private Boolean _markOldTilePos; // 0x2d
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_useRangeId; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	protected Boolean useRangeId { get; }

	// RVA: 0x1fd3fc0 VA: 0x75945ebfc0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd4028 VA: 0x75945ec028
	protected Boolean get_useRangeId() { }
	// RVA: 0x1fd4098 VA: 0x75945ec098
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd4368 VA: 0x75945ec368
	public Void .ctor() { }
}
```
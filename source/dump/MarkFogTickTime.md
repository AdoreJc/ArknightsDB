# MarkFogTickTime

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `Boolean _useRangeId`

- `Boolean _useSourceRootTile`

- `String _rangeId`

- `ActionTargetType _sourceType`

- `String _abilityName`


## Properties

- `Boolean useRangeId`


## Methods

- `Boolean get_useRangeId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MarkFogTickTime : ActionNode
{
	private String _envSystemKey; // 0x10
	private Boolean _useRangeId; // 0x18
	private Boolean _useSourceRootTile; // 0x19
	private String _rangeId; // 0x20
	private ActionTargetType _sourceType; // 0x28
	private String _abilityName; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_useRangeId; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	protected Boolean useRangeId { get; }

	// RVA: 0x1fd43e0 VA: 0x75945ec3e0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd4448 VA: 0x75945ec448
	protected Boolean get_useRangeId() { }
	// RVA: 0x1fd44b0 VA: 0x75945ec4b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd4944 VA: 0x75945ec944
	public Void .ctor() { }
}
```
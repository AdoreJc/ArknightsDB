# InsertCheckPointInRuntimeRoute

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `Boolean _clearRouteBeforeInsert`

- `CheckpointType _type`

- `Boolean _randomizeReachOffset`

- `Vector2 _reachOffset`

- `Single _time`

- `Boolean _addIntoRuntimeRoute`

- `Boolean _toMapPosition`

- `Boolean _checkReachable`

- `Boolean _manuallySpecifyInsertIndex`

- `Int32 _insertIndex`

- `Boolean _manuallySpecifyReassignIndex`

- `Int32 _reassignIndex`


## Properties

- `Boolean checkpointEqualsMove`

- `Boolean checkpointEqualsWait`

- `Boolean toSourcePosition`


## Methods

- `Boolean get_checkpointEqualsMove()`

- `Boolean get_checkpointEqualsWait()`

- `Boolean get_toSourcePosition()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InsertCheckPointInRuntimeRoute : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private Boolean _clearRouteBeforeInsert; // 0x18
	private CheckpointType _type; // 0x1c
	private Boolean _randomizeReachOffset; // 0x20
	private Vector2 _reachOffset; // 0x24
	private Single _time; // 0x2c
	private Boolean _addIntoRuntimeRoute; // 0x30
	private Boolean _toMapPosition; // 0x31
	private Boolean _checkReachable; // 0x32
	private Boolean _manuallySpecifyInsertIndex; // 0x33
	private Int32 _insertIndex; // 0x34
	private Boolean _manuallySpecifyReassignIndex; // 0x38
	private Int32 _reassignIndex; // 0x3c
	private static DelegateBridge __Hotfix0_get_checkpointEqualsMove; // 0x0
	private static DelegateBridge __Hotfix0_get_checkpointEqualsWait; // 0x8
	private static DelegateBridge __Hotfix0_get_toSourcePosition; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x18
	private static DelegateBridge __Hotfix0_Execute; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected Boolean checkpointEqualsMove { get; }
	protected Boolean checkpointEqualsWait { get; }
	protected Boolean toSourcePosition { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fc1ee0 VA: 0x75945d9ee0
	protected Boolean get_checkpointEqualsMove() { }
	// RVA: 0x1fc1f50 VA: 0x75945d9f50
	protected Boolean get_checkpointEqualsWait() { }
	// RVA: 0x1fc1fc0 VA: 0x75945d9fc0
	protected Boolean get_toSourcePosition() { }
	// RVA: 0x1fc2030 VA: 0x75945da030
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc2098 VA: 0x75945da098
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc2720 VA: 0x75945da720
	public Void .ctor() { }
}
```
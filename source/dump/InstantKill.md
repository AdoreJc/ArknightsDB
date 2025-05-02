# InstantKill

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _killSource`

- `Boolean _noSource`

- `Boolean _withdrawIfRallyPoint`

- `Boolean _resultIfInRallyPointMode`

- `Boolean _skipReborn`

- `Boolean _noReason`

- `Boolean _markReachExit`

- `Boolean _switchState`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InstantKill : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _killSource; // 0x14
	private Boolean _noSource; // 0x15
	private Boolean _withdrawIfRallyPoint; // 0x16
	private Boolean _resultIfInRallyPointMode; // 0x17
	private Boolean _skipReborn; // 0x18
	private Boolean _noReason; // 0x19
	private Boolean _markReachExit; // 0x1a
	private Boolean _switchState; // 0x1b
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f42f6c VA: 0x759455af6c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f42fd4 VA: 0x759455afd4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f43244 VA: 0x759455b244
	public Void .ctor() { }
}
```
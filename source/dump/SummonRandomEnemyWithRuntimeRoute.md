# SummonRandomEnemyWithRuntimeRoute

**Namespace:** ` `


## Fields

- `Boolean _noSource`

- `ActionTargetType _source`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _waitTime`

- `Single _offset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonRandomEnemyWithRuntimeRoute : ActionNode
{
	private String[] _randomEnemys; // 0x10
	private Boolean _noSource; // 0x18
	private ActionTargetType _source; // 0x1c
	private MotionMode _motionMode; // 0x20
	private Boolean _unharmful; // 0x24
	private Boolean _alwaysCountAsKilled; // 0x25
	private Single _waitTime; // 0x28
	private Single _offset; // 0x2c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fddaac VA: 0x75945f5aac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fddb14 VA: 0x75945f5b14
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdde20 VA: 0x75945f5e20
	public Void .ctor() { }
}
```
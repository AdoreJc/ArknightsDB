# TrapGarageSummonEnemy

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `String _enemyKey`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _endPosOffsetAlongDirection`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TrapGarageSummonEnemy : ActionNode
{
	private ActionTargetType _source; // 0x10
	private String _enemyKey; // 0x18
	private MotionMode _motionMode; // 0x20
	private Boolean _unharmful; // 0x24
	private Boolean _alwaysCountAsKilled; // 0x25
	private Single _endPosOffsetAlongDirection; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f56ed4 VA: 0x759456eed4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f56f3c VA: 0x759456ef3c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f573b4 VA: 0x759456f3b4
	public Void .ctor() { }
}
```
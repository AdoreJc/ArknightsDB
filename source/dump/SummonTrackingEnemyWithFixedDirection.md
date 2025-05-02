# SummonTrackingEnemyWithFixedDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `Int32 _summonCount`

- `Int32 _waveNum`

- `String _enemyKey`

- `Single _delayTime`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _spawnOffset`

- `Single _startAngle`

- `Single _endAngle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonTrackingEnemyWithFixedDirection : ActionNode
{
	private ActionTargetType _source; // 0x10
	private Int32 _summonCount; // 0x14
	private Int32 _waveNum; // 0x18
	private String _enemyKey; // 0x20
	private Single _delayTime; // 0x28
	private MotionMode _motionMode; // 0x2c
	private Boolean _unharmful; // 0x30
	private Boolean _alwaysCountAsKilled; // 0x31
	private Single _spawnOffset; // 0x34
	private Single _startAngle; // 0x38
	private Single _endAngle; // 0x3c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fded74 VA: 0x75945f6d74
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fdeddc VA: 0x75945f6ddc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdf0c8 VA: 0x75945f70c8
	public Void .ctor() { }
}
```
# TrapRockflSummonLtrock

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `String _enemyKey`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _midPosOffsetAlongDirection`

- `Single _endPosOffsetAlongDirection`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TrapRockflSummonLtrock : ActionNode
{
	private ActionTargetType _source; // 0x10
	private String _enemyKey; // 0x18
	private MotionMode _motionMode; // 0x20
	private Boolean _unharmful; // 0x24
	private Boolean _alwaysCountAsKilled; // 0x25
	private Single _midPosOffsetAlongDirection; // 0x28
	private Single _endPosOffsetAlongDirection; // 0x2c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f57434 VA: 0x759456f434
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5749c VA: 0x759456f49c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f57a24 VA: 0x759456fa24
	public Void .ctor() { }
}
```
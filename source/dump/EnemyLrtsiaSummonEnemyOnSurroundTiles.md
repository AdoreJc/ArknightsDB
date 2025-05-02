# EnemyLrtsiaSummonEnemyOnSurroundTiles

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `Boolean _useSpecialHost`

- `ActionTargetType _host`

- `String _enemyKey`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _waitTime`

- `Boolean _checkTileBBBeforeSummon`

- `String _blackboardKey`

- `Single _valueToCompare`

- `CompareType _condType`

- `Boolean _assignTileBBAfterSummon`

- `Single _valueToAssign`

- `Boolean _checkCharIdBeforeSummon`


## Properties

- `Boolean useSpecialHost`


## Methods

- `Boolean get_useSpecialHost()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyLrtsiaSummonEnemyOnSurroundTiles : ActionNode
{
	private ActionTargetType _source; // 0x10
	private Boolean _useSpecialHost; // 0x14
	private ActionTargetType _host; // 0x18
	private String _enemyKey; // 0x20
	private MotionMode _motionMode; // 0x28
	private Boolean _unharmful; // 0x2c
	private Boolean _alwaysCountAsKilled; // 0x2d
	private Single _waitTime; // 0x30
	private Boolean _checkTileBBBeforeSummon; // 0x34
	private String _blackboardKey; // 0x38
	private Single _valueToCompare; // 0x40
	private CompareType _condType; // 0x44
	private Boolean _assignTileBBAfterSummon; // 0x48
	private Single _valueToAssign; // 0x4c
	private Boolean _checkCharIdBeforeSummon; // 0x50
	private String[] _forbiddenIds; // 0x58
	private static DelegateBridge __Hotfix0_get_useSpecialHost; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean useSpecialHost { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fddea0 VA: 0x75945f5ea0
	public Boolean get_useSpecialHost() { }
	// RVA: 0x1fddf08 VA: 0x75945f5f08
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fddf70 VA: 0x75945f5f70
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fde5ec VA: 0x75945f65ec
	public Void .ctor() { }
}
```
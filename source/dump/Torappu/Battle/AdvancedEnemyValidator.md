# AdvancedEnemyValidator

**Namespace:** `Torappu.Battle`


## Fields

- `EnemyLevelMask _enemyLevelMask`

- `MotionMask _motionMask`

- `Boolean _allowNoneApplyWay`

- `SourceApplyWay _applyWay`

- `Boolean _checkIsBlockedByOwner`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedEnemyValidator : TargetValidator
{
	private EnemyLevelMask _enemyLevelMask; // 0x8c
	private MotionMask _motionMask; // 0x90
	private Boolean _allowNoneApplyWay; // 0x94
	private SourceApplyWay _applyWay; // 0x98
	private Boolean _checkIsBlockedByOwner; // 0x9c


	// RVA: 0x1bda43c VA: 0x75941f243c
	public override Boolean Validate(Entity target) { }
	// RVA: 0x1bda69c VA: 0x75941f269c
	public Void .ctor() { }
}
```
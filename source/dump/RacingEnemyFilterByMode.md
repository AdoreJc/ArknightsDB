# RacingEnemyFilterByMode

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `RacingMode _racingMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RacingEnemyFilterByMode : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private RacingMode _racingMode; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7ab0c VA: 0x7594592b0c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7ab74 VA: 0x7594592b74
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7ad1c VA: 0x7594592d1c
	public Void .ctor() { }
}
```
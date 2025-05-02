# SwitchRacingMode

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `RacingMode _racingMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchRacingMode : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private RacingMode _racingMode; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7a2d0 VA: 0x75945922d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7a338 VA: 0x7594592338
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7a4dc VA: 0x75945924dc
	public Void .ctor() { }
}
```
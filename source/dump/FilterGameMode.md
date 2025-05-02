# FilterGameMode

**Namespace:** ` `


## Fields

- `GameModeType _gameModeType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterGameMode : ActionNode
{
	private GameModeType _gameModeType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6235c VA: 0x759457a35c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f623c4 VA: 0x759457a3c4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f62508 VA: 0x759457a508
	public Void .ctor() { }
}
```
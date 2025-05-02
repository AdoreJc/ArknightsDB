# ForceSetBattleSpeedLevel

**Namespace:** ` `


## Fields

- `SpeedLevel _speedLevel`

- `Boolean _setPause`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ForceSetBattleSpeedLevel : ActionNode
{
	private SpeedLevel _speedLevel; // 0x10
	private Boolean _setPause; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fda468 VA: 0x75945f2468
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fda4d0 VA: 0x75945f24d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fda5b4 VA: 0x75945f25b4
	public Void .ctor() { }
}
```
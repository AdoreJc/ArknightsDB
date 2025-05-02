# GameCityTriggerEnvSystem

**Namespace:** ` `


## Fields

- `String _envKey`

- `UIScoreType _uiType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GameCityTriggerEnvSystem : ActionNode
{
	private String _envKey; // 0x10
	private UIScoreType _uiType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f55078 VA: 0x759456d078
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f550e0 VA: 0x759456d0e0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f552f4 VA: 0x759456d2f4
	public Void .ctor() { }
}
```
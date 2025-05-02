# ReleaseEnemyFromCurrentWave

**Namespace:** ` `


## Fields

- `Boolean _trackEnemyAtNextWave`

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ReleaseEnemyFromCurrentWave : ActionNode
{
	private Boolean _trackEnemyAtNextWave; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f96618 VA: 0x75945ae618
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f96680 VA: 0x75945ae680
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f96874 VA: 0x75945ae874
	public Void .ctor() { }
}
```
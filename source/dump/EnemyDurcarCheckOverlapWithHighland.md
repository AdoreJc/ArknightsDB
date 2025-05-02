# EnemyDurcarCheckOverlapWithHighland

**Namespace:** ` `


## Fields

- `Boolean _ignoreCheckSomeTiles`

- `AdvancedBuildableMask _ignoredAdvancedBuildMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyDurcarCheckOverlapWithHighland : ActionNode
{
	private Boolean _ignoreCheckSomeTiles; // 0x10
	private AdvancedBuildableMask _ignoredAdvancedBuildMask; // 0x14
	private const Single CHECK_RADIUS; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f57aa8 VA: 0x759456faa8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f57b10 VA: 0x759456fb10
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f57f90 VA: 0x759456ff90
	public Void .ctor() { }
}
```
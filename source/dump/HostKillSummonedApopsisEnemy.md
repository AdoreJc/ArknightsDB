# HostKillSummonedApopsisEnemy

**Namespace:** ` `


## Fields

- `ActionTargetType _source`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HostKillSummonedApopsisEnemy : ActionNode
{
	private ActionTargetType _source; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7ffd4 VA: 0x7594597fd4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8003c VA: 0x759459803c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f802c4 VA: 0x75945982c4
	public Void .ctor() { }
}
```
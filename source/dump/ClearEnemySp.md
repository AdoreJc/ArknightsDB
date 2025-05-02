# ClearEnemySp

**Namespace:** ` `


## Fields

- `ActionTargetType _enemy`


## Methods

- `Boolean _ReduceSpToZero(Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ClearEnemySp : ActionNode
{
	private ActionTargetType _enemy; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__ReduceSpToZero; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcfcc8 VA: 0x75945e7cc8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcfd30 VA: 0x75945e7d30
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcfeb8 VA: 0x75945e7eb8
	private Boolean _ReduceSpToZero(Enemy enemy) { }
	// RVA: 0x1fcfffc VA: 0x75945e7ffc
	public Void .ctor() { }
}
```
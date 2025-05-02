# CreateBuffToUnitInCurrentMapLayer

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `TargetOptions _targetOptions`

- `BuffData _buff`


## Methods

- `Void _AddBuff(Entity, Unit, ref, Blackboard)`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToUnitInCurrentMapLayer : ActionNode, IBuffSource
{
	private ActionTargetType _source; // 0x10
	private TargetOptions _targetOptions; // 0x18
	private BuffData _buff; // 0x78
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__AddBuff; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1f00c68 VA: 0x7594518c68
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f00cd0 VA: 0x7594518cd0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f01098 VA: 0x7594519098
	private Void _AddBuff(Entity source, Unit target, ref Snapshot snapshot, Blackboard blackboard) { }
	// RVA: 0x1f0122c VA: 0x759451922c
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f01334 VA: 0x7594519334
	public Void .ctor() { }
}
```
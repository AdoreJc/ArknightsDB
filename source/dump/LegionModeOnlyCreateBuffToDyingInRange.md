# LegionModeOnlyCreateBuffToDyingInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `TargetOptions _targetOptions`

- `Int32 _maxNum`

- `BuffData _buffData`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyCreateBuffToDyingInRange : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private TargetOptions _targetOptions; // 0x18
	private Int32 _maxNum; // 0x78
	private BuffData _buffData; // 0x80
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f65750 VA: 0x759457d750
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f657b8 VA: 0x759457d7b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f65e74 VA: 0x759457de74
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f65f7c VA: 0x759457df7c
	public Void .ctor() { }
}
```
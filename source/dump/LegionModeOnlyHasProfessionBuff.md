# LegionModeOnlyHasProfessionBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _checkIsMaxLevel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyHasProfessionBuff : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _checkIsMaxLevel; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f671f0 VA: 0x759457f1f0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f67258 VA: 0x759457f258
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f67478 VA: 0x759457f478
	public Void .ctor() { }
}
```
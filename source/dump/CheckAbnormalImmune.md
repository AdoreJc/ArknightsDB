# CheckAbnormalImmune

**Namespace:** ` `


## Fields

- `AbnormalFlag _abnormalFlag`

- `ActionTargetType _targetType`

- `Boolean _isUnset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckAbnormalImmune : ActionNode
{
	private AbnormalFlag _abnormalFlag; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Boolean _isUnset; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f19418 VA: 0x7594531418
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f19480 VA: 0x7594531480
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f195c8 VA: 0x75945315c8
	public Void .ctor() { }
}
```
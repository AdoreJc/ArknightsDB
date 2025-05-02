# CheckBlockeeAbnormalFlags

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBlockeeAbnormalFlags : ActionNode
{
	private List`1 _abnormalFlags; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f32c00 VA: 0x759454ac00
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f32c68 VA: 0x759454ac68
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f333d8 VA: 0x759454b3d8
	public Void .ctor() { }
}
```
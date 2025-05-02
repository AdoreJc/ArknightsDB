# FinishAllBuffsWithCertainAbnormalFlag

**Namespace:** ` `


## Fields

- `AbnormalFlag _abnormalFlag`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishAllBuffsWithCertainAbnormalFlag : ActionNode
{
	private AbnormalFlag _abnormalFlag; // 0x10
	private ActionTargetType _targetType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0343c VA: 0x759451b43c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f034a4 VA: 0x759451b4a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f035d4 VA: 0x759451b5d4
	public Void .ctor() { }
}
```
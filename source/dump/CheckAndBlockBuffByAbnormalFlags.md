# CheckAndBlockBuffByAbnormalFlags

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckAndBlockBuffByAbnormalFlags : ActionNode
{
	private List`1 _abnormalFlags; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f11a74 VA: 0x7594529a74
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f11adc VA: 0x7594529adc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f11cd0 VA: 0x7594529cd0
	public Void .ctor() { }
}
```
# FilterAbilityValidCastTargetCnt

**Namespace:** ` `


## Fields

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterAbilityValidCastTargetCnt : ActionNode
{
	private CompareType _condType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f567f4 VA: 0x759456e7f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5685c VA: 0x759456e85c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f56b78 VA: 0x759456eb78
	public Void .ctor() { }
}
```
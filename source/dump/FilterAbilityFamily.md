# FilterAbilityFamily

**Namespace:** ` `


## Fields

- `FamilyGroupMask _familyGroupMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterAbilityFamily : ActionNode
{
	private FamilyGroupMask _familyGroupMask; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f161d4 VA: 0x759452e1d4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1623c VA: 0x759452e23c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f16340 VA: 0x759452e340
	public Void .ctor() { }
}
```
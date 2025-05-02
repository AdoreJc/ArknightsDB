# IfTargetSide

**Namespace:** ` `


## Fields

- `SideType _sideMask`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IfTargetSide : ActionNode
{
	private SideType _sideMask; // 0x10
	private ActionTargetType _targetType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f15308 VA: 0x759452d308
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f15370 VA: 0x759452d370
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1549c VA: 0x759452d49c
	public Void .ctor() { }
}
```
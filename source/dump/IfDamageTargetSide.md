# IfDamageTargetSide

**Namespace:** ` `


## Fields

- `SideType _sideMask`

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IfDamageTargetSide : ActionNode
{
	private SideType _sideMask; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f150a8 VA: 0x759452d0a8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f15110 VA: 0x759452d110
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f15284 VA: 0x759452d284
	public Void .ctor() { }
}
```
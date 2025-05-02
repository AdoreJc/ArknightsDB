# IsTargetInEPBreakRecovery

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _checkRecoveryType`

- `ElementType _elementType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IsTargetInEPBreakRecovery : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _checkRecoveryType; // 0x14
	private ElementType _elementType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f31450 VA: 0x7594549450
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f314b8 VA: 0x75945494b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f31614 VA: 0x7594549614
	public Void .ctor() { }
}
```
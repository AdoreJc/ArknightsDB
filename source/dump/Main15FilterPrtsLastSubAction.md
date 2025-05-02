# Main15FilterPrtsLastSubAction

**Namespace:** ` `


## Fields

- `PrtsSubActionType _actionType`

- `Boolean _filterActionInstead`

- `PrtsActionType _mainActionType`


## Properties

- `Boolean filterSubAction`


## Methods

- `Boolean get_filterSubAction()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Main15FilterPrtsLastSubAction : ActionNode
{
	private PrtsSubActionType _actionType; // 0x10
	private Boolean _filterActionInstead; // 0x14
	private PrtsActionType _mainActionType; // 0x18
	private static DelegateBridge __Hotfix0_get_filterSubAction; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Boolean filterSubAction { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f70784 VA: 0x7594588784
	protected Boolean get_filterSubAction() { }
	// RVA: 0x1f707f4 VA: 0x75945887f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7085c VA: 0x759458885c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f70a3c VA: 0x7594588a3c
	public Void .ctor() { }
}
```
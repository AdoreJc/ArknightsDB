# ModifyMaxCost

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _isMinus`

- `Boolean _ensureCurCostNotExceedMax`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyMaxCost : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _isMinus; // 0x14
	private Boolean _ensureCurCostNotExceedMax; // 0x15
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0c624 VA: 0x7594524624
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0c68c VA: 0x759452468c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0c844 VA: 0x7594524844
	public Void .ctor() { }
}
```
# ModifySpData

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _spCostString`

- `Boolean _onlyUpdateSpCost`

- `Boolean _updateSkillSpCostMin`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifySpData : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _spCostString; // 0x18
	private Boolean _onlyUpdateSpCost; // 0x20
	private Boolean _updateSkillSpCostMin; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0d6f4 VA: 0x75945256f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0d75c VA: 0x759452575c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0da54 VA: 0x7594525a54
	public Void .ctor() { }
}
```
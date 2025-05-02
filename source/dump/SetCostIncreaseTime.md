# SetCostIncreaseTime

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _blackboardKey`

- `Single _costIncreaseTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetCostIncreaseTime : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _blackboardKey; // 0x18
	private Single _costIncreaseTime; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0c350 VA: 0x7594524350
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0c3b8 VA: 0x75945243b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0c574 VA: 0x7594524574
	public Void .ctor() { }
}
```
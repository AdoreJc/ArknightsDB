# CreateBuffToCurTarget

**Namespace:** ` `


## Fields

- `BuffData _buff`

- `ActionTargetType _buffSource`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToCurTarget : ActionNode, IBuffSource, ICreateBuffNode
{
	private BuffData _buff; // 0x10
	private ActionTargetType _buffSource; // 0x18
	private Boolean _isDerivedBuff; // 0x1c
	private Boolean _finishDerivedBuffIfParentFinish; // 0x1d
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1efde48 VA: 0x7594515e48
	public override SourceType get_allowedSource() { }
	// RVA: 0x1efdeb0 VA: 0x7594515eb0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1efe3a0 VA: 0x75945163a0
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1efe494 VA: 0x7594516494
	public Void .ctor() { }
}
```
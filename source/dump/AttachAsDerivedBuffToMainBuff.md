# AttachAsDerivedBuffToMainBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `Boolean _finishDerivedBuffIfParentFinish`

- `BuffData _buff`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AttachAsDerivedBuffToMainBuff : ActionNode, IBuffSource, ICreateBuffNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private Boolean _finishDerivedBuffIfParentFinish; // 0x18
	private BuffData _buff; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f041f8 VA: 0x759451c1f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f04260 VA: 0x759451c260
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f04454 VA: 0x759451c454
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f04548 VA: 0x759451c548
	public Void .ctor() { }
}
```
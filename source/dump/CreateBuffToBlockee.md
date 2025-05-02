# CreateBuffToBlockee

**Namespace:** ` `


## Fields

- `BuffData _buff`

- `ActionTargetType _buffOwner`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToBlockee : ActionNode, IBuffSource, ICreateBuffNode
{
	private BuffData _buff; // 0x10
	private ActionTargetType _buffOwner; // 0x18
	private Boolean _isDerivedBuff; // 0x1c
	private Boolean _finishDerivedBuffIfParentFinish; // 0x1d
	private List`1 m_entities; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1efd410 VA: 0x7594515410
	public override SourceType get_allowedSource() { }
	// RVA: 0x1efd478 VA: 0x7594515478
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1efdc3c VA: 0x7594515c3c
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1efdd30 VA: 0x7594515d30
	public Void .ctor() { }
}
```
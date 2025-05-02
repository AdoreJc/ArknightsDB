# CreateBuffs

**Namespace:** ` `


## Fields

- `BuffPair _buffPair`

- `ActionTargetType _buffOwner`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffs : ActionNode, IBuffSource
{
	private BuffPair _buffPair; // 0x10
	private ActionTargetType _buffOwner; // 0x18
	private Boolean _isDerivedBuff; // 0x1c
	private Boolean _finishDerivedBuffIfParentFinish; // 0x1d
	private List`1 m_buff; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef9668 VA: 0x7594511668
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef96d0 VA: 0x75945116d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef9b4c VA: 0x7594511b4c
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ef9c48 VA: 0x7594511c48
	public Void .ctor() { }
}
```
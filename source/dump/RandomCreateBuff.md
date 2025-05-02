# RandomCreateBuff

**Namespace:** ` `


## Fields

- `Boolean _buffWithWeight`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RandomCreateBuff : ActionNode, IBuffSource
{
	private BuffPair[] _datas; // 0x10
	private Boolean _buffWithWeight; // 0x18
	private Boolean _isDerivedBuff; // 0x19
	private Boolean _finishDerivedBuffIfParentFinish; // 0x1a
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef90dc VA: 0x75945110dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef9144 VA: 0x7594511144
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef9488 VA: 0x7594511488
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ef95dc VA: 0x75945115dc
	public Void .ctor() { }
}
```
# CreateBuffById

**Namespace:** ` `


## Fields

- `String _buffKey`

- `ActionTargetType _buffOwner`

- `Boolean _isDerivedBuff`

- `Boolean _loadFromBlackboard`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffById : ActionNode, IBuffSource
{
	private String _buffKey; // 0x10
	private ActionTargetType _buffOwner; // 0x18
	private Boolean _isDerivedBuff; // 0x1c
	private Boolean _loadFromBlackboard; // 0x1d
	private Boolean _finishDerivedBuffIfParentFinish; // 0x1e
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef9d1c VA: 0x7594511d1c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef9d84 VA: 0x7594511d84
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef9f88 VA: 0x7594511f88
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1efa090 VA: 0x7594512090
	public Void .ctor() { }
}
```
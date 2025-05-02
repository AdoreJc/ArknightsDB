# CreateBuffToHost

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `BuffData _buffData`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToHost : ActionNode, IBuffSource
{
	private ActionTargetType _sourceType; // 0x10
	private BuffData _buffData; // 0x18
	private Boolean _isDerivedBuff; // 0x20
	private Boolean _finishDerivedBuffIfParentFinish; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1efcfc8 VA: 0x7594514fc8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1efd030 VA: 0x7594515030
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1efd290 VA: 0x7594515290
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1efd398 VA: 0x7594515398
	public Void .ctor() { }
}
```
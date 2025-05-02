# CreateBuffWithOverrideEffect

**Namespace:** ` `


## Fields

- `String _effectKey`

- `BuffData _buff`

- `ActionTargetType _buffOwner`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherEffects(List`1)`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffWithOverrideEffect : ActionNode, IBuffSource, IEffectSource, ICreateBuffNode
{
	private String _effectKey; // 0x10
	private BuffData _buff; // 0x18
	private ActionTargetType _buffOwner; // 0x20
	private Boolean _isDerivedBuff; // 0x24
	private Boolean _finishDerivedBuffIfParentFinish; // 0x25
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef8508 VA: 0x7594510508
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef8570 VA: 0x7594510570
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ef8684 VA: 0x7594510684
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef88ec VA: 0x75945108ec
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ef89e0 VA: 0x75945109e0
	public Void .ctor() { }
}
```
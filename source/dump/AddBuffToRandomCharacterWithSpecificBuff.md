# AddBuffToRandomCharacterWithSpecificBuff

**Namespace:** ` `


## Fields

- `String _buffKey`

- `Boolean _excludeToken`

- `Boolean _excludeTrap`

- `Boolean _excludeSpecificTarget`

- `ActionTargetType _excludeTargetType`

- `BuffData _buff`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddBuffToRandomCharacterWithSpecificBuff : ActionNode, IBuffSource, ICreateBuffNode
{
	private String _buffKey; // 0x10
	private Boolean _excludeToken; // 0x18
	private Boolean _excludeTrap; // 0x19
	private Boolean _excludeSpecificTarget; // 0x1a
	private ActionTargetType _excludeTargetType; // 0x1c
	private BuffData _buff; // 0x20
	private Boolean _isDerivedBuff; // 0x28
	private Boolean _finishDerivedBuffIfParentFinish; // 0x29
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7ea74 VA: 0x7594596a74
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7eadc VA: 0x7594596adc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7f0fc VA: 0x75945970fc
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f7f1f0 VA: 0x75945971f0
	public Void .ctor() { }
}
```
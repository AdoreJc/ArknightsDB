# AttachAsDerivedBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _buffKey`

- `Boolean _loadFromBlackboard`

- `Boolean _finishDerivedBuffIfParentFinish`

- `BuffData _buff`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AttachAsDerivedBuff : ActionNode, IBuffSource, ICreateBuffNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _buffKey; // 0x18
	private Boolean _loadFromBlackboard; // 0x20
	private Boolean _finishDerivedBuffIfParentFinish; // 0x21
	private BuffData _buff; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f03dac VA: 0x759451bdac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f03e14 VA: 0x759451be14
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f04044 VA: 0x759451c044
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f04138 VA: 0x759451c138
	public Void .ctor() { }
}
```
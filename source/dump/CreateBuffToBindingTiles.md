# CreateBuffToBindingTiles

**Namespace:** ` `


## Fields

- `BuffData _buff`

- `ActionTargetType _source`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`

- `Boolean _excludeRootTile`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToBindingTiles : ActionNode, IBuffSource
{
	private BuffData _buff; // 0x10
	private ActionTargetType _source; // 0x18
	private Boolean _isDerivedBuff; // 0x1c
	private Boolean _finishDerivedBuffIfParentFinish; // 0x1d
	private Boolean _excludeRootTile; // 0x1e
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef8ad0 VA: 0x7594510ad0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef8b38 VA: 0x7594510b38
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef8f70 VA: 0x7594510f70
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ef9064 VA: 0x7594511064
	public Void .ctor() { }
}
```
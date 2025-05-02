# RebuildCharacterOnRandomTile

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _createBuff`

- `BuffData _buff`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RebuildCharacterOnRandomTile : ActionNode, IBuffSource, ICreateBuffNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _createBuff; // 0x14
	private BuffData _buff; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd20d4 VA: 0x75945ea0d4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd213c VA: 0x75945ea13c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd2668 VA: 0x75945ea668
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1fd275c VA: 0x75945ea75c
	public Void .ctor() { }
}
```
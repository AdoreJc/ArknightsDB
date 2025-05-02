# AutoChessRebuildCharacterOnTile

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _rangeId`

- `Boolean _createBuff`

- `BuffData _buff`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessRebuildCharacterOnTile : ActionNode, IBuffSource, ICreateBuffNode
{
	private ActionTargetType _target; // 0x10
	private String _rangeId; // 0x18
	private Boolean _createBuff; // 0x20
	private BuffData _buff; // 0x28
	private static List`1 s_cachedTiles; // 0x0
	private static List`1 s_cachedEnemys; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee7c64 VA: 0x75944ffc64
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee7cdc VA: 0x75944ffcdc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee8890 VA: 0x7594500890
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ee8994 VA: 0x7594500994
	public Void .ctor() { }
	// RVA: 0x1ee8a44 VA: 0x7594500a44
	private static Void .cctor() { }
}
```
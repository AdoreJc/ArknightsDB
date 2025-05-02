# ForceSetToTilePosition

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _colKey`

- `String _rowKey`

- `Boolean _disableCurrentStillPull`

- `Single _randomOffset`

- `Single _randomOffsetInnerRange`

- `Boolean _findNearestPassableTile`


## Methods

- `Void _SetTargetToTileWithRandom(Tile, Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ForceSetToTilePosition : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _colKey; // 0x18
	private String _rowKey; // 0x20
	private Boolean _disableCurrentStillPull; // 0x28
	private Single _randomOffset; // 0x2c
	private Single _randomOffsetInnerRange; // 0x30
	private Boolean _findNearestPassableTile; // 0x34
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__SetTargetToTileWithRandom; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f5a574 VA: 0x7594572574
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5a5dc VA: 0x75945725dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5a904 VA: 0x7594572904
	private Void _SetTargetToTileWithRandom(Tile tile, Enemy target) { }
	// RVA: 0x1f5aa70 VA: 0x7594572a70
	public Void .ctor() { }
}
```
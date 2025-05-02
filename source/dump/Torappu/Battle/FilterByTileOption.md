# FilterByTileOption

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _checkPassableMask`

- `MotionMask _passableMask`

- `Boolean _checkBuildableType`

- `BuildableType _buildableType`

- `Boolean _checkBuildableMask`

- `AdvancedBuildableMask _advancedBuildableMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FilterByTileOption : ExtraBuildConditionNode
{
	private Boolean _checkPassableMask; // 0x10
	private MotionMask _passableMask; // 0x14
	private Boolean _checkBuildableType; // 0x18
	private BuildableType _buildableType; // 0x1c
	private Boolean _checkBuildableMask; // 0x20
	private AdvancedBuildableMask _advancedBuildableMask; // 0x24
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x1c451fc VA: 0x759425d1fc
	public override Boolean CheckBuildable(Tile tile, Direction direction, Boolean spawnManually, Boolean overflowOccupiedCnt, BattleCharacterData sourceData, PlayerSide operationSide) { }
	// RVA: 0x1c45364 VA: 0x759425d364
	public Void .ctor() { }
}
```
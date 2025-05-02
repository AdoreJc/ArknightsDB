# FilterByTileBlackboard

**Namespace:** `Torappu.Battle`


## Fields

- `String _blackboardKey`

- `String _value`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FilterByTileBlackboard : ExtraBuildConditionNode
{
	private String _blackboardKey; // 0x10
	private String _value; // 0x18
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x1c45014 VA: 0x759425d014
	public override Boolean CheckBuildable(Tile tile, Direction direction, Boolean spawnManually, Boolean overflowOccupiedCnt, BattleCharacterData sourceData, PlayerSide operationSide) { }
	// RVA: 0x1c45160 VA: 0x759425d160
	public Void .ctor() { }
}
```
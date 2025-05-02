# AutoChessEquipBuildBaseCondition

**Namespace:** `Torappu.Battle.GameMode`


## Fields

- `Int32 _chessLevelToCompare`

- `CompareType _condType`

- `String _filterGroupId`

- `ProfessionCategory _professionCategoryMask`


## Methods

- `Boolean _CheckTargetValidShopLevel(Tile)`

- `Boolean _CheckTargetNotGold(Tile)`

- `Boolean _CheckTargetChessLevel(Tile, Int32)`

- `Boolean _CheckTargetGroupId(Tile)`

- `Boolean _CheckTargetProfession(Tile)`

- `Boolean _CheckTargetIsDefaultFaction(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.GameMode
public class AutoChessEquipBuildBaseCondition : ExtraBuildConditionNode
{
	private ExtraBuildCondition[] _extraConditions; // 0x10
	private Int32 _chessLevelToCompare; // 0x18
	private CompareType _condType; // 0x1c
	private String _filterGroupId; // 0x20
	private ProfessionCategory _professionCategoryMask; // 0x28
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x0
	private static DelegateBridge __Hotfix0__CheckTargetValidShopLevel; // 0x8
	private static DelegateBridge __Hotfix0__CheckTargetNotGold; // 0x10
	private static DelegateBridge __Hotfix0__CheckTargetChessLevel; // 0x18
	private static DelegateBridge __Hotfix0__CheckTargetGroupId; // 0x20
	private static DelegateBridge __Hotfix0__CheckTargetProfession; // 0x28
	private static DelegateBridge __Hotfix0__CheckTargetIsDefaultFaction; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1d14b7c VA: 0x759432cb7c
	public override Boolean CheckBuildable(Tile tile, Direction direction, Boolean spawnManually, Boolean overflowOccupiedCnt, BattleCharacterData sourceData, PlayerSide operationSide) { }
	// RVA: 0x1d14e6c VA: 0x759432ce6c
	private Boolean _CheckTargetValidShopLevel(Tile tile) { }
	// RVA: 0x1d14f0c VA: 0x759432cf0c
	private Boolean _CheckTargetNotGold(Tile tile) { }
	// RVA: 0x1d15094 VA: 0x759432d094
	private Boolean _CheckTargetChessLevel(Tile tile, Int32 chessLevelToCompare) { }
	// RVA: 0x1d1523c VA: 0x759432d23c
	private Boolean _CheckTargetGroupId(Tile tile) { }
	// RVA: 0x1d1549c VA: 0x759432d49c
	private Boolean _CheckTargetProfession(Tile tile) { }
	// RVA: 0x1d155dc VA: 0x759432d5dc
	private Boolean _CheckTargetIsDefaultFaction(Tile tile) { }
	// RVA: 0x1d15734 VA: 0x759432d734
	public Void .ctor() { }
}
```
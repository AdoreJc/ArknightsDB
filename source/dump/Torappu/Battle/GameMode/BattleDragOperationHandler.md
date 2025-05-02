# BattleDragOperationHandler

**Namespace:** `Torappu.Battle.GameMode`


## Fields

- `GridPosition startPos`

- `Int32 startInstId`

- `GridPosition endPos`

- `GridPosition startPosRelatedTokenHandPos`

- `String startChessId`

- `Int32 endInstId`

- `GridPosition endPosRelatedTokenHandPos`

- `Direction selectedDirection`

- `AutoChessOperationCase currentCase`

- `Boolean m_inited`


## Methods

- `Void ConstructOperation(BattleGameInfo, GridPosition, GridPosition, Direction)`

- `Void _ApplyFlag(AutoChessDragOperationFlag, Boolean)`

- `Boolean _ContainsFlag(AutoChessDragOperationFlag)`

- `Boolean _DealWithHand2HandSwap(BattleGameInfo)`

- `Boolean _DealWithBattle2BattleSwap(BattleGameInfo)`

- `Boolean _DealWithHand2BattleSwap(BattleGameInfo)`

- `Void _DealWithBattleCharacter2BattleTokenSwap(BattleGameInfo)`

- `Void _DealWithHandCharacter2BattleTokenSwap(BattleGameInfo)`

- `Void _DealWithBattleCharacter2BattleCharacterSwap(BattleGameInfo)`

- `Void _DealWithHandCharacter2BattleCharacterSwap(BattleGameInfo)`

- `Void DealWithToken2BattlePlaceEmpty(BattleGameInfo)`

- `Void _DealWithHandCharacter2BattlePlaceEmpty(BattleGameInfo)`

- `Void _DealWithBattleCharacter2BattlePlaceEmpty(BattleGameInfo)`

- `Void _DealWithBattleToken2BattleTokenSwap(BattleGameInfo)`

- `Void _DealWithHandToken2BattleTokenSwap(BattleGameInfo)`

- `Void _DealWithBattleToken2BattleCharacterSwap(BattleGameInfo)`

- `Void _DealWithHandToken2BattleCharacterSwap(BattleGameInfo)`

- `Void _MoveInstFromStart2End(BattleGameInfo)`

- `Void _SendTokenToValidHand(BattleGameInfo, Int32)`

- `Void _UpdateMap(BattleGameInfo, Boolean, GridPosition, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.GameMode
public class BattleDragOperationHandler : AutoChessGameModeTileOperationHandlerBase
{
	public GridPosition startPos; // 0x10
	public Int32 startInstId; // 0x18
	public GridPosition endPos; // 0x1c
	public GridPosition startPosRelatedTokenHandPos; // 0x24
	public String startChessId; // 0x30
	public Int32 endInstId; // 0x38
	public GridPosition endPosRelatedTokenHandPos; // 0x3c
	public Direction selectedDirection; // 0x44
	public AutoChessOperationCase currentCase; // 0x48
	private Boolean m_inited; // 0x50
	private static DelegateBridge __Hotfix0_ConstructOperation; // 0x0
	private static DelegateBridge __Hotfix0_CheckOperationValid; // 0x8
	private static DelegateBridge __Hotfix0_PushMeta; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0__ApplyFlag; // 0x20
	private static DelegateBridge __Hotfix0__ContainsFlag; // 0x28
	private static DelegateBridge __Hotfix0__DealWithHand2HandSwap; // 0x30
	private static DelegateBridge __Hotfix0__DealWithBattle2BattleSwap; // 0x38
	private static DelegateBridge __Hotfix0__DealWithHand2BattleSwap; // 0x40
	private static DelegateBridge __Hotfix0__DealWithBattleCharacter2BattleTokenSwap; // 0x48
	private static DelegateBridge __Hotfix0__DealWithHandCharacter2BattleTokenSwap; // 0x50
	private static DelegateBridge __Hotfix0__DealWithBattleCharacter2BattleCharacterSwap; // 0x58
	private static DelegateBridge __Hotfix0__DealWithHandCharacter2BattleCharacterSwap; // 0x60
	private static DelegateBridge __Hotfix0_DealWithToken2BattlePlaceEmpty; // 0x68
	private static DelegateBridge __Hotfix0__DealWithHandCharacter2BattlePlaceEmpty; // 0x70
	private static DelegateBridge __Hotfix0__DealWithBattleCharacter2BattlePlaceEmpty; // 0x78
	private static DelegateBridge __Hotfix0__DealWithBattleToken2BattleTokenSwap; // 0x80
	private static DelegateBridge __Hotfix0__DealWithHandToken2BattleTokenSwap; // 0x88
	private static DelegateBridge __Hotfix0__DealWithBattleToken2BattleCharacterSwap; // 0x90
	private static DelegateBridge __Hotfix0__DealWithHandToken2BattleCharacterSwap; // 0x98
	private static DelegateBridge __Hotfix0__MoveInstFromStart2End; // 0xa0
	private static DelegateBridge __Hotfix0__SendTokenToValidHand; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateMap; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8


	// RVA: 0x1d08d14 VA: 0x7594320d14
	public Void ConstructOperation(BattleGameInfo gameInfo, GridPosition start, GridPosition end, Direction direction) { }
	// RVA: 0x1d09944 VA: 0x7594321944
	public override Boolean CheckOperationValid() { }
	// RVA: 0x1d09ac8 VA: 0x7594321ac8
	protected override Boolean PushMeta(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0a0fc VA: 0x75943220fc
	public override Void Reset() { }
	// RVA: 0x1d09194 VA: 0x7594321194
	private Void _ApplyFlag(AutoChessDragOperationFlag flag, Boolean apply) { }
	// RVA: 0x1d09598 VA: 0x7594321598
	private Boolean _ContainsFlag(AutoChessDragOperationFlag flag) { }
	// RVA: 0x1d09c08 VA: 0x7594321c08
	private Boolean _DealWithHand2HandSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d09d54 VA: 0x7594321d54
	private Boolean _DealWithBattle2BattleSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d09eb4 VA: 0x7594321eb4
	private Boolean _DealWithHand2BattleSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0a894 VA: 0x7594322894
	private Void _DealWithBattleCharacter2BattleTokenSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0af64 VA: 0x7594322f64
	private Void _DealWithHandCharacter2BattleTokenSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0a6c4 VA: 0x75943226c4
	private Void _DealWithBattleCharacter2BattleCharacterSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0ae14 VA: 0x7594322e14
	private Void _DealWithHandCharacter2BattleCharacterSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0a2dc VA: 0x75943222dc
	private Void DealWithToken2BattlePlaceEmpty(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0ad28 VA: 0x7594322d28
	private Void _DealWithHandCharacter2BattlePlaceEmpty(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0a5b4 VA: 0x75943225b4
	private Void _DealWithBattleCharacter2BattlePlaceEmpty(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0a48c VA: 0x759432248c
	private Void _DealWithBattleToken2BattleTokenSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0abdc VA: 0x7594322bdc
	private Void _DealWithHandToken2BattleTokenSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0a35c VA: 0x759432235c
	private Void _DealWithBattleToken2BattleCharacterSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0aa94 VA: 0x7594322a94
	private Void _DealWithHandToken2BattleCharacterSwap(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0b29c VA: 0x759432329c
	private Void _MoveInstFromStart2End(BattleGameInfo gameInfo) { }
	// RVA: 0x1d0b204 VA: 0x7594323204
	private Void _SendTokenToValidHand(BattleGameInfo gameInfo, Int32 instId) { }
	// RVA: 0x1d0a178 VA: 0x7594322178
	protected Void _UpdateMap(BattleGameInfo gameInfo, Boolean isSet, GridPosition pos, Int32 instId, Boolean isToken) { }
	// RVA: 0x1d0b360 VA: 0x7594323360
	public Void .ctor() { }
}
```
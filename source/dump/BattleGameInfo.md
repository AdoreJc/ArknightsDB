# BattleGameInfo

**Namespace:** ` `


## Fields

- `Int32 m_overflowItemCnt`


## Properties

- `Int32 overflowItemCnt`


## Methods

- `Int32 get_overflowItemCnt()`

- `Void CollectInBattleInst(ref, ListDict`2, ActivityAutoChessVerify1Data)`

- `Int32 GetMaxBuildSeq()`

- `Void SendTokenToValidHand(Int32, Boolean)`

- `Int32 GetCntByCondition(Func`2)`

- `Void LoadData(BattleGameInfo)`

- `Void LoadData(AutoChessGameInfo)`

- `Void LoadData(AutoChessChar[], AutoChessTrap[], Dictionary`2, Int32)`

- `Boolean RemoveAllInstIdRelatedToken(Int32)`

- `Void OptimizeHandMap(Int32)`

- `GridPosition GetFirstEmptyHand()`

- `Void UpdateMap(Boolean, GridPosition, Int32, Direction, Boolean)`

- `Boolean _CollectFromInsts(IEnumerable`1, List`1)`

- `Boolean _RemoveInvalid(AutoChessChar[], AutoChessTrap[], Dictionary`2)`

- `Boolean _InsertNewChesses(AutoChessChar[], AutoChessTrap[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BattleGameInfo : AutoChessViewModelBase
{
	public Dictionary`2 chessInstMap; // 0x18
	private Int32 m_overflowItemCnt; // 0x20
	private static DelegateBridge __Hotfix0_get_overflowItemCnt; // 0x0
	private static DelegateBridge __Hotfix0_CollectInBattleInst; // 0x8
	private static DelegateBridge __Hotfix0_GetMaxBuildSeq; // 0x10
	private static DelegateBridge __Hotfix0_SendTokenToValidHand; // 0x18
	private static DelegateBridge __Hotfix0_GetCntByCondition; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix1_LoadData; // 0x30
	private static DelegateBridge __Hotfix2_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_RemoveAllInstIdRelatedToken; // 0x40
	private static DelegateBridge __Hotfix0_OptimizeHandMap; // 0x48
	private static DelegateBridge __Hotfix0_GetFirstEmptyHand; // 0x50
	private static DelegateBridge __Hotfix0_UpdateMap; // 0x58
	private static DelegateBridge __Hotfix0__CollectFromInsts; // 0x60
	private static DelegateBridge __Hotfix0__RemoveInvalid; // 0x68
	private static DelegateBridge __Hotfix0__ContainInst; // 0x70
	private static DelegateBridge __Hotfix0__InsertNewChesses; // 0x78
	private static DelegateBridge __Hotfix0_op_Implicit; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Int32 overflowItemCnt { get; }

	// RVA: 0x1cfd504 VA: 0x7594315504
	public Int32 get_overflowItemCnt() { }
	// RVA: 0x1cfd56c VA: 0x759431556c
	public Void CollectInBattleInst(ref List`1 battleInsts, ListDict`2 inst2ChessIdMap, ActivityAutoChessVerify1Data data) { }
	// RVA: 0x1cfd8f4 VA: 0x75943158f4
	public Int32 GetMaxBuildSeq() { }
	// RVA: 0x1cfda90 VA: 0x7594315a90
	public Void SendTokenToValidHand(Int32 instId, Boolean removeOrigin) { }
	// RVA: 0x1cfe7b4 VA: 0x75943167b4
	public Int32 GetCntByCondition(Func`2 condition) { }
	// RVA: 0x1cfc588 VA: 0x7594314588
	public Void LoadData(BattleGameInfo info) { }
	// RVA: 0x1cfe980 VA: 0x7594316980
	public Void LoadData(AutoChessGameInfo origin) { }
	// RVA: 0x1cfc8bc VA: 0x75943148bc
	public Void LoadData(AutoChessChar[] chars, AutoChessTrap[] traps, Dictionary`2 spells, Int32 maxHandCnt) { }
	// RVA: 0x1cfdf0c VA: 0x7594315f0c
	public Boolean RemoveAllInstIdRelatedToken(Int32 instId) { }
	// RVA: 0x1cff988 VA: 0x7594317988
	public Void OptimizeHandMap(Int32 maxHandCnt) { }
	// RVA: 0x1cfe31c VA: 0x759431631c
	public GridPosition GetFirstEmptyHand() { }
	// RVA: 0x1cfe548 VA: 0x7594316548
	public Void UpdateMap(Boolean isSet, GridPosition pos, Int32 instId, Direction direction, Boolean isToken) { }
	// RVA: 0x1d00204 VA: 0x7594318204
	private Boolean _CollectFromInsts(IEnumerable`1 traps, List`1 handInst) { }
	// RVA: 0x1cfef98 VA: 0x7594316f98
	private Boolean _RemoveInvalid(AutoChessChar[] chars, AutoChessTrap[] traps, Dictionary`2 spells) { }
	// RVA: 0x1d00780 VA: 0x7594318780
	private static Boolean _ContainInst(AutoChessChar[] chars, AutoChessTrap[] traps, Dictionary`2 spells, KeyValuePair`2 inst) { }
	// RVA: 0x1cff4f4 VA: 0x75943174f4
	private Boolean _InsertNewChesses(AutoChessChar[] chars, AutoChessTrap[] traps) { }
	// RVA: 0x1d00a6c VA: 0x7594318a6c
	public static GameInfo op_Implicit(BattleGameInfo info) { }
	// RVA: 0x1cfc7f8 VA: 0x75943147f8
	public Void .ctor() { }
}
```
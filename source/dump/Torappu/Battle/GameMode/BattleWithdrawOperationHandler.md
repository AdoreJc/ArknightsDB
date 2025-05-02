# BattleWithdrawOperationHandler

**Namespace:** `Torappu.Battle.GameMode`


## Fields

- `Boolean isBattleField`

- `Boolean isToken`

- `GridPosition pos`


## Methods

- `Void ConstructOperation(BattleGameInfo, GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.GameMode
public class BattleWithdrawOperationHandler : AutoChessGameModeTileOperationHandlerBase
{
	public Boolean isBattleField; // 0x10
	public Boolean isToken; // 0x11
	public GridPosition pos; // 0x14
	private static DelegateBridge __Hotfix0_ConstructOperation; // 0x0
	private static DelegateBridge __Hotfix0_CheckOperationValid; // 0x8
	private static DelegateBridge __Hotfix0_PushMeta; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1d08944 VA: 0x7594320944
	public Void ConstructOperation(BattleGameInfo gameInfo, GridPosition pos) { }
	// RVA: 0x1d089fc VA: 0x75943209fc
	public override Boolean CheckOperationValid() { }
	// RVA: 0x1d08a64 VA: 0x7594320a64
	protected override Boolean PushMeta(BattleGameInfo gameInfo) { }
	// RVA: 0x1d08c40 VA: 0x7594320c40
	public override Void Reset() { }
	// RVA: 0x1d08ca8 VA: 0x7594320ca8
	public Void .ctor() { }
}
```
# InstTileTileDataBinder

**Namespace:** ` `


## Fields

- `SeqNumChecker m_handBattleChecker`


## Methods

- `Void _RemoveDummyOnTile(Character, Tile)`

- `Void _CreateDummyOnTile(BattleChessInst, Tile)`

- `Void <>xLuaBaseProxy_DoNotifyUpdate(BattlePlayerAutoChessData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InstTileTileDataBinder : AutoChessDataBinder
{
	private SeqNumChecker m_handBattleChecker; // 0x18
	private static DelegateBridge __Hotfix0_GetTiles; // 0x0
	private static DelegateBridge __Hotfix0_DoNotifyUpdate; // 0x8
	private static DelegateBridge __Hotfix0__RemoveDummyOnTile; // 0x10
	private static DelegateBridge __Hotfix0__CreateDummyOnTile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ca2df8 VA: 0x75942badf8
	protected virtual IEnumerable`1 GetTiles() { }
	// RVA: 0x1ca2ed8 VA: 0x75942baed8
	protected override Void DoNotifyUpdate(BattlePlayerAutoChessData data) { }
	// RVA: 0x1ca3624 VA: 0x75942bb624
	private Void _RemoveDummyOnTile(Character character, Tile tile) { }
	// RVA: 0x1ca3728 VA: 0x75942bb728
	public Void _CreateDummyOnTile(BattleChessInst chessInst, Tile tile) { }
	// RVA: 0x1ca39a4 VA: 0x75942bb9a4
	public Void .ctor() { }
	// RVA: 0x1ca3a54 VA: 0x75942bba54
	private Void <>xLuaBaseProxy_DoNotifyUpdate(BattlePlayerAutoChessData P0) { }
}
```
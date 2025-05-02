# ShopTileTileDataBinder

**Namespace:** ` `


## Fields

- `SeqNumChecker m_statusChecker`

- `SeqNumChecker m_shopResponseChecker`

- `SeqNumChecker m_finishResponseChecker`


## Methods

- `Void _UpdateForce(AutoChessDataCenter)`

- `Void _UpdaetShopItems(AutoChessDataCenter, String, Func`2, Func`2)`

- `Void <>xLuaBaseProxy_DoNotifyDummyAsyncChanged(BattlePlayerAutoChessData)`

- `Void <>xLuaBaseProxy_DoNotifyUpdate(BattlePlayerAutoChessData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ShopTileTileDataBinder : AutoChessDataBinder
{
	private SeqNumChecker m_statusChecker; // 0x18
	private SeqNumChecker m_shopResponseChecker; // 0x20
	private SeqNumChecker m_finishResponseChecker; // 0x28
	private static DelegateBridge __Hotfix0_DoNotifyDummyAsyncChanged; // 0x0
	private static DelegateBridge __Hotfix0_DoNotifyUpdate; // 0x8
	private static DelegateBridge __Hotfix0__UpdateForce; // 0x10
	private static DelegateBridge __Hotfix0__UpdaetShopItems; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ca1220 VA: 0x75942b9220
	protected override Void DoNotifyDummyAsyncChanged(BattlePlayerAutoChessData data) { }
	// RVA: 0x1ca18d8 VA: 0x75942b98d8
	protected override Void DoNotifyUpdate(BattlePlayerAutoChessData data) { }
	// RVA: 0x1ca1d8c VA: 0x75942b9d8c
	private Void _UpdateForce(AutoChessDataCenter center) { }
	// RVA: 0x1ca2194 VA: 0x75942ba194
	private Void _UpdaetShopItems(AutoChessDataCenter center, String key, Func`2 tileIsValid, Func`2 chessIdIsValid) { }
	// RVA: 0x1ca2ce8 VA: 0x75942bace8
	public Void .ctor() { }
	// RVA: 0x1ca2de8 VA: 0x75942bade8
	private Void <>xLuaBaseProxy_DoNotifyDummyAsyncChanged(BattlePlayerAutoChessData P0) { }
	// RVA: 0x1ca2df0 VA: 0x75942badf0
	private Void <>xLuaBaseProxy_DoNotifyUpdate(BattlePlayerAutoChessData P0) { }
}
```
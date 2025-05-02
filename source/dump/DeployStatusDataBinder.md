# DeployStatusDataBinder

**Namespace:** ` `


## Fields

- `SeqNumChecker m_handBattleChecker`


## Methods

- `Void _DoCheckDeployStatus(BattlePlayerAutoChessData)`

- `Void <>xLuaBaseProxy_DoNotifyUpdate(BattlePlayerAutoChessData)`

- `Void <>xLuaBaseProxy_DoNotifyDummyAsyncChanged(BattlePlayerAutoChessData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DeployStatusDataBinder : AutoChessDataBinder
{
	private SeqNumChecker m_handBattleChecker; // 0x18
	private static DelegateBridge __Hotfix0_DoNotifyUpdate; // 0x0
	private static DelegateBridge __Hotfix0_DoNotifyDummyAsyncChanged; // 0x8
	private static DelegateBridge __Hotfix0__DoCheckDeployStatus; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1ca08b8 VA: 0x75942b88b8
	protected override Void DoNotifyUpdate(BattlePlayerAutoChessData data) { }
	// RVA: 0x1ca0e1c VA: 0x75942b8e1c
	protected override Void DoNotifyDummyAsyncChanged(BattlePlayerAutoChessData data) { }
	// RVA: 0x1ca09e8 VA: 0x75942b89e8
	private Void _DoCheckDeployStatus(BattlePlayerAutoChessData data) { }
	// RVA: 0x1ca1160 VA: 0x75942b9160
	public Void .ctor() { }
	// RVA: 0x1ca1210 VA: 0x75942b9210
	private Void <>xLuaBaseProxy_DoNotifyUpdate(BattlePlayerAutoChessData P0) { }
	// RVA: 0x1ca1218 VA: 0x75942b9218
	private Void <>xLuaBaseProxy_DoNotifyDummyAsyncChanged(BattlePlayerAutoChessData P0) { }
}
```
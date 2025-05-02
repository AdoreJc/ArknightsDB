# EffectInfoViewModel

**Namespace:** ` `


## Properties

- `Boolean isValid`


## Methods

- `Boolean get_isValid()`

- `Void Reset()`

- `Void LoadData(AutoChessBehaviourMessage, BattleGameInfo, BattleGameInfo)`

- `Void LoadDestoryedData(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void LoadUpdaeData(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void UpdateDirty()`

- `Void _ProcessGaineReward(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void _ProcessDeckExchangeGained(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void _ProcessGainChar(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void _ProcessGainTrap(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void _ProcessUpgrade(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void _ProcessGainTrapChessDestory(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void _PreProcessEquipAutoDestoryDestory(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void _ProcessDeckExchangeDeleted(AutoChessBehaviourMessage, BattleGameInfo)`

- `Void _ProcessGetChessDelDestory(AutoChessBehaviourMessage, BattleGameInfo)`

- `Boolean _GetInstSourcePos(BattleGameInfo, Int32, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EffectInfoViewModel : AutoChessViewModelBase
{
	public List`1 effectInfos; // 0x18
	private ListDict`2 m_oldPosMapping; // 0x20
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_LoadDestoryedData; // 0x18
	private static DelegateBridge __Hotfix0_LoadUpdaeData; // 0x20
	private static DelegateBridge __Hotfix0_UpdateDirty; // 0x28
	private static DelegateBridge __Hotfix0__ProcessGaineReward; // 0x30
	private static DelegateBridge __Hotfix0__ProcessDeckExchangeGained; // 0x38
	private static DelegateBridge __Hotfix0__ProcessGainChar; // 0x40
	private static DelegateBridge __Hotfix0__ProcessGainTrap; // 0x48
	private static DelegateBridge __Hotfix0__ProcessUpgrade; // 0x50
	private static DelegateBridge __Hotfix0__ProcessGainTrapChessDestory; // 0x58
	private static DelegateBridge __Hotfix0__PreProcessEquipAutoDestoryDestory; // 0x60
	private static DelegateBridge __Hotfix0__ProcessDeckExchangeDeleted; // 0x68
	private static DelegateBridge __Hotfix0__ProcessGetChessDelDestory; // 0x70
	private static DelegateBridge __Hotfix0__GetInstSourcePos; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Boolean isValid { get; }

	// RVA: 0x1d0126c VA: 0x759431926c
	public Boolean get_isValid() { }
	// RVA: 0x1d012f8 VA: 0x75943192f8
	public Void Reset() { }
	// RVA: 0x1d013a0 VA: 0x75943193a0
	public Void LoadData(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoCached, BattleGameInfo gameInfoRefreshed) { }
	// RVA: 0x1d01478 VA: 0x7594319478
	public Void LoadDestoryedData(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoCached) { }
	// RVA: 0x1d015fc VA: 0x75943195fc
	public Void LoadUpdaeData(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoRefreshed) { }
	// RVA: 0x1d017b4 VA: 0x75943197b4
	public Void UpdateDirty() { }
	// RVA: 0x1d03b80 VA: 0x759431bb80
	private Void _ProcessGaineReward(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoRefreshed) { }
	// RVA: 0x1d03774 VA: 0x759431b774
	private Void _ProcessDeckExchangeGained(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoRefreshed) { }
	// RVA: 0x1d031cc VA: 0x759431b1cc
	private Void _ProcessGainChar(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoRefreshed) { }
	// RVA: 0x1d02c34 VA: 0x759431ac34
	private Void _ProcessGainTrap(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoRefreshed) { }
	// RVA: 0x1d02974 VA: 0x759431a974
	private Void _ProcessUpgrade(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoRefreshed) { }
	// RVA: 0x1d0202c VA: 0x759431a02c
	private Void _ProcessGainTrapChessDestory(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoCached) { }
	// RVA: 0x1d01ce0 VA: 0x7594319ce0
	private Void _PreProcessEquipAutoDestoryDestory(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoCached) { }
	// RVA: 0x1d024f0 VA: 0x759431a4f0
	private Void _ProcessDeckExchangeDeleted(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoRefreshed) { }
	// RVA: 0x1d01854 VA: 0x7594319854
	private Void _ProcessGetChessDelDestory(AutoChessBehaviourMessage behaviourMessage, BattleGameInfo gameInfoCached) { }
	// RVA: 0x1d03e3c VA: 0x759431be3c
	private Boolean _GetInstSourcePos(BattleGameInfo gameInfoCached, Int32 instId, out GridPosition pos) { }
	// RVA: 0x1cfd2b0 VA: 0x75943152b0
	public Void .ctor() { }
}
```
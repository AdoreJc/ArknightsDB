# TutorialChecker

**Namespace:** ` `


## Methods

- `Void _HandleStartTutorial(Object)`

- `Boolean _TryTriggerTutorial(AutoChessDataCenter)`

- `Boolean _TryTriggerBuyCharChess(AutoChessDataCenter)`

- `Boolean _TryTriggerShopLevelUp(AutoChessDataCenter)`

- `Boolean _TryTriggerPrepareBattle(AutoChessDataCenter)`

- `Boolean _TryTriggerBuyEquipChess(AutoChessDataCenter)`

- `Boolean _TryTriggerWearEquip(AutoChessDataCenter)`

- `Boolean _TryTriggerBuySecondCharChess(AutoChessDataCenter)`

- `Boolean _TryTriggerBuyThirdCharChess(AutoChessDataCenter)`

- `Boolean _TryTriggerUseSpecialMagic(AutoChessDataCenter)`

- `Boolean _TryTriggerBuySpecialCharacterChess(AutoChessDataCenter)`

- `Boolean _TryTriggerRefreshStore2ndTime(AutoChessDataCenter)`

- `Boolean _TryTriggerBuySecondEquip(AutoChessDataCenter)`

- `Boolean _TryTriggerShopLevelUp2ndTime(AutoChessDataCenter)`

- `Void _TryRaiseSignalChessInBattle(AutoChessDataCenter)`

- `Void _RegisterTutorialTarget(String, GridPosition)`

- `Void <>xLuaBaseProxy_Init()`

- `Void <>xLuaBaseProxy_DoNotifyUpdate(BattlePlayerAutoChessData)`

- `Void <>xLuaBaseProxy_DoNotifyDummyAsyncChanged(BattlePlayerAutoChessData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TutorialChecker : AutoChessDataBinder
{
	private List`1 m_tutorialSignalList; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0__HandleStartTutorial; // 0x8
	private static DelegateBridge __Hotfix0_get_tutorialSignalList; // 0x10
	private static DelegateBridge __Hotfix0_DoNotifyUpdate; // 0x18
	private static DelegateBridge __Hotfix0__TryTriggerTutorial; // 0x20
	private static DelegateBridge __Hotfix0_DoNotifyDummyAsyncChanged; // 0x28
	private static DelegateBridge __Hotfix0__TryTriggerBuyCharChess; // 0x30
	private static DelegateBridge __Hotfix0__TryTriggerShopLevelUp; // 0x38
	private static DelegateBridge __Hotfix0__TryTriggerPrepareBattle; // 0x40
	private static DelegateBridge __Hotfix0__TryTriggerBuyEquipChess; // 0x48
	private static DelegateBridge __Hotfix0__TryTriggerWearEquip; // 0x50
	private static DelegateBridge __Hotfix0__TryTriggerBuySecondCharChess; // 0x58
	private static DelegateBridge __Hotfix0__TryTriggerBuyThirdCharChess; // 0x60
	private static DelegateBridge __Hotfix0__TryTriggerUseSpecialMagic; // 0x68
	private static DelegateBridge __Hotfix0__TryTriggerBuySpecialCharacterChess; // 0x70
	private static DelegateBridge __Hotfix0__TryTriggerRefreshStore2ndTime; // 0x78
	private static DelegateBridge __Hotfix0__TryTriggerBuySecondEquip; // 0x80
	private static DelegateBridge __Hotfix0__TryTriggerShopLevelUp2ndTime; // 0x88
	private static DelegateBridge __Hotfix0__TryRaiseSignalChessInBattle; // 0x90
	private static DelegateBridge __Hotfix0__RegisterTutorialTarget; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	private List`1 tutorialSignalList { get; }

	// RVA: 0x1c9c99c VA: 0x75942b499c
	public override Void Init() { }
	// RVA: 0x1c9ca60 VA: 0x75942b4a60
	private Void _HandleStartTutorial(Object arg) { }
	// RVA: 0x1c9cb28 VA: 0x75942b4b28
	private List`1 get_tutorialSignalList() { }
	// RVA: 0x1c9d320 VA: 0x75942b5320
	protected override Void DoNotifyUpdate(BattlePlayerAutoChessData data) { }
	// RVA: 0x1c9d3f0 VA: 0x75942b53f0
	private Boolean _TryTriggerTutorial(AutoChessDataCenter center) { }
	// RVA: 0x1c9d73c VA: 0x75942b573c
	protected override Void DoNotifyDummyAsyncChanged(BattlePlayerAutoChessData data) { }
	// RVA: 0x1c9d7c4 VA: 0x75942b57c4
	private Boolean _TryTriggerBuyCharChess(AutoChessDataCenter center) { }
	// RVA: 0x1c9dab8 VA: 0x75942b5ab8
	private Boolean _TryTriggerShopLevelUp(AutoChessDataCenter center) { }
	// RVA: 0x1c9dcc8 VA: 0x75942b5cc8
	private Boolean _TryTriggerPrepareBattle(AutoChessDataCenter center) { }
	// RVA: 0x1c9ddfc VA: 0x75942b5dfc
	private Boolean _TryTriggerBuyEquipChess(AutoChessDataCenter center) { }
	// RVA: 0x1c9df70 VA: 0x75942b5f70
	private Boolean _TryTriggerWearEquip(AutoChessDataCenter center) { }
	// RVA: 0x1c9e138 VA: 0x75942b6138
	private Boolean _TryTriggerBuySecondCharChess(AutoChessDataCenter center) { }
	// RVA: 0x1c9e2d8 VA: 0x75942b62d8
	private Boolean _TryTriggerBuyThirdCharChess(AutoChessDataCenter center) { }
	// RVA: 0x1c9e478 VA: 0x75942b6478
	private Boolean _TryTriggerUseSpecialMagic(AutoChessDataCenter center) { }
	// RVA: 0x1c9e640 VA: 0x75942b6640
	private Boolean _TryTriggerBuySpecialCharacterChess(AutoChessDataCenter center) { }
	// RVA: 0x1c9e7c4 VA: 0x75942b67c4
	private Boolean _TryTriggerRefreshStore2ndTime(AutoChessDataCenter center) { }
	// RVA: 0x1c9e9f0 VA: 0x75942b69f0
	private Boolean _TryTriggerBuySecondEquip(AutoChessDataCenter center) { }
	// RVA: 0x1c9ebc4 VA: 0x75942b6bc4
	private Boolean _TryTriggerShopLevelUp2ndTime(AutoChessDataCenter center) { }
	// RVA: 0x1c9d614 VA: 0x75942b5614
	private Void _TryRaiseSignalChessInBattle(AutoChessDataCenter center) { }
	// RVA: 0x1c9d938 VA: 0x75942b5938
	private Void _RegisterTutorialTarget(String targetKey, GridPosition validChessPos) { }
	// RVA: 0x1c9c64c VA: 0x75942b464c
	public Void .ctor() { }
	// RVA: 0x1c9eda4 VA: 0x75942b6da4
	private Void <>xLuaBaseProxy_Init() { }
	// RVA: 0x1c9eda8 VA: 0x75942b6da8
	private Void <>xLuaBaseProxy_DoNotifyUpdate(BattlePlayerAutoChessData P0) { }
	// RVA: 0x1c9edac VA: 0x75942b6dac
	private Void <>xLuaBaseProxy_DoNotifyDummyAsyncChanged(BattlePlayerAutoChessData P0) { }
}
```
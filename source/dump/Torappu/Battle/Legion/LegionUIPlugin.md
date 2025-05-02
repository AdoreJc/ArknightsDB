# LegionUIPlugin

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `BasicStatus _basicStatus`

- `UILegionDangerLevel _dangerLevelInfo`

- `UIBattleLegionWidgetsPanel _widgetsPanel`

- `UIBattleLegionIntermissionTipsPanel _intermissionPanel`

- `UILegionBlastCardToastPanel _toastBlastCard`

- `UILegionTrapEffectToastPanel _toastTrapEffect`

- `UIBattleBlurPanel _blurPanel`

- `LegionUICharacterStatusController _characterStatusController`

- `UIBattleLegionWidgetsPanel m_widgetsPanel`

- `UIBattleLegionIntermissionTipsPanel m_intermissionPanel`

- `UILegionBlastCardToastPanel m_toastBlastCard`

- `UILegionTrapEffectToastPanel m_toastTrapEffect`

- `LegionGameMode m_manager`

- `Boolean m_isSelectCardShown`


## Properties

- `LegionGameMode manager`

- `Boolean isSelectCardShown`


## Methods

- `LegionGameMode get_manager()`

- `Boolean get_isSelectCardShown()`

- `Void InitDangerLevel(Single, Int32)`

- `Void UpdateDangerLevel(Int32, Int32, Single)`

- `Void _OnCurWaveWillFinish(Single)`

- `Void _OnShowSelectCardPanel(Object)`

- `Void _SwitchToSelectCardState()`

- `Void OnGameStarted()`

- `Void StartRedrawCard()`

- `Void OnCardRedrawConfirmed(List`1)`

- `Void OnCardSelectConfirmed()`

- `Void OnCardSelectHiden()`

- `Void _PreloadAssets()`

- `Void ShowUsedCard()`

- `Void ShowPendingCard()`

- `Void _SwitchToCardLibraryState(LegionCardLibraryType)`

- `Void CloseLibraryPanel()`

- `Void ShowLegionWidgetPanel(Boolean)`

- `Void <OnGameReset>b__34_0(Object)`

- `Void <OnGameReset>b__34_1(Object)`

- `Void <>xLuaBaseProxy_OnDummyTouchedToTile(Character, Tile)`

- `Void <>xLuaBaseProxy_OnUnitBorn(Unit)`

- `Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch()`

- `Void <>xLuaBaseProxy_OnSystemMenuCancel()`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnGameReady()`

- `Void <>xLuaBaseProxy_OnGameReset(BattleController)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode)`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_OnCardMenuShow(Card)`

- `Void <>xLuaBaseProxy_OnCharacterMenuShow(Character)`

- `Void <>xLuaBaseProxy_OnCharacterMenuHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class LegionUIPlugin : Plugin
{
	public static readonly UIStateEnum UI_STATE_BATTLE_START; // 0x0
	public static readonly UIStateEnum UI_STATE_CARD_REDRAW; // 0x4
	public static readonly UIStateEnum UI_STATE_CARD_SELECT; // 0x8
	public static readonly UIStateEnum UI_STATE_CARD_LIBRARY; // 0xc
	private UIStateNode[] _states; // 0x28
	private BasicStatus _basicStatus; // 0x30
	private UILegionDangerLevel _dangerLevelInfo; // 0x38
	private UIBattleLegionWidgetsPanel _widgetsPanel; // 0x40
	private UIBattleLegionIntermissionTipsPanel _intermissionPanel; // 0x48
	private HookedCharacterInfoSubPanel[] _hookedCharacterInfoSubPanels; // 0x50
	private UILegionBlastCardToastPanel _toastBlastCard; // 0x58
	private UILegionTrapEffectToastPanel _toastTrapEffect; // 0x60
	private UIBattleBlurPanel _blurPanel; // 0x68
	private LegionUICharacterStatusController _characterStatusController; // 0x70
	private UIBattleLegionWidgetsPanel m_widgetsPanel; // 0x78
	private UIBattleLegionIntermissionTipsPanel m_intermissionPanel; // 0x80
	private UILegionBlastCardToastPanel m_toastBlastCard; // 0x88
	private UILegionTrapEffectToastPanel m_toastTrapEffect; // 0x90
	private LegionGameMode m_manager; // 0x98
	private Boolean m_isSelectCardShown; // 0xa0
	private List`1 m_selectCardParamList; // 0xa8
	private static Vector2 CARD_LIST_OFFSET_MAX; // 0x10
	private static Vector2 CARD_LIST_OFFSET_MIN; // 0x18
	private static DelegateBridge __Hotfix0_get_manager; // 0x20
	private static DelegateBridge __Hotfix0_get_isSelectCardShown; // 0x28
	private static DelegateBridge __Hotfix0_HookCharacterInfoSubPanels; // 0x30
	private static DelegateBridge __Hotfix0_OnDummyTouchedToTile; // 0x38
	private static DelegateBridge __Hotfix0_OnUnitBorn; // 0x40
	private static DelegateBridge __Hotfix0_HookGameReadyStateSwitch; // 0x48
	private static DelegateBridge __Hotfix0_OnSystemMenuCancel; // 0x50
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x58
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x60
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x68
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x70
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x78
	private static DelegateBridge __Hotfix0_InitDangerLevel; // 0x80
	private static DelegateBridge __Hotfix0_UpdateDangerLevel; // 0x88
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x90
	private static DelegateBridge __Hotfix0__OnCurWaveWillFinish; // 0x98
	private static DelegateBridge __Hotfix0__OnShowSelectCardPanel; // 0xa0
	private static DelegateBridge __Hotfix0__SwitchToSelectCardState; // 0xa8
	private static DelegateBridge __Hotfix0_OnGameStarted; // 0xb0
	private static DelegateBridge __Hotfix0_StartRedrawCard; // 0xb8
	private static DelegateBridge __Hotfix0_OnCardRedrawConfirmed; // 0xc0
	private static DelegateBridge __Hotfix0_OnCardSelectConfirmed; // 0xc8
	private static DelegateBridge __Hotfix0_OnCardSelectHiden; // 0xd0
	private static DelegateBridge __Hotfix0_OnCreate; // 0xd8
	private static DelegateBridge __Hotfix0__PreloadAssets; // 0xe0
	private static DelegateBridge __Hotfix0_OnCardMenuShow; // 0xe8
	private static DelegateBridge __Hotfix0_OnCharacterMenuShow; // 0xf0
	private static DelegateBridge __Hotfix0_OnCharacterMenuHide; // 0xf8
	private static DelegateBridge __Hotfix0_ShowUsedCard; // 0x100
	private static DelegateBridge __Hotfix0_ShowPendingCard; // 0x108
	private static DelegateBridge __Hotfix0__SwitchToCardLibraryState; // 0x110
	private static DelegateBridge __Hotfix0_CloseLibraryPanel; // 0x118
	private static DelegateBridge __Hotfix0_ShowLegionWidgetPanel; // 0x120
	private static DelegateBridge _c__Hotfix0_ctor; // 0x128

	public LegionGameMode manager { get; }
	public Boolean isSelectCardShown { get; }

	// RVA: 0x1dc26a4 VA: 0x75943da6a4
	public LegionGameMode get_manager() { }
	// RVA: 0x1dc271c VA: 0x75943da71c
	public Boolean get_isSelectCardShown() { }
	// RVA: 0x1dc2794 VA: 0x75943da794
	public override HookedCharacterInfoSubPanel[] HookCharacterInfoSubPanels() { }
	// RVA: 0x1dc280c VA: 0x75943da80c
	public override Void OnDummyTouchedToTile(Character character, Tile tile) { }
	// RVA: 0x1dc28b4 VA: 0x75943da8b4
	public override Void OnUnitBorn(Unit unit) { }
	// RVA: 0x1dc2950 VA: 0x75943da950
	public override Boolean HookGameReadyStateSwitch() { }
	// RVA: 0x1dc2a18 VA: 0x75943daa18
	public override Void OnSystemMenuCancel() { }
	// RVA: 0x1dc2aec VA: 0x75943daaec
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x1dc2c30 VA: 0x75943dac30
	public override Void OnGameReady() { }
	// RVA: 0x1dc2cc8 VA: 0x75943dacc8
	public override Void OnGameReset(BattleController battleController) { }
	// RVA: 0x1dc2e58 VA: 0x75943dae58
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x1dc3194 VA: 0x75943db194
	public override Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x1dc32f0 VA: 0x75943db2f0
	public Void InitDangerLevel(Single interval, Int32 initLevel) { }
	// RVA: 0x1dc33a4 VA: 0x75943db3a4
	public Void UpdateDangerLevel(Int32 level, Int32 maxLevel, Single progressToNextLevel) { }
	// RVA: 0x1dc3464 VA: 0x75943db464
	public override Void UpdateGameInfo() { }
	// RVA: 0x1dc3594 VA: 0x75943db594
	private Void _OnCurWaveWillFinish(Single showTime) { }
	// RVA: 0x1dc3648 VA: 0x75943db648
	private Void _OnShowSelectCardPanel(Object arg) { }
	// RVA: 0x1dc37e8 VA: 0x75943db7e8
	private Void _SwitchToSelectCardState() { }
	// RVA: 0x1dc3ae4 VA: 0x75943dbae4
	public Void OnGameStarted() { }
	// RVA: 0x1dc3c9c VA: 0x75943dbc9c
	public Void StartRedrawCard() { }
	// RVA: 0x1dc3d70 VA: 0x75943dbd70
	public Void OnCardRedrawConfirmed(List`1 uiCardList) { }
	// RVA: 0x1dc40a0 VA: 0x75943dc0a0
	public Void OnCardSelectConfirmed() { }
	// RVA: 0x1dc41a0 VA: 0x75943dc1a0
	public Void OnCardSelectHiden() { }
	// RVA: 0x1dc4250 VA: 0x75943dc250
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x1dc433c VA: 0x75943dc33c
	private Void _PreloadAssets() { }
	// RVA: 0x1dc47e0 VA: 0x75943dc7e0
	public override Void OnCardMenuShow(Card card) { }
	// RVA: 0x1dc487c VA: 0x75943dc87c
	public override Void OnCharacterMenuShow(Character character) { }
	// RVA: 0x1dc4918 VA: 0x75943dc918
	public override Void OnCharacterMenuHide() { }
	// RVA: 0x1dc499c VA: 0x75943dc99c
	public Void ShowUsedCard() { }
	// RVA: 0x1dc4bb8 VA: 0x75943dcbb8
	public Void ShowPendingCard() { }
	// RVA: 0x1dc4a18 VA: 0x75943dca18
	private Void _SwitchToCardLibraryState(LegionCardLibraryType cardType) { }
	// RVA: 0x1dbfca0 VA: 0x75943d7ca0
	public Void CloseLibraryPanel() { }
	// RVA: 0x1dc3bf8 VA: 0x75943dbbf8
	public Void ShowLegionWidgetPanel(Boolean isShow) { }
	// RVA: 0x1dc4c34 VA: 0x75943dcc34
	public Void .ctor() { }
	// RVA: 0x1dc4d44 VA: 0x75943dcd44
	private static Void .cctor() { }
	// RVA: 0x1dc4db0 VA: 0x75943dcdb0
	private Void <OnGameReset>b__34_0(Object arg) { }
	// RVA: 0x1dc4e24 VA: 0x75943dce24
	private Void <OnGameReset>b__34_1(Object arg) { }
	// RVA: 0x1dc4e28 VA: 0x75943dce28
	private HookedCharacterInfoSubPanel[] <>xLuaBaseProxy_HookCharacterInfoSubPanels() { }
	// RVA: 0x1dc4e30 VA: 0x75943dce30
	private Void <>xLuaBaseProxy_OnDummyTouchedToTile(Character P0, Tile P1) { }
	// RVA: 0x1dc4e38 VA: 0x75943dce38
	private Void <>xLuaBaseProxy_OnUnitBorn(Unit P0) { }
	// RVA: 0x1dc4e40 VA: 0x75943dce40
	private Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch() { }
	// RVA: 0x1dc4e48 VA: 0x75943dce48
	private Void <>xLuaBaseProxy_OnSystemMenuCancel() { }
	// RVA: 0x1dc4e50 VA: 0x75943dce50
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x1dc4e58 VA: 0x75943dce58
	private Void <>xLuaBaseProxy_OnGameReady() { }
	// RVA: 0x1dc4e60 VA: 0x75943dce60
	private Void <>xLuaBaseProxy_OnGameReset(BattleController P0) { }
	// RVA: 0x1dc4e68 VA: 0x75943dce68
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x1dc4e70 VA: 0x75943dce70
	private Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode P0) { }
	// RVA: 0x1dc4e78 VA: 0x75943dce78
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x1dc4e80 VA: 0x75943dce80
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x1dc4e88 VA: 0x75943dce88
	private Void <>xLuaBaseProxy_OnCardMenuShow(Card P0) { }
	// RVA: 0x1dc4e90 VA: 0x75943dce90
	private Void <>xLuaBaseProxy_OnCharacterMenuShow(Character P0) { }
	// RVA: 0x1dc4e98 VA: 0x75943dce98
	private Void <>xLuaBaseProxy_OnCharacterMenuHide() { }
}
```
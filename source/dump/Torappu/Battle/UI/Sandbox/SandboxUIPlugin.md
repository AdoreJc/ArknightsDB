# SandboxUIPlugin

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Sprite _defaultWithdrawBtnSprite`

- `Sprite _buildingWithdrawBtnSprite`

- `Sprite _defaultMenuSysBtnSprite`

- `Button _backpackButton`

- `UIBattleBlurPanel _blurPanel`

- `UIBattleSandboxPausePanel _pausePanel`

- `UIBattleSandboxUICardList _cardListWidget`

- `AnimationWrapper _bagPackAnim`

- `UIBattleSandboxConstruct _constructPlugin`

- `UIBattleSandboxItemNotification itemNotification`

- `SandboxBattleFailedMask _battleFailedMask`

- `SandboxExitBattleDeco _deco`

- `SandboxGameMode m_gameMode`

- `UIBattleSandboxTopBarStatus m_curTopbarStatus`

- `SandboxBattleStyle m_battleStyle`

- `UIBattleSandboxUICardList m_cardListWidget`

- `UIBattleSandboxConstruct m_constructPlugin`

- `SandboxBattleFailedMask m_failedPanel`


## Properties

- `SandboxBattleStyle battleStyle`

- `UIBattleSandboxPausePanel pausePanel`

- `UIBattleSandboxConstruct constructPlugin`

- `UIBattleSandboxUICardList cardListWidget`

- `UIBattleSandboxBagState bagState`


## Methods

- `SandboxBattleStyle get_battleStyle()`

- `UIBattleSandboxPausePanel get_pausePanel()`

- `UIBattleSandboxConstruct get_constructPlugin()`

- `UIBattleSandboxUICardList get_cardListWidget()`

- `UIBattleSandboxBagState get_bagState()`

- `Void OnItemCountChanged(Object)`

- `Void _HookUITopBar()`

- `Void OnBackpackButtonClicked()`

- `Void _PreloadAssets()`

- `Void _RegisterEventListenerWhenInit()`

- `Void _ShowConfirmDialog(Object)`

- `SandboxV2ConfirmDialogConfirmVisualType _RouteConfirmVisualType()`

- `SandboxV2ConfirmDialogThemeType _RouteThemeType()`

- `SandboxV2ConfirmIconType _RouteConfirmIconType()`

- `Void _RouteTitleAndDesc(SandboxInput, out, out)`

- `Void _OnConfirmFinish()`

- `Void _OnConfirmCancel()`

- `Void <OnGameReset>b__38_0(Object)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnGameReset(BattleController)`

- `RectTransform <>xLuaBaseProxy_HookBattleFailedPanelInit()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedPanelShow()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedPanelHide()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnCharacterMenuShow(Character)`

- `Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode)`

- `Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch()`

- `IUICharacterMenuPanel <>xLuaBaseProxy_GetHookUICharacterMenuPanel(Character)`

- `Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam)`

- `Boolean <>xLuaBaseProxy_HookOnBattleFinishServiceStateEnter()`

- `Boolean <>xLuaBaseProxy_HookPauseMask(Boolean)`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class SandboxUIPlugin : Plugin
{
	public static readonly UIStateEnum UI_STATE_BAG; // 0x0
	public static readonly UIStateEnum UI_STATE_SYSTEM_MENU; // 0x4
	private const String ANIM_BAG_ADD; // 0x0
	private UIBattleSandboxStateNode[] _states; // 0x28
	private HookedCharacterInfoSubPanel[] _hookedCharacterInfoSubPanels; // 0x30
	private Sprite _defaultWithdrawBtnSprite; // 0x38
	private Sprite _buildingWithdrawBtnSprite; // 0x40
	private TopBarStatusStyle[] _topBarStatuses; // 0x48
	private MenuBtnStatusStyle[] _menuSystemBtns; // 0x50
	private Sprite _defaultMenuSysBtnSprite; // 0x58
	private Button _backpackButton; // 0x60
	private UIBattleBlurPanel _blurPanel; // 0x68
	private UIBattleSandboxPausePanel _pausePanel; // 0x70
	private UIBattleSandboxUICardList _cardListWidget; // 0x78
	private AnimationWrapper _bagPackAnim; // 0x80
	private UIBattleSandboxConstruct _constructPlugin; // 0x88
	private UIBattleSandboxItemNotification itemNotification; // 0x90
	private SandboxBattleFailedMask _battleFailedMask; // 0x98
	private SandboxExitBattleDeco _deco; // 0xa0
	private SandboxGameMode m_gameMode; // 0xa8
	private UIBattleSandboxTopBarStatus m_curTopbarStatus; // 0xb0
	private SandboxBattleStyle m_battleStyle; // 0xb8
	private UIBattleSandboxUICardList m_cardListWidget; // 0xc0
	private UIBattleSandboxConstruct m_constructPlugin; // 0xc8
	private SandboxBattleFailedMask m_failedPanel; // 0xd0
	private static DelegateBridge __Hotfix0_get_battleStyle; // 0x8
	private static DelegateBridge __Hotfix0_get_pausePanel; // 0x10
	private static DelegateBridge __Hotfix0_get_constructPlugin; // 0x18
	private static DelegateBridge __Hotfix0_get_cardListWidget; // 0x20
	private static DelegateBridge __Hotfix0_get_bagState; // 0x28
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x30
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x38
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelInit; // 0x40
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelShow; // 0x48
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelHide; // 0x50
	private static DelegateBridge __Hotfix0_OnItemCountChanged; // 0x58
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x60
	private static DelegateBridge __Hotfix0__HookUITopBar; // 0x68
	private static DelegateBridge __Hotfix0_OnBackpackButtonClicked; // 0x70
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x78
	private static DelegateBridge __Hotfix0_HookCharacterInfoSubPanels; // 0x80
	private static DelegateBridge __Hotfix0_OnCharacterMenuShow; // 0x88
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x90
	private static DelegateBridge __Hotfix0_HookBattleSystemMenuSwitch; // 0x98
	private static DelegateBridge __Hotfix0_GetHookUICharacterMenuPanel; // 0xa0
	private static DelegateBridge __Hotfix0_HookBattleFailedStateSwitch; // 0xa8
	private static DelegateBridge __Hotfix0_HookOnBattleFinishServiceStateEnter; // 0xb0
	private static DelegateBridge __Hotfix0_HookPauseMask; // 0xb8
	private static DelegateBridge __Hotfix0_OnCreate; // 0xc0
	private static DelegateBridge __Hotfix0__PreloadAssets; // 0xc8
	private static DelegateBridge __Hotfix0__RegisterEventListenerWhenInit; // 0xd0
	private static DelegateBridge __Hotfix0__ShowConfirmDialog; // 0xd8
	private static DelegateBridge __Hotfix0__RouteConfirmVisualType; // 0xe0
	private static DelegateBridge __Hotfix0__RouteThemeType; // 0xe8
	private static DelegateBridge __Hotfix0__RouteConfirmIconType; // 0xf0
	private static DelegateBridge __Hotfix0__RouteTitleAndDesc; // 0xf8
	private static DelegateBridge __Hotfix0__OnConfirmFinish; // 0x100
	private static DelegateBridge __Hotfix0__OnConfirmCancel; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110

	public SandboxBattleStyle battleStyle { get; }
	public UIBattleSandboxPausePanel pausePanel { get; }
	public UIBattleSandboxConstruct constructPlugin { get; }
	public UIBattleSandboxUICardList cardListWidget { get; }
	public UIBattleSandboxBagState bagState { get; }

	// RVA: 0x20c49e0 VA: 0x75946dc9e0
	public SandboxBattleStyle get_battleStyle() { }
	// RVA: 0x20c4a58 VA: 0x75946dca58
	public UIBattleSandboxPausePanel get_pausePanel() { }
	// RVA: 0x20c4ad0 VA: 0x75946dcad0
	public UIBattleSandboxConstruct get_constructPlugin() { }
	// RVA: 0x20c4b48 VA: 0x75946dcb48
	public UIBattleSandboxUICardList get_cardListWidget() { }
	// RVA: 0x20c4bc0 VA: 0x75946dcbc0
	public UIBattleSandboxBagState get_bagState() { }
	// RVA: 0x20c4cc0 VA: 0x75946dccc0
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x20c5704 VA: 0x75946dd704
	public override Void OnGameReset(BattleController battleController) { }
	// RVA: 0x20c5828 VA: 0x75946dd828
	public override RectTransform HookBattleFailedPanelInit() { }
	// RVA: 0x20c58f8 VA: 0x75946dd8f8
	public override Boolean HookBattleFailedPanelShow() { }
	// RVA: 0x20c597c VA: 0x75946dd97c
	public override Boolean HookBattleFailedPanelHide() { }
	// RVA: 0x20c5a00 VA: 0x75946dda00
	public Void OnItemCountChanged(Object arg) { }
	// RVA: 0x20c5b8c VA: 0x75946ddb8c
	public override Void UpdateGameInfo() { }
	// RVA: 0x20c51e4 VA: 0x75946dd1e4
	private Void _HookUITopBar() { }
	// RVA: 0x20c5d24 VA: 0x75946ddd24
	public Void OnBackpackButtonClicked() { }
	// RVA: 0x20c5e08 VA: 0x75946dde08
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x20c5f4c VA: 0x75946ddf4c
	public override HookedCharacterInfoSubPanel[] HookCharacterInfoSubPanels() { }
	// RVA: 0x20c5fc4 VA: 0x75946ddfc4
	public override Void OnCharacterMenuShow(Character character) { }
	// RVA: 0x20c6130 VA: 0x75946de130
	public override Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x20c6288 VA: 0x75946de288
	public override Boolean HookBattleSystemMenuSwitch() { }
	// RVA: 0x20c6374 VA: 0x75946de374
	public override IUICharacterMenuPanel GetHookUICharacterMenuPanel(Character character) { }
	// RVA: 0x20c64a0 VA: 0x75946de4a0
	public override Boolean HookBattleFailedStateSwitch(BattleFailedStateParam param) { }
	// RVA: 0x20c65ec VA: 0x75946de5ec
	public override Boolean HookOnBattleFinishServiceStateEnter() { }
	// RVA: 0x20c6670 VA: 0x75946de670
	public override Boolean HookPauseMask(Boolean isPause) { }
	// RVA: 0x20c6730 VA: 0x75946de730
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x20c67cc VA: 0x75946de7cc
	private Void _PreloadAssets() { }
	// RVA: 0x20c5638 VA: 0x75946dd638
	private Void _RegisterEventListenerWhenInit() { }
	// RVA: 0x20c6970 VA: 0x75946de970
	private Void _ShowConfirmDialog(Object obj) { }
	// RVA: 0x20c7128 VA: 0x75946df128
	private SandboxV2ConfirmDialogConfirmVisualType _RouteConfirmVisualType() { }
	// RVA: 0x20c7018 VA: 0x75946df018
	private SandboxV2ConfirmDialogThemeType _RouteThemeType() { }
	// RVA: 0x20c6ee8 VA: 0x75946deee8
	private SandboxV2ConfirmIconType _RouteConfirmIconType() { }
	// RVA: 0x20c6cc8 VA: 0x75946decc8
	private Void _RouteTitleAndDesc(SandboxInput input, out String title, out String desc) { }
	// RVA: 0x20c71fc VA: 0x75946df1fc
	private Void _OnConfirmFinish() { }
	// RVA: 0x20c7278 VA: 0x75946df278
	private Void _OnConfirmCancel() { }
	// RVA: 0x20c72f4 VA: 0x75946df2f4
	public Void .ctor() { }
	// RVA: 0x20c7374 VA: 0x75946df374
	private static Void .cctor() { }
	// RVA: 0x20c73c4 VA: 0x75946df3c4
	private Void <OnGameReset>b__38_0(Object arg) { }
	// RVA: 0x20c73c8 VA: 0x75946df3c8
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x20c73d0 VA: 0x75946df3d0
	private Void <>xLuaBaseProxy_OnGameReset(BattleController P0) { }
	// RVA: 0x20c73d8 VA: 0x75946df3d8
	private RectTransform <>xLuaBaseProxy_HookBattleFailedPanelInit() { }
	// RVA: 0x20c73e0 VA: 0x75946df3e0
	private Boolean <>xLuaBaseProxy_HookBattleFailedPanelShow() { }
	// RVA: 0x20c73e8 VA: 0x75946df3e8
	private Boolean <>xLuaBaseProxy_HookBattleFailedPanelHide() { }
	// RVA: 0x20c73f0 VA: 0x75946df3f0
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x20c73f8 VA: 0x75946df3f8
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x20c7400 VA: 0x75946df400
	private HookedCharacterInfoSubPanel[] <>xLuaBaseProxy_HookCharacterInfoSubPanels() { }
	// RVA: 0x20c7408 VA: 0x75946df408
	private Void <>xLuaBaseProxy_OnCharacterMenuShow(Character P0) { }
	// RVA: 0x20c7410 VA: 0x75946df410
	private Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode P0) { }
	// RVA: 0x20c7418 VA: 0x75946df418
	private Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch() { }
	// RVA: 0x20c7420 VA: 0x75946df420
	private IUICharacterMenuPanel <>xLuaBaseProxy_GetHookUICharacterMenuPanel(Character P0) { }
	// RVA: 0x20c7428 VA: 0x75946df428
	private Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam P0) { }
	// RVA: 0x20c7434 VA: 0x75946df434
	private Boolean <>xLuaBaseProxy_HookOnBattleFinishServiceStateEnter() { }
	// RVA: 0x20c743c VA: 0x75946df43c
	private Boolean <>xLuaBaseProxy_HookPauseMask(Boolean P0) { }
	// RVA: 0x20c7448 VA: 0x75946df448
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
}
```
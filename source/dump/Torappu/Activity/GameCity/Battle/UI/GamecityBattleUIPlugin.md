# GamecityBattleUIPlugin

**Namespace:** `Torappu.Activity.GameCity.Battle.UI`


## Fields

- `GameCityTopBarPanel _topBarPanel`

- `RectTransform _scorePanelTransform`

- `RectTransform _pauseButtonTransform`

- `RectTransform _speedSwitcherTransform`

- `RectTransform _menuButtonTransform`

- `Button _menuButton`

- `RectTransform _menuPanel`

- `UINumericTextWithoutModifier _extraTextToShow`

- `RectTransform _battleStartPerform`

- `UIAnimationPerform _battleFinishPerform`

- `UIBattleGameCityMinerCharacterMenuPanel _minerCharacterMenuPanel`

- `EmptyWavePlugin m_wavePlugin`

- `GameCityGameMode m_gameMode`

- `UIBattleGameCityMinerCharacterMenuPanel m_minerPanel`

- `Boolean <isQuit>k__BackingField`


## Properties

- `Boolean isQuit`


## Methods

- `Boolean get_isQuit()`

- `Void set_isQuit(Boolean)`

- `Void _InitLayout()`

- `Void SetGameCityScore(Int32)`

- `Void UpgradeRank(Rank, Single)`

- `Void OnWaveStart()`

- `Void OnMenuButtonClick()`

- `Boolean <>xLuaBaseProxy_get_needPerspectiveAlwaysOn()`

- `Void <>xLuaBaseProxy_OnGameReady()`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Boolean <>xLuaBaseProxy_CanPressBackButton()`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_ShowGameModeText(Int32, Transform, Color)`

- `Void <>xLuaBaseProxy_UpdateDisableMask(BattleFunctionDisableMask)`

- `Boolean <>xLuaBaseProxy_HookBattleAccomplishPerform(out)`

- `Boolean <>xLuaBaseProxy_HookConfirmFinish(Action)`

- `Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam)`

- `Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch()`

- `Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode)`

- `IUICharacterMenuPanel <>xLuaBaseProxy_GetHookUICharacterMenuPanel(Character)`

- `Boolean <>xLuaBaseProxy_HookPredefinedUILocation(Camera, PredefinedLocation, out)`

- `Boolean <>xLuaBaseProxy_HookShowCharacter(Character)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.GameCity.Battle.UI
public class GamecityBattleUIPlugin : Plugin
{
	public static readonly UIStateEnum ON_GAME_CITY_START_STATE; // 0x0
	public static readonly UIStateEnum ON_GAME_CITY_WAVE_STATE; // 0x4
	public static readonly UIStateEnum ON_GAME_CITY_SYSTEM_MENU; // 0x8
	private UIStateNode[] _states; // 0x28
	private GameCityTopBarPanel _topBarPanel; // 0x30
	private RectTransform _scorePanelTransform; // 0x38
	private RectTransform _pauseButtonTransform; // 0x40
	private RectTransform _speedSwitcherTransform; // 0x48
	private RectTransform _menuButtonTransform; // 0x50
	private Button _menuButton; // 0x58
	private RectTransform _menuPanel; // 0x60
	private UINumericTextWithoutModifier _extraTextToShow; // 0x68
	private RectTransform _battleStartPerform; // 0x70
	private UIAnimationPerform _battleFinishPerform; // 0x78
	private UIBattleGameCityMinerCharacterMenuPanel _minerCharacterMenuPanel; // 0x80
	private EmptyWavePlugin m_wavePlugin; // 0x88
	private GameCityGameMode m_gameMode; // 0x90
	private UIBattleGameCityMinerCharacterMenuPanel m_minerPanel; // 0x98
	private Boolean <isQuit>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_isQuit; // 0x10
	private static DelegateBridge __Hotfix0_set_isQuit; // 0x18
	private static DelegateBridge __Hotfix0_get_needPerspectiveAlwaysOn; // 0x20
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x28
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x30
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x38
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x40
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x48
	private static DelegateBridge __Hotfix0_CanPressBackButton; // 0x50
	private static DelegateBridge __Hotfix0_OnCreate; // 0x58
	private static DelegateBridge __Hotfix0_ShowGameModeText; // 0x60
	private static DelegateBridge __Hotfix0_UpdateDisableMask; // 0x68
	private static DelegateBridge __Hotfix0_HookBattleAccomplishPerform; // 0x70
	private static DelegateBridge __Hotfix0_HookConfirmFinish; // 0x78
	private static DelegateBridge __Hotfix0_HookBattleAccomplishedStateSwitch; // 0x80
	private static DelegateBridge __Hotfix0_HookBattleFailedStateSwitch; // 0x88
	private static DelegateBridge __Hotfix0_HookBattleSystemMenuSwitch; // 0x90
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x98
	private static DelegateBridge __Hotfix0_GetHookUICharacterMenuPanel; // 0xa0
	private static DelegateBridge __Hotfix0_HookPredefinedUILocation; // 0xa8
	private static DelegateBridge __Hotfix0_HookShowCharacter; // 0xb0
	private static DelegateBridge __Hotfix0__InitLayout; // 0xb8
	private static DelegateBridge __Hotfix0_SetGameCityScore; // 0xc0
	private static DelegateBridge __Hotfix0_UpgradeRank; // 0xc8
	private static DelegateBridge __Hotfix0_OnWaveStart; // 0xd0
	private static DelegateBridge __Hotfix0_OnMenuButtonClick; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0

	public Boolean isQuit { get; set; }
	public override Boolean needPerspectiveAlwaysOn { get; }

	// RVA: 0x33e4c74 VA: 0x75959fcc74
	public Boolean get_isQuit() { }
	// RVA: 0x33e4cec VA: 0x75959fccec
	public Void set_isQuit(Boolean value) { }
	// RVA: 0x33e4d7c VA: 0x75959fcd7c
	public override Boolean get_needPerspectiveAlwaysOn() { }
	// RVA: 0x33e4df4 VA: 0x75959fcdf4
	public override Void OnGameReady() { }
	// RVA: 0x33e50a4 VA: 0x75959fd0a4
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x33e54d0 VA: 0x75959fd4d0
	public override Void OnGameStart() { }
	// RVA: 0x33e55b4 VA: 0x75959fd5b4
	public override Void UpdateGameInfo() { }
	// RVA: 0x33e5a24 VA: 0x75959fda24
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x33e5b68 VA: 0x75959fdb68
	public override Boolean CanPressBackButton() { }
	// RVA: 0x33e5ca4 VA: 0x75959fdca4
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x33e5f90 VA: 0x75959fdf90
	public override Void ShowGameModeText(Int32 value, Transform spawnPoint, Color color) { }
	// RVA: 0x33e61b8 VA: 0x75959fe1b8
	public override Void UpdateDisableMask(BattleFunctionDisableMask mask) { }
	// RVA: 0x33e6378 VA: 0x75959fe378
	public override Boolean HookBattleAccomplishPerform(out UIAnimationPerform perform) { }
	// RVA: 0x33e6414 VA: 0x75959fe414
	public override Boolean HookConfirmFinish(Action finishCallback) { }
	// RVA: 0x33e65a8 VA: 0x75959fe5a8
	public override Boolean HookBattleAccomplishedStateSwitch() { }
	// RVA: 0x33e665c VA: 0x75959fe65c
	public override Boolean HookBattleFailedStateSwitch(BattleFailedStateParam param) { }
	// RVA: 0x33e6704 VA: 0x75959fe704
	public override Boolean HookBattleSystemMenuSwitch() { }
	// RVA: 0x33e67f0 VA: 0x75959fe7f0
	public override Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x33e69a0 VA: 0x75959fe9a0
	public override IUICharacterMenuPanel GetHookUICharacterMenuPanel(Character character) { }
	// RVA: 0x33e6a60 VA: 0x75959fea60
	public override Boolean HookPredefinedUILocation(Camera uiCam, PredefinedLocation location, out Vector3 worldPos) { }
	// RVA: 0x33e6c4c VA: 0x75959fec4c
	public override Boolean HookShowCharacter(Character character) { }
	// RVA: 0x33e5d40 VA: 0x75959fdd40
	private Void _InitLayout() { }
	// RVA: 0x33e6d24 VA: 0x75959fed24
	public Void SetGameCityScore(Int32 value) { }
	// RVA: 0x33e6f14 VA: 0x75959fef14
	public Void UpgradeRank(Rank rank, Single score) { }
	// RVA: 0x33e710c VA: 0x75959ff10c
	public Void OnWaveStart() { }
	// RVA: 0x33e7270 VA: 0x75959ff270
	public Void OnMenuButtonClick() { }
	// RVA: 0x33e7308 VA: 0x75959ff308
	public Void .ctor() { }
	// RVA: 0x33e7470 VA: 0x75959ff470
	private static Void .cctor() { }
	// RVA: 0x33e74c8 VA: 0x75959ff4c8
	private Boolean <>xLuaBaseProxy_get_needPerspectiveAlwaysOn() { }
	// RVA: 0x33e74d0 VA: 0x75959ff4d0
	private Void <>xLuaBaseProxy_OnGameReady() { }
	// RVA: 0x33e74d8 VA: 0x75959ff4d8
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x33e74e0 VA: 0x75959ff4e0
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x33e74e8 VA: 0x75959ff4e8
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x33e74f0 VA: 0x75959ff4f0
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x33e74f8 VA: 0x75959ff4f8
	private Boolean <>xLuaBaseProxy_CanPressBackButton() { }
	// RVA: 0x33e7500 VA: 0x75959ff500
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x33e7508 VA: 0x75959ff508
	private Void <>xLuaBaseProxy_ShowGameModeText(Int32 P0, Transform P1, Color P2) { }
	// RVA: 0x33e7510 VA: 0x75959ff510
	private Void <>xLuaBaseProxy_UpdateDisableMask(BattleFunctionDisableMask P0) { }
	// RVA: 0x33e7518 VA: 0x75959ff518
	private Boolean <>xLuaBaseProxy_HookBattleAccomplishPerform(out UIAnimationPerform P0) { }
	// RVA: 0x33e7520 VA: 0x75959ff520
	private Boolean <>xLuaBaseProxy_HookConfirmFinish(Action P0) { }
	// RVA: 0x33e7528 VA: 0x75959ff528
	private Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch() { }
	// RVA: 0x33e7530 VA: 0x75959ff530
	private Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam P0) { }
	// RVA: 0x33e753c VA: 0x75959ff53c
	private Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch() { }
	// RVA: 0x33e7544 VA: 0x75959ff544
	private Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode P0) { }
	// RVA: 0x33e754c VA: 0x75959ff54c
	private IUICharacterMenuPanel <>xLuaBaseProxy_GetHookUICharacterMenuPanel(Character P0) { }
	// RVA: 0x33e7554 VA: 0x75959ff554
	private Boolean <>xLuaBaseProxy_HookPredefinedUILocation(Camera P0, PredefinedLocation P1, out Vector3 P2) { }
	// RVA: 0x33e755c VA: 0x75959ff55c
	private Boolean <>xLuaBaseProxy_HookShowCharacter(Character P0) { }
}
```
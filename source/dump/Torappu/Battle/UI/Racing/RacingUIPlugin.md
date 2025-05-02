# RacingUIPlugin

**Namespace:** `Torappu.Battle.UI.Racing`


## Fields

- `UIAtlasObject _racingBattleAtlas`

- `GameObject _battleTransitionHolder`

- `Image _battleTransitionBgImage`

- `UIAnimationLocation _gameFinishAnim`

- `GameObject _racingInfoHolder`

- `Slider _sliderRacingProgress`

- `Transform _otherPlayerHandleHolder`

- `Transform _circlesHolder`

- `String _unfinishedCircleImg`

- `String _finishedCircleImg`

- `Image _playerIcon`

- `Text _textMaxPlayerNum`

- `Text _textPlayerRanking`

- `Text _textRacingTime`

- `UIAnimationLocation _topbarShowAnim`

- `Sprite _btnSystemMenu`

- `Button _racingItemButton`

- `UIAnimationLocation _useItemAnim`

- `UIAnimationLocation _gainItemAnim`

- `UIAtlasImage _itemIcon`

- `Text _itemName`

- `UIAtlasImage _invalidItemImage`

- `GameObject _validItemHolder`

- `UISwitchToggle _cameraModeButton`

- `Boolean m_racingStarted`

- `RacingGameMode m_gameMode`

- `FP m_realRacingTime`

- `Tween m_racingUseItemTween`

- `Tween m_racingGainItemTween`

- `SandboxV2RacingItemInfo m_lastItemInfo`


## Methods

- `Void OnStartCountdownComplete()`

- `Tween OnFinishCountdownComplete()`

- `Sprite _GetPlayerInsectIcon(String)`

- `String _GetRacerItemIdByRacerId(String, SandboxV2Data)`

- `Void _InitRacingTopbar()`

- `Void _UpdateTopbarInfo()`

- `Void _UpdateButtons()`

- `Void _ActiveButtons(Boolean)`

- `Void _OnGainRacingItem(String, String)`

- `Void OnRacingItemButtonClicked()`

- `Void OnCameraModeButtonClicked()`

- `Void _RegisterEventListenerWhenInit()`

- `Void _ShowExitConfirmDialog(Object)`

- `Void _OnConfirmFinish()`

- `Void _OnConfirmCancel()`

- `Void <_OnGainRacingItem>b__58_0()`

- `Void <_OnGainRacingItem>b__58_1()`

- `Void <OnRacingItemButtonClicked>b__59_0()`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnGameReady()`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Boolean <>xLuaBaseProxy_CanPressBackButton()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch()`

- `Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Racing
public class RacingUIPlugin : Plugin
{
	public static readonly UIStateEnum RACING_START_COUNTDOWN_STATE; // 0x0
	public static readonly UIStateEnum RACING_FINISH_COUNTDOWN_STATE; // 0x4
	public static readonly UIStateEnum RACING_SYSTEM_MENU_STATE; // 0x8
	private const String OTHER_PLAYER_HANDLE_PATH; // 0x0
	private const String CIRCLE_PREFAB_PATH; // 0x0
	private const String INIT_RACING_TIME; // 0x0
	private const Single IMAGE_FADE_TIME; // 0x0
	private const Single DARK_BACKGROUND_ALPHA; // 0x0
	private const Single INVALID_ITEM_IMAGE_FADE_DELAY_TIME; // 0x0
	private UIStateNode[] _states; // 0x28
	private UIAtlasObject _racingBattleAtlas; // 0x30
	private GameObject _battleTransitionHolder; // 0x38
	private Image _battleTransitionBgImage; // 0x40
	private UIAnimationLocation _gameFinishAnim; // 0x48
	private GameObject _racingInfoHolder; // 0x58
	private Slider _sliderRacingProgress; // 0x60
	private Transform _otherPlayerHandleHolder; // 0x68
	private Transform _circlesHolder; // 0x70
	private String _unfinishedCircleImg; // 0x78
	private String _finishedCircleImg; // 0x80
	private Image _playerIcon; // 0x88
	private Text _textMaxPlayerNum; // 0x90
	private Text _textPlayerRanking; // 0x98
	private Text _textRacingTime; // 0xa0
	private UIAnimationLocation _topbarShowAnim; // 0xa8
	private Sprite _btnSystemMenu; // 0xb8
	private Button _racingItemButton; // 0xc0
	private UIAnimationLocation _useItemAnim; // 0xc8
	private UIAnimationLocation _gainItemAnim; // 0xd8
	private UIAtlasImage _itemIcon; // 0xe8
	private Text _itemName; // 0xf0
	private UIAtlasImage _invalidItemImage; // 0xf8
	private GameObject _validItemHolder; // 0x100
	private UISwitchToggle _cameraModeButton; // 0x108
	private Boolean m_racingStarted; // 0x110
	private RacingGameMode m_gameMode; // 0x118
	private List`1 m_circles; // 0x120
	private Dictionary`2 m_racingHandleDict; // 0x128
	private FP m_realRacingTime; // 0x130
	private Tween m_racingUseItemTween; // 0x138
	private Tween m_racingGainItemTween; // 0x140
	private SandboxV2RacingItemInfo m_lastItemInfo; // 0x148
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x10
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x18
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x20
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x28
	private static DelegateBridge __Hotfix0_CanPressBackButton; // 0x30
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x38
	private static DelegateBridge __Hotfix0_HookBattleAccomplishedStateSwitch; // 0x40
	private static DelegateBridge __Hotfix0_HookBattleSystemMenuSwitch; // 0x48
	private static DelegateBridge __Hotfix0_OnStartCountdownComplete; // 0x50
	private static DelegateBridge __Hotfix0_OnFinishCountdownComplete; // 0x58
	private static DelegateBridge __Hotfix0__GetPlayerInsectIcon; // 0x60
	private static DelegateBridge __Hotfix0__GetRacerItemIdByRacerId; // 0x68
	private static DelegateBridge __Hotfix0__InitRacingTopbar; // 0x70
	private static DelegateBridge __Hotfix0__UpdateTopbarInfo; // 0x78
	private static DelegateBridge __Hotfix0__UpdateButtons; // 0x80
	private static DelegateBridge __Hotfix0__ActiveButtons; // 0x88
	private static DelegateBridge __Hotfix0__OnGainRacingItem; // 0x90
	private static DelegateBridge __Hotfix0_OnRacingItemButtonClicked; // 0x98
	private static DelegateBridge __Hotfix0_OnCameraModeButtonClicked; // 0xa0
	private static DelegateBridge __Hotfix0__RegisterEventListenerWhenInit; // 0xa8
	private static DelegateBridge __Hotfix0__ShowExitConfirmDialog; // 0xb0
	private static DelegateBridge __Hotfix0__OnConfirmFinish; // 0xb8
	private static DelegateBridge __Hotfix0__OnConfirmCancel; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8


	// RVA: 0x20f244c VA: 0x759470a44c
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x20f26cc VA: 0x759470a6cc
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x20f2810 VA: 0x759470a810
	public override Void OnGameReady() { }
	// RVA: 0x20f2aa8 VA: 0x759470aaa8
	public override Void OnGameStart() { }
	// RVA: 0x20f2b7c VA: 0x759470ab7c
	public override Boolean CanPressBackButton() { }
	// RVA: 0x20f2cb8 VA: 0x759470acb8
	public override Void UpdateGameInfo() { }
	// RVA: 0x20f3720 VA: 0x759470b720
	public override Boolean HookBattleAccomplishedStateSwitch() { }
	// RVA: 0x20f37d8 VA: 0x759470b7d8
	public override Boolean HookBattleSystemMenuSwitch() { }
	// RVA: 0x20f1afc VA: 0x7594709afc
	public Void OnStartCountdownComplete() { }
	// RVA: 0x20f1038 VA: 0x7594709038
	public Tween OnFinishCountdownComplete() { }
	// RVA: 0x20f3ffc VA: 0x759470bffc
	private Sprite _GetPlayerInsectIcon(String racerId) { }
	// RVA: 0x20f41d4 VA: 0x759470c1d4
	private String _GetRacerItemIdByRacerId(String racerId, SandboxV2Data dataTable) { }
	// RVA: 0x20f38b4 VA: 0x759470b8b4
	private Void _InitRacingTopbar() { }
	// RVA: 0x20f2d44 VA: 0x759470ad44
	private Void _UpdateTopbarInfo() { }
	// RVA: 0x20f348c VA: 0x759470b48c
	private Void _UpdateButtons() { }
	// RVA: 0x20f2918 VA: 0x759470a918
	private Void _ActiveButtons(Boolean value) { }
	// RVA: 0x20f4314 VA: 0x759470c314
	private Void _OnGainRacingItem(String itemId, String itemName) { }
	// RVA: 0x20f4590 VA: 0x759470c590
	public Void OnRacingItemButtonClicked() { }
	// RVA: 0x20f47c0 VA: 0x759470c7c0
	public Void OnCameraModeButtonClicked() { }
	// RVA: 0x20f2600 VA: 0x759470a600
	private Void _RegisterEventListenerWhenInit() { }
	// RVA: 0x20f4940 VA: 0x759470c940
	private Void _ShowExitConfirmDialog(Object obj) { }
	// RVA: 0x20f4c44 VA: 0x759470cc44
	private Void _OnConfirmFinish() { }
	// RVA: 0x20f4cc0 VA: 0x759470ccc0
	private Void _OnConfirmCancel() { }
	// RVA: 0x20f4d3c VA: 0x759470cd3c
	public Void .ctor() { }
	// RVA: 0x20f4ed0 VA: 0x759470ced0
	private static Void .cctor() { }
	// RVA: 0x20f4f28 VA: 0x759470cf28
	private Void <_OnGainRacingItem>b__58_0() { }
	// RVA: 0x20f4f50 VA: 0x759470cf50
	private Void <_OnGainRacingItem>b__58_1() { }
	// RVA: 0x20f4f64 VA: 0x759470cf64
	private Void <OnRacingItemButtonClicked>b__59_0() { }
	// RVA: 0x20f4f90 VA: 0x759470cf90
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x20f4f98 VA: 0x759470cf98
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x20f4fa0 VA: 0x759470cfa0
	private Void <>xLuaBaseProxy_OnGameReady() { }
	// RVA: 0x20f4fa8 VA: 0x759470cfa8
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x20f4fb0 VA: 0x759470cfb0
	private Boolean <>xLuaBaseProxy_CanPressBackButton() { }
	// RVA: 0x20f4fb8 VA: 0x759470cfb8
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x20f4fc0 VA: 0x759470cfc0
	private Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch() { }
	// RVA: 0x20f4fc8 VA: 0x759470cfc8
	private Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch() { }
}
```
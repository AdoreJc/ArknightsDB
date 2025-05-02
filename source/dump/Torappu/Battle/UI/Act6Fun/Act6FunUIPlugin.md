# Act6FunUIPlugin

**Namespace:** `Torappu.Battle.UI.Act6Fun`


## Fields

- `Act6FunUIDynPosJoystickHost _joystickHost`

- `ETCJoystick _joystick`

- `RectTransform _rectTransformArrow`

- `CanvasGroup _canvasGroupArrow`

- `Single _arrowRotationOffset`

- `Text _coinPanelText`

- `AnimationWrapper _gainCoinAnimWrapper`

- `String _gainCoinClipName`

- `GameObject _gainCoinHolder`

- `GameObject _feverEffectHolder`

- `Text _timerText`

- `UIUnitHUD _mainEnemyHud`

- `UIAnimationPerform _accomplishedPerform`

- `CanvasGroup _canvasGroupInCombatBanner`

- `FadeSwitchTween m_arrowFadeTween`

- `FadeSwitchTween m_panelInCombatFadeTween`

- `Int32 m_oldCoinCnt`

- `Int32 m_oldPlayTime`


## Properties

- `Act6FunGameMode gameMode`


## Methods

- `Act6FunGameMode get_gameMode()`

- `Void Update()`

- `Void _ShowOrHideArrow(Boolean)`

- `Vector2 GetDirectionInput()`

- `Boolean _CheckInputDisabled()`

- `Vector2 _GetJoystickAxis()`

- `Void _UpdateCoinPanel(Boolean)`

- `Void _UpdateTimerPanel(Boolean)`

- `Void _ToggleInCombatPanel(Boolean)`

- `Void SetEnemyBlocked(Boolean)`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Boolean <>xLuaBaseProxy_HookBattleAccomplishPerform(out)`

- `Boolean <>xLuaBaseProxy_HookGameStartStateSwitch()`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnFixedUpdate(FP)`

- `Void <>xLuaBaseProxy_OnCharacterMenuShow(Character)`

- `Void <>xLuaBaseProxy_OnCharacterMenuHide()`

- `Boolean <>xLuaBaseProxy_HookPauseMask(Boolean)`

- `Boolean <>xLuaBaseProxy_HookUnitHud(Unit, out)`

- `Boolean <>xLuaBaseProxy_HookBattleFailedTips(Int32, out)`

- `Void <>xLuaBaseProxy_HookBattleData(BattleData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Act6Fun
public class Act6FunUIPlugin : Plugin
{
	private const String DISABLE_JOYSTICK_KEY_PAUSE; // 0x0
	private const String DISABLE_JOYSTICK_KEY_CHAR_MENU; // 0x0
	private const String TIMER_FORMAT; // 0x0
	public const Single SHOW_IN_COMBAT_BANNER_DURATION; // 0x0
	public static readonly UIStateEnum UI_STATE_BATTLE_START; // 0x0
	private Act6FunUIDynPosJoystickHost _joystickHost; // 0x28
	private ETCJoystick _joystick; // 0x30
	private RectTransform _rectTransformArrow; // 0x38
	private CanvasGroup _canvasGroupArrow; // 0x40
	private Single _arrowRotationOffset; // 0x48
	private Text _coinPanelText; // 0x50
	private AnimationWrapper _gainCoinAnimWrapper; // 0x58
	private String _gainCoinClipName; // 0x60
	private GameObject _gainCoinHolder; // 0x68
	private GameObject _feverEffectHolder; // 0x70
	private Text _timerText; // 0x78
	private UIUnitHUD _mainEnemyHud; // 0x80
	private List`1 _states; // 0x88
	private UIAnimationPerform _accomplishedPerform; // 0x90
	private String[] _failedPanelTipDescKeys; // 0x98
	private CanvasGroup _canvasGroupInCombatBanner; // 0xa0
	private FadeSwitchTween m_arrowFadeTween; // 0xa8
	private FadeSwitchTween m_panelInCombatFadeTween; // 0xb0
	private Int32 m_oldCoinCnt; // 0xb8
	private Int32 m_oldPlayTime; // 0xbc
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__ShowOrHideArrow; // 0x18
	private static DelegateBridge __Hotfix0_GetDirectionInput; // 0x20
	private static DelegateBridge __Hotfix0__CheckInputDisabled; // 0x28
	private static DelegateBridge __Hotfix0__GetJoystickAxis; // 0x30
	private static DelegateBridge __Hotfix0__UpdateCoinPanel; // 0x38
	private static DelegateBridge __Hotfix0__UpdateTimerPanel; // 0x40
	private static DelegateBridge __Hotfix0__ToggleInCombatPanel; // 0x48
	private static DelegateBridge __Hotfix0_OnCreate; // 0x50
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x58
	private static DelegateBridge __Hotfix0_HookBattleAccomplishPerform; // 0x60
	private static DelegateBridge __Hotfix0_HookGameStartStateSwitch; // 0x68
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x70
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x78
	private static DelegateBridge __Hotfix0_OnCharacterMenuShow; // 0x80
	private static DelegateBridge __Hotfix0_OnCharacterMenuHide; // 0x88
	private static DelegateBridge __Hotfix0_HookPauseMask; // 0x90
	private static DelegateBridge __Hotfix0_HookUnitHud; // 0x98
	private static DelegateBridge __Hotfix0_HookBattleFailedTips; // 0xa0
	private static DelegateBridge __Hotfix0_HookBattleData; // 0xa8
	private static DelegateBridge __Hotfix0_SetEnemyBlocked; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	private Act6FunGameMode gameMode { get; }

	// RVA: 0x20f5760 VA: 0x759470d760
	private Act6FunGameMode get_gameMode() { }
	// RVA: 0x20f5848 VA: 0x759470d848
	private Void Update() { }
	// RVA: 0x20f5ae8 VA: 0x759470dae8
	private Void _ShowOrHideArrow(Boolean isShow) { }
	// RVA: 0x20f5bf4 VA: 0x759470dbf4
	public Vector2 GetDirectionInput() { }
	// RVA: 0x20f5e24 VA: 0x759470de24
	private Boolean _CheckInputDisabled() { }
	// RVA: 0x20f59e0 VA: 0x759470d9e0
	private Vector2 _GetJoystickAxis() { }
	// RVA: 0x20f5f18 VA: 0x759470df18
	private Void _UpdateCoinPanel(Boolean isInit) { }
	// RVA: 0x20f6104 VA: 0x759470e104
	private Void _UpdateTimerPanel(Boolean isInit) { }
	// RVA: 0x20f62b8 VA: 0x759470e2b8
	private Void _ToggleInCombatPanel(Boolean isShow) { }
	// RVA: 0x20f642c VA: 0x759470e42c
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x20f6544 VA: 0x759470e544
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x20f669c VA: 0x759470e69c
	public override Boolean HookBattleAccomplishPerform(out UIAnimationPerform perform) { }
	// RVA: 0x20f6738 VA: 0x759470e738
	public override Boolean HookGameStartStateSwitch() { }
	// RVA: 0x20f6800 VA: 0x759470e800
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x20f68d0 VA: 0x759470e8d0
	public override Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20f697c VA: 0x759470e97c
	public override Void OnCharacterMenuShow(Character character) { }
	// RVA: 0x20f6bf0 VA: 0x759470ebf0
	public override Void OnCharacterMenuHide() { }
	// RVA: 0x20f6c8c VA: 0x759470ec8c
	public override Boolean HookPauseMask(Boolean isPause) { }
	// RVA: 0x20f6d50 VA: 0x759470ed50
	public override Boolean HookUnitHud(Unit unit, out UIUnitHUD hud) { }
	// RVA: 0x20f6e50 VA: 0x759470ee50
	public override Boolean HookBattleFailedTips(Int32 tipCnt, out TipData[] tipData) { }
	// RVA: 0x20f70e0 VA: 0x759470f0e0
	public override Void HookBattleData(BattleData battleData) { }
	// RVA: 0x20f71d4 VA: 0x759470f1d4
	public Void SetEnemyBlocked(Boolean isDisable) { }
	// RVA: 0x20f7264 VA: 0x759470f264
	public Void .ctor() { }
	// RVA: 0x20f72e4 VA: 0x759470f2e4
	private static Void .cctor() { }
	// RVA: 0x20f7330 VA: 0x759470f330
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x20f7338 VA: 0x759470f338
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x20f7340 VA: 0x759470f340
	private Boolean <>xLuaBaseProxy_HookBattleAccomplishPerform(out UIAnimationPerform P0) { }
	// RVA: 0x20f7348 VA: 0x759470f348
	private Boolean <>xLuaBaseProxy_HookGameStartStateSwitch() { }
	// RVA: 0x20f7350 VA: 0x759470f350
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x20f7358 VA: 0x759470f358
	private Void <>xLuaBaseProxy_OnFixedUpdate(FP P0) { }
	// RVA: 0x20f7360 VA: 0x759470f360
	private Void <>xLuaBaseProxy_OnCharacterMenuShow(Character P0) { }
	// RVA: 0x20f7368 VA: 0x759470f368
	private Void <>xLuaBaseProxy_OnCharacterMenuHide() { }
	// RVA: 0x20f7370 VA: 0x759470f370
	private Boolean <>xLuaBaseProxy_HookPauseMask(Boolean P0) { }
	// RVA: 0x20f737c VA: 0x759470f37c
	private Boolean <>xLuaBaseProxy_HookUnitHud(Unit P0, out UIUnitHUD P1) { }
	// RVA: 0x20f7384 VA: 0x759470f384
	private Boolean <>xLuaBaseProxy_HookBattleFailedTips(Int32 P0, out TipData[] P1) { }
	// RVA: 0x20f738c VA: 0x759470f38c
	private Void <>xLuaBaseProxy_HookBattleData(BattleData P0) { }
}
```
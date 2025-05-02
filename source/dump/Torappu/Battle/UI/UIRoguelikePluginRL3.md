# UIRoguelikePluginRL3

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIRoguelikeBattleFailedMask _battleFailedMaskPrefab`

- `UIRoguelikeBattleFailedMask _battleFailedMaskPrefab2`

- `GameObject _bossHudHolder`

- `UIAtlasImage _imageBossSkillReady`

- `UIBossHudRL3 _bossLeftHud`

- `UIBossHudRL3 _bossRightHud`

- `UITopbarStatusRL3 _UITopbarStatusRL3`

- `UITopbarStatusRL3 _UITopbarStatusWithExp`

- `UIEmergencyBattleToastPanelRL3 _emergencyBattletoastPrefab`

- `UIEmergencyBattleToastPanelRL3 m_toast`

- `UITopbarStatusRL3 m_currentStatus`

- `UIRoguelikeBattleFailedMask m_failedPanel`

- `Boolean hideUILifePoint`

- `RoguelikeGameMode m_gameMode`

- `Boolean m_isSpecialExpStyle`

- `Boolean m_isFailProtect`

- `Single m_defaultBossReadyAlpha`


## Properties

- `UIBossHudRL3 bossLeftHud`

- `UIBossHudRL3 bossRightHud`


## Methods

- `UIBossHudRL3 get_bossLeftHud()`

- `UIBossHudRL3 get_bossRightHud()`

- `Void _InitTopBar()`

- `Void _InitFailedPanel()`

- `Void _InitBossHud()`

- `Void _UpdateBossHudInfo()`

- `Void _StartBossHudFadeInTweenAnim()`

- `Void OnBossSkillReady()`

- `RoguelikeTopicMode _GetSpecialTopicMode()`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch()`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_HookConfirmFinish(Action)`

- `RectTransform <>xLuaBaseProxy_HookBattleFailedPanelInit()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedPanelShow()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedPanelHide()`

- `Boolean <>xLuaBaseProxy_HookPredefinedUILocation(Camera, PredefinedLocation, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIRoguelikePluginRL3 : Plugin
{
	private const Single FADE_TIME; // 0x0
	private const Single BLINK_TIME; // 0x0
	private UIRoguelikeBattleFailedMask _battleFailedMaskPrefab; // 0x28
	private UIRoguelikeBattleFailedMask _battleFailedMaskPrefab2; // 0x30
	private GameObject _bossHudHolder; // 0x38
	private UIAtlasImage _imageBossSkillReady; // 0x40
	private UIBossHudRL3 _bossLeftHud; // 0x48
	private UIBossHudRL3 _bossRightHud; // 0x50
	private UITopbarStatusRL3 _UITopbarStatusRL3; // 0x58
	private UITopbarStatusRL3 _UITopbarStatusWithExp; // 0x60
	private UIEmergencyBattleToastPanelRL3 _emergencyBattletoastPrefab; // 0x68
	private UIEmergencyBattleToastPanelRL3 m_toast; // 0x70
	private UITopbarStatusRL3 m_currentStatus; // 0x78
	private UIRoguelikeBattleFailedMask m_failedPanel; // 0x80
	public Boolean hideUILifePoint; // 0x88
	private RoguelikeGameMode m_gameMode; // 0x90
	private Boolean m_isSpecialExpStyle; // 0x98
	private Boolean m_isFailProtect; // 0x99
	private Single m_defaultBossReadyAlpha; // 0x9c
	private static DelegateBridge __Hotfix0_get_bossLeftHud; // 0x0
	private static DelegateBridge __Hotfix0_get_bossRightHud; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x18
	private static DelegateBridge __Hotfix0_HookGameReadyStateSwitch; // 0x20
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x28
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x30
	private static DelegateBridge __Hotfix0_HookConfirmFinish; // 0x38
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelInit; // 0x40
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelShow; // 0x48
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelHide; // 0x50
	private static DelegateBridge __Hotfix0__InitTopBar; // 0x58
	private static DelegateBridge __Hotfix0__InitFailedPanel; // 0x60
	private static DelegateBridge __Hotfix0__InitBossHud; // 0x68
	private static DelegateBridge __Hotfix0__UpdateBossHudInfo; // 0x70
	private static DelegateBridge __Hotfix0__StartBossHudFadeInTweenAnim; // 0x78
	private static DelegateBridge __Hotfix0_OnBossSkillReady; // 0x80
	private static DelegateBridge __Hotfix0_HookPredefinedUILocation; // 0x88
	private static DelegateBridge __Hotfix0__GetSpecialTopicMode; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public UIBossHudRL3 bossLeftHud { get; }
	public UIBossHudRL3 bossRightHud { get; }

	// RVA: 0x2075eb4 VA: 0x759468deb4
	public UIBossHudRL3 get_bossLeftHud() { }
	// RVA: 0x2075f1c VA: 0x759468df1c
	public UIBossHudRL3 get_bossRightHud() { }
	// RVA: 0x2075f84 VA: 0x759468df84
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x2076268 VA: 0x759468e268
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x207655c VA: 0x759468e55c
	public override Boolean HookGameReadyStateSwitch() { }
	// RVA: 0x2076694 VA: 0x759468e694
	public override Void OnGameStart() { }
	// RVA: 0x20767dc VA: 0x759468e7dc
	public override Void UpdateGameInfo() { }
	// RVA: 0x2076aa0 VA: 0x759468eaa0
	public override Boolean HookConfirmFinish(Action finishCallback) { }
	// RVA: 0x2076c44 VA: 0x759468ec44
	public override RectTransform HookBattleFailedPanelInit() { }
	// RVA: 0x2076cbc VA: 0x759468ecbc
	public override Boolean HookBattleFailedPanelShow() { }
	// RVA: 0x2076e08 VA: 0x759468ee08
	public override Boolean HookBattleFailedPanelHide() { }
	// RVA: 0x2076448 VA: 0x759468e448
	private Void _InitTopBar() { }
	// RVA: 0x20760f0 VA: 0x759468e0f0
	private Void _InitFailedPanel() { }
	// RVA: 0x20761b0 VA: 0x759468e1b0
	private Void _InitBossHud() { }
	// RVA: 0x207698c VA: 0x759468e98c
	private Void _UpdateBossHudInfo() { }
	// RVA: 0x2077028 VA: 0x759468f028
	private Void _StartBossHudFadeInTweenAnim() { }
	// RVA: 0x20771b0 VA: 0x759468f1b0
	public Void OnBossSkillReady() { }
	// RVA: 0x20772fc VA: 0x759468f2fc
	public override Boolean HookPredefinedUILocation(Camera uiCam, PredefinedLocation location, out Vector3 worldPos) { }
	// RVA: 0x2076d68 VA: 0x759468ed68
	private RoguelikeTopicMode _GetSpecialTopicMode() { }
	// RVA: 0x2077590 VA: 0x759468f590
	public Void .ctor() { }
	// RVA: 0x2077600 VA: 0x759468f600
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x2077608 VA: 0x759468f608
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x2077610 VA: 0x759468f610
	private Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch() { }
	// RVA: 0x2077618 VA: 0x759468f618
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x2077620 VA: 0x759468f620
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x2077628 VA: 0x759468f628
	private Boolean <>xLuaBaseProxy_HookConfirmFinish(Action P0) { }
	// RVA: 0x2077630 VA: 0x759468f630
	private RectTransform <>xLuaBaseProxy_HookBattleFailedPanelInit() { }
	// RVA: 0x2077638 VA: 0x759468f638
	private Boolean <>xLuaBaseProxy_HookBattleFailedPanelShow() { }
	// RVA: 0x2077640 VA: 0x759468f640
	private Boolean <>xLuaBaseProxy_HookBattleFailedPanelHide() { }
	// RVA: 0x2077648 VA: 0x759468f648
	private Boolean <>xLuaBaseProxy_HookPredefinedUILocation(Camera P0, PredefinedLocation P1, out Vector3 P2) { }
}
```
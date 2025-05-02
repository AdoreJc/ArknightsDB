# AutoChessUIPlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `AutoChessCharacterMenuPanel _characterMenuPanel`

- `AutoChessDeployStatusPanel _deployStatusPanel`

- `String _dummyHudPrefabName`

- `AutoChessCoinCntPanel _coinCntPanelPrefab`

- `Single _toastTime`

- `AutoChessCameraPlugin m_cameraPlugin`

- `AutoChessDummyHud m_dummyPluginPrefab`

- `AutoChessCharacterMenuPanel m_characterMenuPanel`

- `AutoChessCoinCntPanel m_coinCntPanel`

- `AudioManager m_audioManager`

- `Boolean m_isDuringCampMove`

- `Coroutine m_cameraMoveCoroutine`

- `AutoChessGameMode m_gameMode`


## Properties

- `AutoChessGameMode gameMode`

- `AutoChessCameraPlugin cameraPlugin`

- `AutoChessDummyHud dummyPlugin`

- `Boolean isDuringCampMove`


## Methods

- `AutoChessGameMode get_gameMode()`

- `AutoChessCameraPlugin get_cameraPlugin()`

- `AutoChessDummyHud get_dummyPlugin()`

- `Boolean get_isDuringCampMove()`

- `Void _OnEnemyCampClick(Object)`

- `Void _RouteToDefault(Object)`

- `Void _OnDummyUpdate(Object)`

- `Void _OnDummyRemoved(Object)`

- `Void _OnTutorialRegistExtraBattleTarget(Object)`

- `Void _OnDummyDeployStatusChanged(Object)`

- `Void _OnPlaneAnim(Object)`

- `Void _OnExitShopState(Object)`

- `Void _OnRoundStarted(Object)`

- `Void _OnRoundFinished(Object)`

- `Void _OnSystemMenuConfirm(Object)`

- `Void _OnHudClicked(Object)`

- `Void _OnTimeChanged(Object)`

- `Void _OnDataChanged(Object)`

- `Void _LeaveGameQuiet()`

- `Void _FinishGame(Object)`

- `Void _OnOperationeRejected(Object)`

- `Void _OnLoadForShopFinished(Object)`

- `Void _OnCharacterPlaceAtBattleField(Object)`

- `Void _OnCharacterPlaceAtHandField(Object)`

- `Void _SetDummyHud(Tile, Character, AutoChessDummyHud)`

- `Boolean _SetShopStateDummy(Tile, Character, AutoChessDummyHud)`

- `Void _OnPauseClick(Object)`

- `Void _OnPauseRevert(Object)`

- `Void _OnMenuClick(Object)`

- `Void _OnLoadForBattle(Object)`

- `Void OnBeginDrag_StateOnly(Object)`

- `Void _ShowRetryDialog(Object)`

- `Void _OnRetryNegative()`

- `Void _InitCoinCntPanel()`

- `Void _BindEventCenterEvent()`

- `Void _BindGameModeEvent()`

- `Void _InitCameraPosition(Options)`

- `HintData _GetHintData(String)`

- `Void _SetHandDummy(Tile, Character, AutoChessDummyHud, Int32, Boolean, Int32)`

- `Void _SetBattleFieldDummy(Character, AutoChessDummyHud, Int32, Boolean, Int32)`

- `Boolean _SetShopDummy(Character, AutoChessDummyHud, Tile)`

- `Boolean _SetBattleStateDummy(Tile, Character, AutoChessDummyHud)`

- `Boolean _IsCameraMoveValid()`

- `Void _LockUntilMoveFinished()`

- `IEnumerator _LockHighlightUntilMoveFinished()`

- `Void OnDestroy()`

- `Boolean <>xLuaBaseProxy_get_needReleaseIllust()`

- `Vector3 <>xLuaBaseProxy_get_hudScale()`

- `Boolean <>xLuaBaseProxy_get_showCharacterStatusInDummy()`

- `Boolean <>xLuaBaseProxy_get_slowMotionInCharacterMenuState()`

- `IUICharacterMenuPanel <>xLuaBaseProxy_GetHookUICharacterMenuPanel(Character)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Boolean <>xLuaBaseProxy_HookOnBattleFinishServiceStateEnter()`

- `Boolean <>xLuaBaseProxy_HookUIShowCardState()`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_HookCharacterInfoSubPanelSkillParse(Blackboard, BattleCharacterData, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessUIPlugin : Plugin
{
	public const UIStateEnum UI_STATE_DRAG_STATE; // 0x0
	public const UIStateEnum UI_STATE_ACCOMPLISHED_STATE; // 0x0
	public const UIStateEnum UI_STATE_HIGHLIGHT_STATE; // 0x0
	private const Single HUD_SCALE; // 0x0
	private UIStateNode[] _states; // 0x28
	private AutoChessCharacterMenuPanel _characterMenuPanel; // 0x30
	private AutoChessDeployStatusPanel _deployStatusPanel; // 0x38
	private String _dummyHudPrefabName; // 0x40
	private AutoChessCoinCntPanel _coinCntPanelPrefab; // 0x48
	private Single _toastTime; // 0x50
	private HookedCharacterInfoSubPanel[] _hookedCharacterInfoSubPanels; // 0x58
	private AutoChessCameraPlugin m_cameraPlugin; // 0x60
	private AutoChessDummyHud m_dummyPluginPrefab; // 0x68
	private AutoChessCharacterMenuPanel m_characterMenuPanel; // 0x70
	private AutoChessCoinCntPanel m_coinCntPanel; // 0x78
	private ListDict`2 m_dummyHudMap; // 0x80
	private AudioManager m_audioManager; // 0x88
	private Boolean m_isDuringCampMove; // 0x90
	private Coroutine m_cameraMoveCoroutine; // 0x98
	public Action`1 onBeginDrag; // 0xa0
	private List`1 m_hintData; // 0xa8
	private AutoChessGameMode m_gameMode; // 0xb0
	private static DelegateBridge __Hotfix0_get_hintData; // 0x0
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x8
	private static DelegateBridge __Hotfix0_get_cameraPlugin; // 0x10
	private static DelegateBridge __Hotfix0_get_dummyPlugin; // 0x18
	private static DelegateBridge __Hotfix0_get_needReleaseIllust; // 0x20
	private static DelegateBridge __Hotfix0_get_hudScale; // 0x28
	private static DelegateBridge __Hotfix0_HookCharacterInfoSubPanels; // 0x30
	private static DelegateBridge __Hotfix0_get_showCharacterStatusInDummy; // 0x38
	private static DelegateBridge __Hotfix0_get_slowMotionInCharacterMenuState; // 0x40
	private static DelegateBridge __Hotfix0_get_isDuringCampMove; // 0x48
	private static DelegateBridge __Hotfix0_GetHookUICharacterMenuPanel; // 0x50
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x58
	private static DelegateBridge __Hotfix0_HookOnBattleFinishServiceStateEnter; // 0x60
	private static DelegateBridge __Hotfix0_HookUIShowCardState; // 0x68
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x70
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x78
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x80
	private static DelegateBridge __Hotfix0_HookCharacterInfoSubPanelSkillParse; // 0x88
	private static DelegateBridge __Hotfix0__OnEnemyCampClick; // 0x90
	private static DelegateBridge __Hotfix0__RouteToDefault; // 0x98
	private static DelegateBridge __Hotfix0__OnDummyUpdate; // 0xa0
	private static DelegateBridge __Hotfix0__OnDummyRemoved; // 0xa8
	private static DelegateBridge __Hotfix0__OnTutorialRegistExtraBattleTarget; // 0xb0
	private static DelegateBridge __Hotfix0__OnDummyDeployStatusChanged; // 0xb8
	private static DelegateBridge __Hotfix0__OnPlaneAnim; // 0xc0
	private static DelegateBridge __Hotfix0__OnExitShopState; // 0xc8
	private static DelegateBridge __Hotfix0__OnRoundStarted; // 0xd0
	private static DelegateBridge __Hotfix0__OnRoundFinished; // 0xd8
	private static DelegateBridge __Hotfix0__OnSystemMenuConfirm; // 0xe0
	private static DelegateBridge __Hotfix0__OnHudClicked; // 0xe8
	private static DelegateBridge __Hotfix0__OnTimeChanged; // 0xf0
	private static DelegateBridge __Hotfix0__OnDataChanged; // 0xf8
	private static DelegateBridge __Hotfix0__LeaveGameQuiet; // 0x100
	private static DelegateBridge __Hotfix0__FinishGame; // 0x108
	private static DelegateBridge __Hotfix0__OnOperationeRejected; // 0x110
	private static DelegateBridge __Hotfix0__OnLoadForShopFinished; // 0x118
	private static DelegateBridge __Hotfix0__OnCharacterPlaceAtBattleField; // 0x120
	private static DelegateBridge __Hotfix0__OnCharacterPlaceAtHandField; // 0x128
	private static DelegateBridge __Hotfix0__SetDummyHud; // 0x130
	private static DelegateBridge __Hotfix0__SetShopStateDummy; // 0x138
	private static DelegateBridge __Hotfix0__OnPauseClick; // 0x140
	private static DelegateBridge __Hotfix0__OnPauseRevert; // 0x148
	private static DelegateBridge __Hotfix0__OnMenuClick; // 0x150
	private static DelegateBridge __Hotfix0__OnLoadForBattle; // 0x158
	private static DelegateBridge __Hotfix0_OnBeginDrag_StateOnly; // 0x160
	private static DelegateBridge __Hotfix0__ShowRetryDialog; // 0x168
	private static DelegateBridge __Hotfix0__OnRetryNegative; // 0x170
	private static DelegateBridge __Hotfix0__InitCoinCntPanel; // 0x178
	private static DelegateBridge __Hotfix0__BindEventCenterEvent; // 0x180
	private static DelegateBridge __Hotfix0__BindGameModeEvent; // 0x188
	private static DelegateBridge __Hotfix0__InitCameraPosition; // 0x190
	private static DelegateBridge __Hotfix0__GetHintData; // 0x198
	private static DelegateBridge __Hotfix0__SetHandDummy; // 0x1a0
	private static DelegateBridge __Hotfix0__SetBattleFieldDummy; // 0x1a8
	private static DelegateBridge __Hotfix0__SetShopDummy; // 0x1b0
	private static DelegateBridge __Hotfix0__SetBattleStateDummy; // 0x1b8
	private static DelegateBridge __Hotfix0__IsCameraMoveValid; // 0x1c0
	private static DelegateBridge __Hotfix0__LockUntilMoveFinished; // 0x1c8
	private static DelegateBridge __Hotfix0__LockHighlightUntilMoveFinished; // 0x1d0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x1d8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1e0

	private List`1 hintData { get; }
	private AutoChessGameMode gameMode { get; }
	private AutoChessCameraPlugin cameraPlugin { get; }
	private AutoChessDummyHud dummyPlugin { get; }
	public override Boolean needReleaseIllust { get; }
	public override Vector3 hudScale { get; }
	public override Boolean showCharacterStatusInDummy { get; }
	public override Boolean slowMotionInCharacterMenuState { get; }
	public Boolean isDuringCampMove { get; }

	// RVA: 0x2069468 VA: 0x7594681468
	private List`1 get_hintData() { }
	// RVA: 0x2069a3c VA: 0x7594681a3c
	private AutoChessGameMode get_gameMode() { }
	// RVA: 0x2069aec VA: 0x7594681aec
	private AutoChessCameraPlugin get_cameraPlugin() { }
	// RVA: 0x2069c4c VA: 0x7594681c4c
	private AutoChessDummyHud get_dummyPlugin() { }
	// RVA: 0x2069d54 VA: 0x7594681d54
	public override Boolean get_needReleaseIllust() { }
	// RVA: 0x2069dec VA: 0x7594681dec
	public override Vector3 get_hudScale() { }
	// RVA: 0x2069e5c VA: 0x7594681e5c
	public override HookedCharacterInfoSubPanel[] HookCharacterInfoSubPanels() { }
	// RVA: 0x2069ec4 VA: 0x7594681ec4
	public override Boolean get_showCharacterStatusInDummy() { }
	// RVA: 0x2069f2c VA: 0x7594681f2c
	public override Boolean get_slowMotionInCharacterMenuState() { }
	// RVA: 0x2069f90 VA: 0x7594681f90
	public Boolean get_isDuringCampMove() { }
	// RVA: 0x2069ff8 VA: 0x7594681ff8
	public override IUICharacterMenuPanel GetHookUICharacterMenuPanel(Character character) { }
	// RVA: 0x206a174 VA: 0x7594682174
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x206ae54 VA: 0x7594682e54
	public override Boolean HookOnBattleFinishServiceStateEnter() { }
	// RVA: 0x206aee0 VA: 0x7594682ee0
	public override Boolean HookUIShowCardState() { }
	// RVA: 0x206af48 VA: 0x7594682f48
	public override Void OnGameStart() { }
	// RVA: 0x206b33c VA: 0x759468333c
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x206b434 VA: 0x7594683434
	public override Void UpdateGameInfo() { }
	// RVA: 0x206b5c8 VA: 0x75946835c8
	public override Boolean HookCharacterInfoSubPanelSkillParse(Blackboard blackboard, BattleCharacterData data, ref String description) { }
	// RVA: 0x206b7fc VA: 0x75946837fc
	public Void _OnEnemyCampClick(Object arg) { }
	// RVA: 0x206bb50 VA: 0x7594683b50
	public Void _RouteToDefault(Object arg) { }
	// RVA: 0x206bc64 VA: 0x7594683c64
	private Void _OnDummyUpdate(Object arg) { }
	// RVA: 0x206c07c VA: 0x759468407c
	private Void _OnDummyRemoved(Object arg) { }
	// RVA: 0x206c1dc VA: 0x75946841dc
	private Void _OnTutorialRegistExtraBattleTarget(Object arg) { }
	// RVA: 0x206c2f0 VA: 0x75946842f0
	private Void _OnDummyDeployStatusChanged(Object arg) { }
	// RVA: 0x206c43c VA: 0x759468443c
	private Void _OnPlaneAnim(Object arg) { }
	// RVA: 0x206c668 VA: 0x7594684668
	private Void _OnExitShopState(Object arg) { }
	// RVA: 0x206c74c VA: 0x759468474c
	private Void _OnRoundStarted(Object arg) { }
	// RVA: 0x206c7ec VA: 0x75946847ec
	private Void _OnRoundFinished(Object arg) { }
	// RVA: 0x206c9f0 VA: 0x75946849f0
	private Void _OnSystemMenuConfirm(Object arg) { }
	// RVA: 0x206cb40 VA: 0x7594684b40
	private Void _OnHudClicked(Object arg) { }
	// RVA: 0x206cc24 VA: 0x7594684c24
	private Void _OnTimeChanged(Object arg) { }
	// RVA: 0x206ce18 VA: 0x7594684e18
	private Void _OnDataChanged(Object arg) { }
	// RVA: 0x206ca6c VA: 0x7594684a6c
	private Void _LeaveGameQuiet() { }
	// RVA: 0x206cf80 VA: 0x7594684f80
	private Void _FinishGame(Object arg) { }
	// RVA: 0x206d020 VA: 0x7594685020
	private Void _OnOperationeRejected(Object arg) { }
	// RVA: 0x206d484 VA: 0x7594685484
	private Void _OnLoadForShopFinished(Object obj) { }
	// RVA: 0x206d560 VA: 0x7594685560
	private Void _OnCharacterPlaceAtBattleField(Object arg) { }
	// RVA: 0x206d7d0 VA: 0x75946857d0
	private Void _OnCharacterPlaceAtHandField(Object arg) { }
	// RVA: 0x206bf18 VA: 0x7594683f18
	private Void _SetDummyHud(Tile tile, Character character, AutoChessDummyHud hud) { }
	// RVA: 0x206daec VA: 0x7594685aec
	private Boolean _SetShopStateDummy(Tile tile, Character character, AutoChessDummyHud hud) { }
	// RVA: 0x206e61c VA: 0x759468661c
	private Void _OnPauseClick(Object arg) { }
	// RVA: 0x206e750 VA: 0x7594686750
	private Void _OnPauseRevert(Object arg) { }
	// RVA: 0x206e894 VA: 0x7594686894
	private Void _OnMenuClick(Object arg) { }
	// RVA: 0x206ea6c VA: 0x7594686a6c
	private Void _OnLoadForBattle(Object arg) { }
	// RVA: 0x206eb00 VA: 0x7594686b00
	public Void OnBeginDrag_StateOnly(Object arg) { }
	// RVA: 0x206eb98 VA: 0x7594686b98
	private Void _ShowRetryDialog(Object arg) { }
	// RVA: 0x206ed68 VA: 0x7594686d68
	private Void _OnRetryNegative() { }
	// RVA: 0x206b108 VA: 0x7594683108
	private Void _InitCoinCntPanel() { }
	// RVA: 0x206a5fc VA: 0x75946825fc
	private Void _BindEventCenterEvent() { }
	// RVA: 0x206a988 VA: 0x7594682988
	private Void _BindGameModeEvent() { }
	// RVA: 0x206a26c VA: 0x759468226c
	private Void _InitCameraPosition(Options levelOptions) { }
	// RVA: 0x206d25c VA: 0x759468525c
	private HintData _GetHintData(String hintRef) { }
	// RVA: 0x206e3b0 VA: 0x75946863b0
	private Void _SetHandDummy(Tile tile, Character character, AutoChessDummyHud hud, Int32 chessLevel, Boolean isEquipOrMagic, Int32 instId) { }
	// RVA: 0x206e160 VA: 0x7594686160
	private Void _SetBattleFieldDummy(Character character, AutoChessDummyHud hud, Int32 chessLevel, Boolean isEquipOrMagic, Int32 instId) { }
	// RVA: 0x206dda0 VA: 0x7594685da0
	private Boolean _SetShopDummy(Character character, AutoChessDummyHud hud, Tile tile) { }
	// RVA: 0x206d908 VA: 0x7594685908
	private Boolean _SetBattleStateDummy(Tile tile, Character character, AutoChessDummyHud hud) { }
	// RVA: 0x206b910 VA: 0x7594683910
	private Boolean _IsCameraMoveValid() { }
	// RVA: 0x206bab0 VA: 0x7594683ab0
	private Void _LockUntilMoveFinished() { }
	// RVA: 0x206ee84 VA: 0x7594686e84
	private IEnumerator _LockHighlightUntilMoveFinished() { }
	// RVA: 0x206ef58 VA: 0x7594686f58
	private Void OnDestroy() { }
	// RVA: 0x206efe0 VA: 0x7594686fe0
	public Void .ctor() { }
	// RVA: 0x206f208 VA: 0x7594687208
	private Boolean <>xLuaBaseProxy_get_needReleaseIllust() { }
	// RVA: 0x206f20c VA: 0x759468720c
	private Vector3 <>xLuaBaseProxy_get_hudScale() { }
	// RVA: 0x206f210 VA: 0x7594687210
	private HookedCharacterInfoSubPanel[] <>xLuaBaseProxy_HookCharacterInfoSubPanels() { }
	// RVA: 0x206f214 VA: 0x7594687214
	private Boolean <>xLuaBaseProxy_get_showCharacterStatusInDummy() { }
	// RVA: 0x206f218 VA: 0x7594687218
	private Boolean <>xLuaBaseProxy_get_slowMotionInCharacterMenuState() { }
	// RVA: 0x206f21c VA: 0x759468721c
	private IUICharacterMenuPanel <>xLuaBaseProxy_GetHookUICharacterMenuPanel(Character P0) { }
	// RVA: 0x206f220 VA: 0x7594687220
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x206f224 VA: 0x7594687224
	private Boolean <>xLuaBaseProxy_HookOnBattleFinishServiceStateEnter() { }
	// RVA: 0x206f228 VA: 0x7594687228
	private Boolean <>xLuaBaseProxy_HookUIShowCardState() { }
	// RVA: 0x206f22c VA: 0x759468722c
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x206f230 VA: 0x7594687230
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x206f234 VA: 0x7594687234
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x206f238 VA: 0x7594687238
	private Boolean <>xLuaBaseProxy_HookCharacterInfoSubPanelSkillParse(Blackboard P0, BattleCharacterData P1, ref String P2) { }
}
```
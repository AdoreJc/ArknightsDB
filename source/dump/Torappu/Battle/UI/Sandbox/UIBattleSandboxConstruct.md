# UIBattleSandboxConstruct

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `UIBattleSandboxConstructCharacterMenuPanel _constructCharacterMenuPanel`

- `UIFadeFloatPanel _rightButtonGroup`

- `UIFadeFloatPanel _rightUpSaveGroup`

- `UIFadeFloatPanel _rightPageOpenGroup`

- `Transform _inputSwallower`

- `EventTrigger _inputTrigger`

- `UIBattleSandboxConstructFloatIDPanel _floatIdPanel`

- `UIFadeFloatPanel _rightUpMatGroup`

- `SimpleLayoutContent _topRightMatLayoutContent`

- `Text _goldName`

- `UIBattleSandboxConstructItemPair _goldPair`

- `Single _matColorAlpha`

- `Image _matBg`

- `UIBattleSandboxConstructTopBar _topPlayerStatusBar`

- `UIFadeFloatPanel _topGroup`

- `UIFadeFloatPanel _topHpGroup`

- `Slider _hpSlider`

- `Button _saveBtn`

- `Single _fastTweenTime`

- `Single _cameraMoveSpeed`

- `Single _matDelayTweenTime`

- `Ease _outScaleEase`

- `Ease _inScaleEase`

- `Ease _outEase`

- `Ease _inEase`

- `Boolean _useMouseMoving`

- `Single _disableCamSeconds`

- `String _repairAllEffect`

- `Single _repairEffectDelay`

- `Boolean m_inited`

- `Boolean m_needResetCamera`

- `Vector3 m_lastCameraPos`

- `UIBattleSandboxConstructCharacterMenuPanel m_constructPanel`

- `PairListAdapter m_adapter`

- `GroupTransHelper m_transHelper`

- `CoroutineId m_hideCamCoroutine`

- `ConstructLandManager m_manager`

- `PrecisePeriodicTimer m_timer`

- `Single m_baseHpRatio`

- `Boolean m_showBase`

- `Boolean m_isTriggerDrag`

- `Effect m_repairEffect`

- `Tween m_showUITween`


## Properties

- `SandboxV2ConstructDetailModel detailedModel`

- `UIBattleSandboxConstructCharacterMenuPanel constructPanel`

- `SandboxV2Data dataTable`

- `SandboxCameraPlugin cameraPlugin`

- `ConstructLandManager manager`

- `SandboxGameMode sandboxGameMode`


## Methods

- `SandboxV2ConstructDetailModel get_detailedModel()`

- `UIBattleSandboxConstructCharacterMenuPanel get_constructPanel()`

- `SandboxV2Data get_dataTable()`

- `SandboxCameraPlugin get_cameraPlugin()`

- `ConstructLandManager get_manager()`

- `SandboxGameMode get_sandboxGameMode()`

- `Void _InitIfNot()`

- `Void _InitTopInfo(String)`

- `Void _InitMats(String)`

- `Void _BindEvents()`

- `Void _BindAvgBtns()`

- `Void Update()`

- `Void OnDestroy()`

- `Void OnUIStateSwitched(Int32, Int32)`

- `Boolean _IsDisplayState(UIStateEnum)`

- `Void OnSaveBtnClicked()`

- `Void OnResetBtnClicked()`

- `Void OnCameraBtnClicked()`

- `Void OnHideUIBtnClicked()`

- `Void OnToCraftBtnClicked()`

- `Void OnInputTriggerClicked(Object)`

- `Void OnTriggerDrag(Object)`

- `Void _ReturnToDefaultState(Object)`

- `Void _OnPageStop(Object)`

- `Void _OnPageResume(Object)`

- `Void _OnRepairAllConfirmed(Object)`

- `Void _OnResetMapConfimed(Object)`

- `Void _OnGameStart(Object)`

- `Void _OnConstructPanelHide(Boolean)`

- `Void _OnCharacterClicked(Character)`

- `Void _PlayRepairAllEffect()`

- `Void _DoUpdateAllRepairCost()`

- `Vector3 _GetWorldCenter()`

- `Void _DoHideUI()`

- `Boolean _TryResetCamera(Object)`

- `Boolean _IsUnbreakableShowingUI()`

- `Void _ShowUI(Object)`

- `Tween _DoDelayToShowUIWithTween(Single)`

- `Void _RenderTopStatisIfChanged()`

- `Void <_DoDelayToShowUIWithTween>b__87_0()`

- `Void <_DoDelayToShowUIWithTween>b__87_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxConstruct : MonoBehaviour, IHotfixable
{
	private UIBattleSandboxConstructCharacterMenuPanel _constructCharacterMenuPanel; // 0x18
	private UIFadeFloatPanel _rightButtonGroup; // 0x20
	private UIFadeFloatPanel _rightUpSaveGroup; // 0x28
	private UIFadeFloatPanel _rightPageOpenGroup; // 0x30
	private Transform _inputSwallower; // 0x38
	private EventTrigger _inputTrigger; // 0x40
	private UIBattleSandboxConstructFloatIDPanel _floatIdPanel; // 0x48
	private UIFadeFloatPanel _rightUpMatGroup; // 0x50
	private SimpleLayoutContent _topRightMatLayoutContent; // 0x58
	private Text _goldName; // 0x60
	private UIBattleSandboxConstructItemPair _goldPair; // 0x68
	private Single _matColorAlpha; // 0x70
	private Image _matBg; // 0x78
	private UIBattleSandboxConstructTopBar _topPlayerStatusBar; // 0x80
	private UIFadeFloatPanel _topGroup; // 0x88
	private UIFadeFloatPanel _topHpGroup; // 0x90
	private Slider _hpSlider; // 0x98
	private Button _saveBtn; // 0xa0
	private Single _fastTweenTime; // 0xa8
	private Single _cameraMoveSpeed; // 0xac
	private Single _matDelayTweenTime; // 0xb0
	private Ease _outScaleEase; // 0xb4
	private Ease _inScaleEase; // 0xb8
	private Ease _outEase; // 0xbc
	private Ease _inEase; // 0xc0
	private Boolean _useMouseMoving; // 0xc4
	private Single _disableCamSeconds; // 0xc8
	private String _repairAllEffect; // 0xd0
	private Single _repairEffectDelay; // 0xd8
	private Boolean m_inited; // 0xdc
	private Boolean m_needResetCamera; // 0xdd
	private Vector3 m_lastCameraPos; // 0xe0
	private UIBattleSandboxConstructCharacterMenuPanel m_constructPanel; // 0xf0
	private PairListAdapter m_adapter; // 0xf8
	private GroupTransHelper m_transHelper; // 0x100
	private CoroutineId m_hideCamCoroutine; // 0x108
	private ConstructLandManager m_manager; // 0x118
	private PrecisePeriodicTimer m_timer; // 0x120
	private Single m_baseHpRatio; // 0x128
	private Boolean m_showBase; // 0x12c
	private Boolean m_isTriggerDrag; // 0x12d
	private const Single STATUS_UPDATE_INTERVAL; // 0x0
	private Effect m_repairEffect; // 0x130
	private Tween m_showUITween; // 0x138
	private static DelegateBridge __Hotfix0_get_detailedModel; // 0x0
	private static DelegateBridge __Hotfix0_get_constructPanel; // 0x8
	private static DelegateBridge __Hotfix0_get_dataTable; // 0x10
	private static DelegateBridge __Hotfix0_get_cameraPlugin; // 0x18
	private static DelegateBridge __Hotfix0_get_manager; // 0x20
	private static DelegateBridge __Hotfix0_get_sandboxGameMode; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__InitTopInfo; // 0x38
	private static DelegateBridge __Hotfix0__InitMats; // 0x40
	private static DelegateBridge __Hotfix0__BindEvents; // 0x48
	private static DelegateBridge __Hotfix0__BindAvgBtns; // 0x50
	private static DelegateBridge __Hotfix0_Update; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge __Hotfix0_OnUIStateSwitched; // 0x68
	private static DelegateBridge __Hotfix0__IsDisplayState; // 0x70
	private static DelegateBridge __Hotfix0_OnSaveBtnClicked; // 0x78
	private static DelegateBridge __Hotfix0_OnResetBtnClicked; // 0x80
	private static DelegateBridge __Hotfix0_OnCameraBtnClicked; // 0x88
	private static DelegateBridge __Hotfix0_OnHideUIBtnClicked; // 0x90
	private static DelegateBridge __Hotfix0_OnToCraftBtnClicked; // 0x98
	private static DelegateBridge __Hotfix0_OnInputTriggerClicked; // 0xa0
	private static DelegateBridge __Hotfix0_OnTriggerDrag; // 0xa8
	private static DelegateBridge __Hotfix0__ReturnToDefaultState; // 0xb0
	private static DelegateBridge __Hotfix0__OnPageStop; // 0xb8
	private static DelegateBridge __Hotfix0__OnPageResume; // 0xc0
	private static DelegateBridge __Hotfix0__OnRepairAllConfirmed; // 0xc8
	private static DelegateBridge __Hotfix0__OnResetMapConfimed; // 0xd0
	private static DelegateBridge __Hotfix0__OnGameStart; // 0xd8
	private static DelegateBridge __Hotfix0__OnConstructPanelHide; // 0xe0
	private static DelegateBridge __Hotfix0__OnCharacterClicked; // 0xe8
	private static DelegateBridge __Hotfix0__PlayRepairAllEffect; // 0xf0
	private static DelegateBridge __Hotfix0__DoUpdateAllRepairCost; // 0xf8
	private static DelegateBridge __Hotfix0__GetWorldCenter; // 0x100
	private static DelegateBridge __Hotfix0__DoHideUI; // 0x108
	private static DelegateBridge __Hotfix0__TryResetCamera; // 0x110
	private static DelegateBridge __Hotfix0__IsUnbreakableShowingUI; // 0x118
	private static DelegateBridge __Hotfix0__ShowUI; // 0x120
	private static DelegateBridge __Hotfix0__DoDelayToShowUIWithTween; // 0x128
	private static DelegateBridge __Hotfix0__RenderTopStatisIfChanged; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138

	private SandboxV2ConstructDetailModel detailedModel { get; }
	public UIBattleSandboxConstructCharacterMenuPanel constructPanel { get; }
	private SandboxV2Data dataTable { get; }
	private SandboxCameraPlugin cameraPlugin { get; }
	private ConstructLandManager manager { get; }
	private SandboxGameMode sandboxGameMode { get; }

	// RVA: 0x2093880 VA: 0x75946ab880
	private SandboxV2ConstructDetailModel get_detailedModel() { }
	// RVA: 0x2093900 VA: 0x75946ab900
	public UIBattleSandboxConstructCharacterMenuPanel get_constructPanel() { }
	// RVA: 0x2093968 VA: 0x75946ab968
	private SandboxV2Data get_dataTable() { }
	// RVA: 0x2093a6c VA: 0x75946aba6c
	private SandboxCameraPlugin get_cameraPlugin() { }
	// RVA: 0x2093b48 VA: 0x75946abb48
	private ConstructLandManager get_manager() { }
	// RVA: 0x20939e0 VA: 0x75946ab9e0
	private SandboxGameMode get_sandboxGameMode() { }
	// RVA: 0x2093c10 VA: 0x75946abc10
	private Void _InitIfNot() { }
	// RVA: 0x20942c8 VA: 0x75946ac2c8
	private Void _InitTopInfo(String topicId) { }
	// RVA: 0x2093f68 VA: 0x75946abf68
	private Void _InitMats(String topicId) { }
	// RVA: 0x209461c VA: 0x75946ac61c
	private Void _BindEvents() { }
	// RVA: 0x2094d40 VA: 0x75946acd40
	private Void _BindAvgBtns() { }
	// RVA: 0x20952a0 VA: 0x75946ad2a0
	private Void Update() { }
	// RVA: 0x2095860 VA: 0x75946ad860
	private Void OnDestroy() { }
	// RVA: 0x2095990 VA: 0x75946ad990
	public Void OnUIStateSwitched(Int32 newStateId, Int32 oldStateId) { }
	// RVA: 0x2095a98 VA: 0x75946ada98
	private Boolean _IsDisplayState(UIStateEnum state) { }
	// RVA: 0x2095b34 VA: 0x75946adb34
	public Void OnSaveBtnClicked() { }
	// RVA: 0x2095bc8 VA: 0x75946adbc8
	public Void OnResetBtnClicked() { }
	// RVA: 0x2095c5c VA: 0x75946adc5c
	public Void OnCameraBtnClicked() { }
	// RVA: 0x20961d4 VA: 0x75946ae1d4
	public Void OnHideUIBtnClicked() { }
	// RVA: 0x20962d4 VA: 0x75946ae2d4
	public Void OnToCraftBtnClicked() { }
	// RVA: 0x2096368 VA: 0x75946ae368
	public Void OnInputTriggerClicked(Object arg) { }
	// RVA: 0x20965b0 VA: 0x75946ae5b0
	public Void OnTriggerDrag(Object arg) { }
	// RVA: 0x2096680 VA: 0x75946ae680
	private Void _ReturnToDefaultState(Object _) { }
	// RVA: 0x2096744 VA: 0x75946ae744
	private Void _OnPageStop(Object _) { }
	// RVA: 0x2096940 VA: 0x75946ae940
	private Void _OnPageResume(Object _) { }
	// RVA: 0x2096aac VA: 0x75946aeaac
	private Void _OnRepairAllConfirmed(Object _) { }
	// RVA: 0x2096dc0 VA: 0x75946aedc0
	private Void _OnResetMapConfimed(Object _) { }
	// RVA: 0x2096ea8 VA: 0x75946aeea8
	private Void _OnGameStart(Object _) { }
	// RVA: 0x2096f3c VA: 0x75946aef3c
	private Void _OnConstructPanelHide(Boolean opExecuted) { }
	// RVA: 0x2096ff0 VA: 0x75946aeff0
	private Void _OnCharacterClicked(Character character) { }
	// RVA: 0x2096c08 VA: 0x75946aec08
	private Void _PlayRepairAllEffect() { }
	// RVA: 0x2096d24 VA: 0x75946aed24
	private Void _DoUpdateAllRepairCost() { }
	// RVA: 0x20960e0 VA: 0x75946ae0e0
	private Vector3 _GetWorldCenter() { }
	// RVA: 0x2095f84 VA: 0x75946adf84
	private Void _DoHideUI() { }
	// RVA: 0x2097344 VA: 0x75946af344
	private Boolean _TryResetCamera(Object arg) { }
	// RVA: 0x2095e58 VA: 0x75946ade58
	private Boolean _IsUnbreakableShowingUI() { }
	// RVA: 0x209641c VA: 0x75946ae41c
	private Void _ShowUI(Object arg) { }
	// RVA: 0x2097510 VA: 0x75946af510
	private Tween _DoDelayToShowUIWithTween(Single time) { }
	// RVA: 0x20954b8 VA: 0x75946ad4b8
	private Void _RenderTopStatisIfChanged() { }
	// RVA: 0x20976dc VA: 0x75946af6dc
	public Void .ctor() { }
	// RVA: 0x20978a0 VA: 0x75946af8a0
	private Void <_DoDelayToShowUIWithTween>b__87_0() { }
	// RVA: 0x2097a48 VA: 0x75946afa48
	private Void <_DoDelayToShowUIWithTween>b__87_1() { }
}
```
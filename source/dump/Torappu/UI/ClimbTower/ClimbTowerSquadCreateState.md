# ClimbTowerSquadCreateState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadCreateView _view`

- `SimpleLayoutContent _stepList`

- `SquadCharSelectMaskPlugin _charSelectMaskPluginPrefab`

- `ClimbTowerMenuButton _menuButtonPrefab`

- `RectTransform _backBtnRt`

- `ClimbTowerSquadCreateStateBean m_stateBean`

- `Input m_paramToSelectState`

- `ClimbTowerInitStepListAdapter m_stepAdapter`

- `MenuAdapter m_menuAdapter`

- `Coroutine m_tutorialCoroutine`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `SquadGroupViewModel GetSquadGroupViewModel()`

- `Void _NavToLayerState()`

- `Void OnQuickFormatClick()`

- `Void OnBtnQuit()`

- `Void _SendSettleGameRequest()`

- `Void OnBtnAssistClick()`

- `Void _EventOnAssistClean(Int32)`

- `Void _EventOnGetAssist(Int32)`

- `Void _EventOnSingleFormatClick(Int32)`

- `Void _EventOnMultiFormatClick()`

- `Input _ParseSquadSelectParam(Boolean, Int32)`

- `Void _EventOnMenuButtonClick()`

- `Int32 _GetProfessionCharCount(ProfessionCategory)`

- `Void _InitSquad()`

- `Void _NavToTowreLayerState()`

- `Void _SaveDataToLocalCache()`

- `Void _SaveTowerSelectModeToCache()`

- `Void _TriggerTutorialCoroutine()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitAndTrigTutorial()`

- `Void <RegisterToDataListener>b__20_0(IStateBean)`

- `Void <RegisterToDataListener>b__20_1(IStateBean)`

- `Void <RegisterFromDataListener>b__22_0(IStateBean)`

- `Void <RegisterFromDataListener>b__22_1(IStateBean)`

- `Void <_SendSettleGameRequest>b__28_0(ClimbTowerSettleGameResponse)`

- `Void <_InitSquad>b__37_0(ClimbTowerInitSquadResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadCreateState : PopupFadeState, ISquadCharSelectContext
{
	private ClimbTowerSquadCreateView _view; // 0x70
	private SimpleLayoutContent _stepList; // 0x78
	private SquadCharSelectMaskPlugin _charSelectMaskPluginPrefab; // 0x80
	private ClimbTowerMenuButton _menuButtonPrefab; // 0x88
	private RectTransform _backBtnRt; // 0x90
	private ClimbTowerSquadCreateStateBean m_stateBean; // 0x98
	private Input m_paramToSelectState; // 0xa0
	private ClimbTowerInitStepListAdapter m_stepAdapter; // 0xe0
	private MenuAdapter m_menuAdapter; // 0xe8
	private Coroutine m_tutorialCoroutine; // 0xf0
	private List`1 m_tempListForExclusiveInstIds; // 0xf8
	private Boolean m_hasInited; // 0x100
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnPause; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x30
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x38
	private static DelegateBridge __Hotfix0_GetTempListForExclusiveInstIds; // 0x40
	private static DelegateBridge __Hotfix0_GetSquadGroupViewModel; // 0x48
	private static DelegateBridge __Hotfix0__NavToLayerState; // 0x50
	private static DelegateBridge __Hotfix0_OnQuickFormatClick; // 0x58
	private static DelegateBridge __Hotfix0_OnBtnQuit; // 0x60
	private static DelegateBridge __Hotfix0__SendSettleGameRequest; // 0x68
	private static DelegateBridge __Hotfix0_OnBtnAssistClick; // 0x70
	private static DelegateBridge __Hotfix0__EventOnAssistClean; // 0x78
	private static DelegateBridge __Hotfix0__EventOnGetAssist; // 0x80
	private static DelegateBridge __Hotfix0__EventOnSingleFormatClick; // 0x88
	private static DelegateBridge __Hotfix0__EventOnMultiFormatClick; // 0x90
	private static DelegateBridge __Hotfix0__ParseSquadSelectParam; // 0x98
	private static DelegateBridge __Hotfix0__EventOnMenuButtonClick; // 0xa0
	private static DelegateBridge __Hotfix0__GetProfessionCharCount; // 0xa8
	private static DelegateBridge __Hotfix0__InitSquad; // 0xb0
	private static DelegateBridge __Hotfix0__NavToTowreLayerState; // 0xb8
	private static DelegateBridge __Hotfix0__SaveDataToLocalCache; // 0xc0
	private static DelegateBridge __Hotfix0__SaveTowerSelectModeToCache; // 0xc8
	private static DelegateBridge __Hotfix0__TriggerTutorialCoroutine; // 0xd0
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0xd8
	private static DelegateBridge __Hotfix0__WaitAndTrigTutorial; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8


	// RVA: 0x2cae708 VA: 0x75952c6708
	protected override Void OnEnter() { }
	// RVA: 0x2cae97c VA: 0x75952c697c
	private Void _InitIfNot() { }
	// RVA: 0x2caec04 VA: 0x75952c6c04
	protected override Void OnResume() { }
	// RVA: 0x2caed60 VA: 0x75952c6d60
	protected override Void OnPause() { }
	// RVA: 0x2caee7c VA: 0x75952c6e7c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2caeee4 VA: 0x75952c6ee4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2caf0d8 VA: 0x75952c70d8
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2caf150 VA: 0x75952c7150
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2caf344 VA: 0x75952c7344
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x2caf3ac VA: 0x75952c73ac
	public SquadGroupViewModel GetSquadGroupViewModel() { }
	// RVA: 0x2caf438 VA: 0x75952c7438
	private Void _NavToLayerState() { }
	// RVA: 0x2caf5b4 VA: 0x75952c75b4
	public Void OnQuickFormatClick() { }
	// RVA: 0x2caf82c VA: 0x75952c782c
	public Void OnBtnQuit() { }
	// RVA: 0x2cafab0 VA: 0x75952c7ab0
	private Void _SendSettleGameRequest() { }
	// RVA: 0x2cafc80 VA: 0x75952c7c80
	public Void OnBtnAssistClick() { }
	// RVA: 0x2cb012c VA: 0x75952c812c
	private Void _EventOnAssistClean(Int32 memberIndex) { }
	// RVA: 0x2cafdec VA: 0x75952c7dec
	private Void _EventOnGetAssist(Int32 index) { }
	// RVA: 0x2cb02a4 VA: 0x75952c82a4
	private Void _EventOnSingleFormatClick(Int32 memberIndex) { }
	// RVA: 0x2caf61c VA: 0x75952c761c
	private Void _EventOnMultiFormatClick() { }
	// RVA: 0x2cb04c8 VA: 0x75952c84c8
	private Input _ParseSquadSelectParam(Boolean isSingleMode, Int32 memberIndex) { }
	// RVA: 0x2cb0a84 VA: 0x75952c8a84
	private Void _EventOnMenuButtonClick() { }
	// RVA: 0x2cb1414 VA: 0x75952c9414
	private Int32 _GetProfessionCharCount(ProfessionCategory profession) { }
	// RVA: 0x2cb0dbc VA: 0x75952c8dbc
	private Void _InitSquad() { }
	// RVA: 0x2cb151c VA: 0x75952c951c
	private Void _NavToTowreLayerState() { }
	// RVA: 0x2cb162c VA: 0x75952c962c
	private Void _SaveDataToLocalCache() { }
	// RVA: 0x2cb16a8 VA: 0x75952c96a8
	private Void _SaveTowerSelectModeToCache() { }
	// RVA: 0x2caecb8 VA: 0x75952c6cb8
	private Void _TriggerTutorialCoroutine() { }
	// RVA: 0x2caedd4 VA: 0x75952c6dd4
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x2cb1808 VA: 0x75952c9808
	private IEnumerator _WaitAndTrigTutorial() { }
	// RVA: 0x2cb18b4 VA: 0x75952c98b4
	public Void .ctor() { }
	// RVA: 0x2cb19b4 VA: 0x75952c99b4
	private Void <RegisterToDataListener>b__20_0(IStateBean stateBean) { }
	// RVA: 0x2cb1a6c VA: 0x75952c9a6c
	private Void <RegisterToDataListener>b__20_1(IStateBean stateBean) { }
	// RVA: 0x2cb1b48 VA: 0x75952c9b48
	private Void <RegisterFromDataListener>b__22_0(IStateBean stateBean) { }
	// RVA: 0x2cb1c28 VA: 0x75952c9c28
	private Void <RegisterFromDataListener>b__22_1(IStateBean friendAssistBean) { }
	// RVA: 0x2cb1d00 VA: 0x75952c9d00
	private Void <_SendSettleGameRequest>b__28_0(ClimbTowerSettleGameResponse response) { }
	// RVA: 0x2cb1d04 VA: 0x75952c9d04
	private Void <_InitSquad>b__37_0(ClimbTowerInitSquadResponse response) { }
	// RVA: 0x2cb1d08 VA: 0x75952c9d08
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2cb1d10 VA: 0x75952c9d10
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2cb1d18 VA: 0x75952c9d18
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2cb1d20 VA: 0x75952c9d20
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2cb1d28 VA: 0x75952c9d28
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2cb1d30 VA: 0x75952c9d30
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```
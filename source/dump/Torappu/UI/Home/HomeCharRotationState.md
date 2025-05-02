# HomeCharRotationState

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeCharRotationView _view`

- `RectTransform _dialogContainer`

- `RectTransform _backPressRect`

- `RectTransform _charRotationListBackPressRect`

- `UIAnimationLocation _animShow`

- `CanvasGroup _rootCanvasGroup`

- `Boolean m_hasInited`

- `UICompDialogMgr m_dialogMgr`

- `Int32 m_dialogInstId`

- `InputParams m_toChangeSkinParams`

- `InputParams m_toChangeCharParams`

- `UISwitchTween m_showTween`

- `HomeIllustView m_illustView`

- `DisplayHandler m_illustDisplayHandler`

- `Int32 m_instId`

- `HomeCharRotationStateBean m_stateBean`


## Methods

- `Void OnDestroy()`

- `Void _EventToOpenHomeBackGroundChangeState(IStateBean)`

- `Void _EventToOpenHomeThemeChangeState(IStateBean)`

- `Void _EventRoutedFromBackgroundAndThemeChangeState(IStateBean)`

- `Void _EventRoutedFromSkinSelectState(IStateBean)`

- `Boolean _IsStateStable()`

- `Void _InitIfNot()`

- `Void _TryPlayDynEntranceOnBack()`

- `Void _StartPreviewMode()`

- `Void _ExitPreviewMode()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _ChangeListShow(Int64)`

- `Void _SelectSkinInRotationList(String)`

- `Void _OpenChangeSecretaryState()`

- `Void _OpenPresetListDialog()`

- `Void _OpenChangeSecretarySkinState()`

- `Void _OpenChangeBackgroundState()`

- `Void _OpenChangeThemeState()`

- `Void _OpenIllustEditState()`

- `Void _SetSecretary(String)`

- `Void _OnPresetListBtnClicked(Int64)`

- `Void _OnSkinListBtnClicked(Int64)`

- `Void _SetDisplay()`

- `Void _OnSetDisplaySucceed(String, String)`

- `Void OnBtnBackClicked()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _ModifyIllustViewConfig(Boolean)`

- `Void _SyncIllustView()`

- `Void _UpdateIllustView(Boolean)`

- `Void _DisposeIllustConfig()`

- `Void _UpdateHomeBackgroundAndTheme()`

- `Void <RegisterToDataListener>b__36_0(IStateBean)`

- `Void <RegisterToDataListener>b__36_1(IStateBean)`

- `Void <_InitIfNot>b__42_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationState : HomeReplaceableState, IValueMsgReceiver, ICompDialogCallBack
{
	public const Int32 CHANGE_ROTATION_LIST; // 0x0
	public const Int32 SELECT_SKIN_IN_ROTATION_LIST; // 0x0
	public const Int32 OPEN_SECRETARY_CHANGE_STATE; // 0x0
	public const Int32 OPEN_PRESET_LIST_DIALOG; // 0x0
	public const Int32 OPEN_SECRETARY_CHANGE_SKIN_STATE; // 0x0
	public const Int32 SET_SECRETARY; // 0x0
	public const Int32 ON_PRESET_LIST_BTN_CLICKED; // 0x0
	public const Int32 ON_SKIN_LIST_BTN_CLICKED; // 0x0
	public const Int32 SET_DISPLAY; // 0x0
	public const Int32 OPEN_BACKGROUND_CHANGE_STATE; // 0x0
	public const Int32 OPEN_THEME_CHANGE_STATE; // 0x0
	public const Int32 OPEN_ILLUST_EDIT_STATE; // 0x0
	private HomeCharRotationView _view; // 0x60
	private RectTransform _dialogContainer; // 0x68
	private RectTransform _backPressRect; // 0x70
	private RectTransform _charRotationListBackPressRect; // 0x78
	private UIAnimationLocation _animShow; // 0x80
	private CanvasGroup _rootCanvasGroup; // 0x90
	private Boolean m_hasInited; // 0x98
	private UICompDialogMgr m_dialogMgr; // 0xa0
	private Int32 m_dialogInstId; // 0xa8
	private InputParams m_toChangeSkinParams; // 0xb0
	private InputParams m_toChangeCharParams; // 0xd0
	private UISwitchTween m_showTween; // 0xe0
	private HomeIllustView m_illustView; // 0xe8
	private DisplayHandler m_illustDisplayHandler; // 0xf0
	private Int32 m_instId; // 0xf8
	private HomeCharRotationStateBean m_stateBean; // 0x100
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnPause; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x30
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x38
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x40
	private static DelegateBridge __Hotfix0__EventToOpenHomeBackGroundChangeState; // 0x48
	private static DelegateBridge __Hotfix0__EventToOpenHomeThemeChangeState; // 0x50
	private static DelegateBridge __Hotfix0__EventRoutedFromBackgroundAndThemeChangeState; // 0x58
	private static DelegateBridge __Hotfix0__EventRoutedFromSkinSelectState; // 0x60
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x70
	private static DelegateBridge __Hotfix0__TryPlayDynEntranceOnBack; // 0x78
	private static DelegateBridge __Hotfix0__StartPreviewMode; // 0x80
	private static DelegateBridge __Hotfix0__ExitPreviewMode; // 0x88
	private static DelegateBridge __Hotfix0_HideEffect; // 0x90
	private static DelegateBridge __Hotfix0_HideFastMode; // 0x98
	private static DelegateBridge __Hotfix0_ShowEffect; // 0xa0
	private static DelegateBridge __Hotfix0_ShowFastMode; // 0xa8
	private static DelegateBridge __Hotfix0_OnMessage; // 0xb0
	private static DelegateBridge __Hotfix0__ChangeListShow; // 0xb8
	private static DelegateBridge __Hotfix0__SelectSkinInRotationList; // 0xc0
	private static DelegateBridge __Hotfix0__OpenChangeSecretaryState; // 0xc8
	private static DelegateBridge __Hotfix0__OpenPresetListDialog; // 0xd0
	private static DelegateBridge __Hotfix0__OpenChangeSecretarySkinState; // 0xd8
	private static DelegateBridge __Hotfix0__OpenChangeBackgroundState; // 0xe0
	private static DelegateBridge __Hotfix0__OpenChangeThemeState; // 0xe8
	private static DelegateBridge __Hotfix0__OpenIllustEditState; // 0xf0
	private static DelegateBridge __Hotfix0__SetSecretary; // 0xf8
	private static DelegateBridge __Hotfix0__OnPresetListBtnClicked; // 0x100
	private static DelegateBridge __Hotfix0__OnSkinListBtnClicked; // 0x108
	private static DelegateBridge __Hotfix0__SetDisplay; // 0x110
	private static DelegateBridge __Hotfix0__OnSetDisplaySucceed; // 0x118
	private static DelegateBridge __Hotfix0_OnBtnBackClicked; // 0x120
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x128
	private static DelegateBridge __Hotfix0__ModifyIllustViewConfig; // 0x130
	private static DelegateBridge __Hotfix0__SyncIllustView; // 0x138
	private static DelegateBridge __Hotfix0__UpdateIllustView; // 0x140
	private static DelegateBridge __Hotfix0__DisposeIllustConfig; // 0x148
	private static DelegateBridge __Hotfix0__UpdateHomeBackgroundAndTheme; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158


	// RVA: 0x27eaccc VA: 0x7594e02ccc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27ead34 VA: 0x7594e02d34
	protected override Void OnEnter() { }
	// RVA: 0x27eb174 VA: 0x7594e03174
	protected override Void OnResume() { }
	// RVA: 0x27eb3a4 VA: 0x7594e033a4
	protected override Void OnPause() { }
	// RVA: 0x27eb540 VA: 0x7594e03540
	protected override Void OnExit() { }
	// RVA: 0x27eb6e4 VA: 0x7594e036e4
	protected Void OnDestroy() { }
	// RVA: 0x27eb754 VA: 0x7594e03754
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x27eb7d0 VA: 0x7594e037d0
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x27eba2c VA: 0x7594e03a2c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x27ebd00 VA: 0x7594e03d00
	private Void _EventToOpenHomeBackGroundChangeState(IStateBean stateBean) { }
	// RVA: 0x27ebe28 VA: 0x7594e03e28
	private Void _EventToOpenHomeThemeChangeState(IStateBean stateBean) { }
	// RVA: 0x27ebf64 VA: 0x7594e03f64
	private Void _EventRoutedFromBackgroundAndThemeChangeState(IStateBean stateBean) { }
	// RVA: 0x27ec250 VA: 0x7594e04250
	private Void _EventRoutedFromSkinSelectState(IStateBean stateBean) { }
	// RVA: 0x27ec398 VA: 0x7594e04398
	private Boolean _IsStateStable() { }
	// RVA: 0x27eae14 VA: 0x7594e02e14
	private Void _InitIfNot() { }
	// RVA: 0x27ec488 VA: 0x7594e04488
	private Void _TryPlayDynEntranceOnBack() { }
	// RVA: 0x27eb27c VA: 0x7594e0327c
	private Void _StartPreviewMode() { }
	// RVA: 0x27eb418 VA: 0x7594e03418
	private Void _ExitPreviewMode() { }
	// RVA: 0x27ec6bc VA: 0x7594e046bc
	protected override IEnumerator HideEffect() { }
	// RVA: 0x27ec790 VA: 0x7594e04790
	protected override Void HideFastMode() { }
	// RVA: 0x27ec81c VA: 0x7594e0481c
	protected override IEnumerator ShowEffect(HomeReplaceableState extractState) { }
	// RVA: 0x27ec914 VA: 0x7594e04914
	protected override Void ShowFastMode() { }
	// RVA: 0x27ec9a0 VA: 0x7594e049a0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x27ecb7c VA: 0x7594e04b7c
	private Void _ChangeListShow(Int64 intVal) { }
	// RVA: 0x27ecc84 VA: 0x7594e04c84
	private Void _SelectSkinInRotationList(String skinId) { }
	// RVA: 0x27ecd70 VA: 0x7594e04d70
	private Void _OpenChangeSecretaryState() { }
	// RVA: 0x27ecee4 VA: 0x7594e04ee4
	private Void _OpenPresetListDialog() { }
	// RVA: 0x27ed0f4 VA: 0x7594e050f4
	private Void _OpenChangeSecretarySkinState() { }
	// RVA: 0x27edac0 VA: 0x7594e05ac0
	private Void _OpenChangeBackgroundState() { }
	// RVA: 0x27edc24 VA: 0x7594e05c24
	private Void _OpenChangeThemeState() { }
	// RVA: 0x27edd88 VA: 0x7594e05d88
	private Void _OpenIllustEditState() { }
	// RVA: 0x27ed258 VA: 0x7594e05258
	private Void _SetSecretary(String skinId) { }
	// RVA: 0x27ed5f0 VA: 0x7594e055f0
	private Void _OnPresetListBtnClicked(Int64 direction) { }
	// RVA: 0x27ed708 VA: 0x7594e05708
	private Void _OnSkinListBtnClicked(Int64 direction) { }
	// RVA: 0x27ed804 VA: 0x7594e05804
	private Void _SetDisplay() { }
	// RVA: 0x27edeb0 VA: 0x7594e05eb0
	private Void _OnSetDisplaySucceed(String instId, String skinId) { }
	// RVA: 0x27ee038 VA: 0x7594e06038
	public Void OnBtnBackClicked() { }
	// RVA: 0x27ee184 VA: 0x7594e06184
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x27ee2c8 VA: 0x7594e062c8
	private Void _ModifyIllustViewConfig(Boolean show) { }
	// RVA: 0x27ee468 VA: 0x7594e06468
	private Void _SyncIllustView() { }
	// RVA: 0x27eb1f4 VA: 0x7594e031f4
	private Void _UpdateIllustView(Boolean show) { }
	// RVA: 0x27eb664 VA: 0x7594e03664
	private Void _DisposeIllustConfig() { }
	// RVA: 0x27ec050 VA: 0x7594e04050
	private Void _UpdateHomeBackgroundAndTheme() { }
	// RVA: 0x27ee4e4 VA: 0x7594e064e4
	public Void .ctor() { }
	// RVA: 0x27ee594 VA: 0x7594e06594
	private Void <RegisterToDataListener>b__36_0(IStateBean stateBean) { }
	// RVA: 0x27ee6a0 VA: 0x7594e066a0
	private Void <RegisterToDataListener>b__36_1(IStateBean stateBean) { }
	// RVA: 0x27ee7a8 VA: 0x7594e067a8
	private Void <_InitIfNot>b__42_0() { }
	// RVA: 0x27ee7b0 VA: 0x7594e067b0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27ee7b8 VA: 0x7594e067b8
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x27ee7c0 VA: 0x7594e067c0
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x27ee7c8 VA: 0x7594e067c8
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x27ee7d0 VA: 0x7594e067d0
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x27ee7d8 VA: 0x7594e067d8
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x27ee7e0 VA: 0x7594e067e0
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```
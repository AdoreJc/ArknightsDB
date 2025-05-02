# UIPopupWindow

**Namespace:** `Torappu.UI`


## Fields

- `Camera _uiCamera`

- `UIReentrantFloatPanel _blackMask`

- `Shader _blurShader`

- `Image _blurMask`

- `UIGuidebookPanel _guidebookPanel`

- `CanvasGroup _panelDialog`

- `UITransloadingMask _transloadingMask`

- `UIInvisLoadingMask _invisLoadingMask`

- `SafeParentComponent _dialogContainer`

- `UIToast _toast`

- `UIReentrantFloatPanel _raycastBlocker`

- `UIReentrantFloatPanel _reentrantLoadingMask`

- `CommonLoadingController _sceneLoadingMask`

- `Tween m_dialogTween`

- `Boolean m_isDialogPanelShown`

- `Int32 m_showCameraCtr`

- `Int64 m_activeBlockerIndex`

- `SceneLoadingState m_sceneLoadingState`

- `ReentrantFloatOpt m_sceneLoading`

- `String m_sceneLoadingIllust`


## Methods

- `Boolean IsBlackMaskShown()`

- `IEnumerator _ShowBlackLoadingMask()`

- `IEnumerator _HideBlackLoadingMask()`

- `Boolean IsCommonDialogsShowing()`

- `CommonDialog _ShowDialog(Type, ShowOptions)`

- `Boolean _DeduplicateDialogInstance(ShowOptions)`

- `Void HideDialog(CommonDialog, Action)`

- `Void _UpdatePanelDialogStatus(Action)`

- `Void _SetDialogStatusAsMarked()`

- `Void _Alert(String, Action)`

- `Void _Alerts(List`1, Action)`

- `Void _TestBound3DLayoutForce()`

- `Void _TestBound3DLayout()`

- `Void _OpenGuidebook(IList`1, Int32, Action)`

- `UIBlocker _RequestRaycastBlocker()`

- `Void _ReleaseRaycastBlocker(Int64)`

- `Void _BlockRaycast()`

- `Void _UnblockRaycast()`

- `IEnumerator _HideReentrantLoadingCoroutine()`

- `ReentrantFloatOpt _EnsureSceneLoading()`

- `Boolean _IsSceneLoadingVisible()`

- `IEnumerator _ShowSceneLoading()`

- `IEnumerator _HideSceneLoading()`

- `Boolean IsFullScreenMaskVisible()`

- `CommonDialog _FindCommonDialogPrefab(Type)`

- `Boolean _IsWindowActive()`

- `Void _SetWindowActive()`

- `Void _SetWindowInactive()`

- `IEnumerator _NextFrameCoroutine(Action)`

- `Void _ClearBlurMask()`

- `Sprite _ShotBlurredCamera(ShotOption)`

- `Void _OnSceneUnloaded(Scene)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPopupWindow : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, ILuaCallCSharp, IHotfixable
{
	private Camera _uiCamera; // 0x18
	private UIReentrantFloatPanel _blackMask; // 0x20
	private Shader _blurShader; // 0x28
	private Image _blurMask; // 0x30
	private UIGuidebookPanel _guidebookPanel; // 0x38
	private CanvasGroup _panelDialog; // 0x40
	private UITransloadingMask _transloadingMask; // 0x48
	private UIInvisLoadingMask _invisLoadingMask; // 0x50
	private CommonDialog[] _dialogPrefabs; // 0x58
	private SafeParentComponent _dialogContainer; // 0x60
	private UIToast _toast; // 0x68
	private UIReentrantFloatPanel _raycastBlocker; // 0x70
	private UIReentrantFloatPanel _reentrantLoadingMask; // 0x78
	private CommonLoadingController _sceneLoadingMask; // 0x80
	private Tween m_dialogTween; // 0x88
	private Boolean m_isDialogPanelShown; // 0x90
	private Int32 m_showCameraCtr; // 0x94
	private List`1 m_dialogInsts; // 0x98
	private const Int64 UIBLOCKER_INVALID_ID; // 0x0
	private ListSet`1 m_activeBlockers; // 0xa0
	private Int64 m_activeBlockerIndex; // 0xa8
	private SceneLoadingState m_sceneLoadingState; // 0xb0
	private ReentrantFloatOpt m_sceneLoading; // 0xb8
	private String m_sceneLoadingIllust; // 0xc0
	private static DelegateBridge __Hotfix0_IsBlackLoadingVisible; // 0x0
	private static DelegateBridge __Hotfix0_IsBlackMaskShown; // 0x8
	private static DelegateBridge __Hotfix0_ShowBlackLoadingMask; // 0x10
	private static DelegateBridge __Hotfix0_RequestBlackLoadingOpt; // 0x18
	private static DelegateBridge __Hotfix0_HideBlackLoadingMask; // 0x20
	private static DelegateBridge __Hotfix0_GetHideBlackLoadingMaskEnumerator; // 0x28
	private static DelegateBridge __Hotfix0__ShowBlackLoadingMask; // 0x30
	private static DelegateBridge __Hotfix0__HideBlackLoadingMask; // 0x38
	private static DelegateBridge __Hotfix0_get_transLoadingMask; // 0x40
	private static DelegateBridge __Hotfix0_get_invisLoadingMask; // 0x48
	private static DelegateBridge __Hotfix0_ShowFloatLoadingMask; // 0x50
	private static DelegateBridge __Hotfix0_HideFloatLoadingMask; // 0x58
	private static DelegateBridge __Hotfix0_ShowTransLoadingMask; // 0x60
	private static DelegateBridge __Hotfix0_HideTransLoadingMask; // 0x68
	private static DelegateBridge __Hotfix0__InstantiateCommonDialog; // 0x70
	private static DelegateBridge __Hotfix0_IsCommonDialogsShowing; // 0x78
	private static DelegateBridge __Hotfix0_ShowDialog; // 0x80
	private static DelegateBridge __Hotfix0_ComplexShowDialog; // 0x88
	private static DelegateBridge __Hotfix0__ShowDialog; // 0x90
	private static DelegateBridge __Hotfix0__DeduplicateDialogInstance; // 0x98
	private static DelegateBridge __Hotfix0_HideDialog; // 0xa0
	private static DelegateBridge __Hotfix0__UpdatePanelDialogStatus; // 0xa8
	private static DelegateBridge __Hotfix0__SetDialogStatusAsMarked; // 0xb0
	private static DelegateBridge __Hotfix0_Alert; // 0xb8
	private static DelegateBridge __Hotfix0__Alert; // 0xc0
	private static DelegateBridge __Hotfix0_Alerts; // 0xc8
	private static DelegateBridge __Hotfix0__Alerts; // 0xd0
	private static DelegateBridge __Hotfix0_AlertsByResponse; // 0xd8
	private static DelegateBridge __Hotfix0_Toast; // 0xe0
	private static DelegateBridge __Hotfix0__TestBound3DLayoutForce; // 0xe8
	private static DelegateBridge __Hotfix0__TestBound3DLayout; // 0xf0
	private static DelegateBridge __Hotfix0_IsGuidebookOpen; // 0xf8
	private static DelegateBridge __Hotfix0_OpenGuidebook; // 0x100
	private static DelegateBridge __Hotfix1_OpenGuidebook; // 0x108
	private static DelegateBridge __Hotfix0_OpenGuidebookExt; // 0x110
	private static DelegateBridge __Hotfix0__OpenGuidebook; // 0x118
	private static DelegateBridge __Hotfix0_BlockRaycast; // 0x120
	private static DelegateBridge __Hotfix0_WrapWithBlockRaycast; // 0x128
	private static DelegateBridge __Hotfix0__RequestRaycastBlocker; // 0x130
	private static DelegateBridge __Hotfix0__ReleaseRaycastBlocker; // 0x138
	private static DelegateBridge __Hotfix0__BlockRaycast; // 0x140
	private static DelegateBridge __Hotfix0__UnblockRaycast; // 0x148
	private static DelegateBridge __Hotfix0_ShowReentrantLoading; // 0x150
	private static DelegateBridge __Hotfix0_HideReentrantLoading; // 0x158
	private static DelegateBridge __Hotfix0__HideReentrantLoadingCoroutine; // 0x160
	private static DelegateBridge __Hotfix0__EnsureSceneLoading; // 0x168
	private static DelegateBridge __Hotfix0__IsSceneLoadingVisible; // 0x170
	private static DelegateBridge __Hotfix0__ShowSceneLoading; // 0x178
	private static DelegateBridge __Hotfix0__HideSceneLoading; // 0x180
	private static DelegateBridge __Hotfix0_ShowSceneLoading; // 0x188
	private static DelegateBridge __Hotfix0_HideSceneLoading; // 0x190
	private static DelegateBridge __Hotfix0_RequestSceneLoadingOpt; // 0x198
	private static DelegateBridge __Hotfix0__StartHideSceneLoadingCoroutine; // 0x1a0
	private static DelegateBridge __Hotfix0_RequestSceneOrBlackLoading; // 0x1a8
	private static DelegateBridge __Hotfix0_IsFullScreenMaskVisible; // 0x1b0
	private static DelegateBridge __Hotfix0__FindCommonDialogPrefab; // 0x1b8
	private static DelegateBridge __Hotfix0__IsWindowActive; // 0x1c0
	private static DelegateBridge __Hotfix0__SetWindowActive; // 0x1c8
	private static DelegateBridge __Hotfix0__SetWindowInactive; // 0x1d0
	private static DelegateBridge __Hotfix0__NextFrameCoroutine; // 0x1d8
	private static DelegateBridge __Hotfix0_ShotBlurredImage; // 0x1e0
	private static DelegateBridge __Hotfix0_ShotBlurredImageWithOption; // 0x1e8
	private static DelegateBridge __Hotfix0_FindViewableCameras; // 0x1f0
	private static DelegateBridge __Hotfix0__ClearBlurMask; // 0x1f8
	private static DelegateBridge __Hotfix0__ShotBlurredCamera; // 0x200
	private static DelegateBridge __Hotfix0__OnSceneUnloaded; // 0x208
	private static DelegateBridge __Hotfix0_OnInit; // 0x210
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x218
	private static DelegateBridge _c__Hotfix0_ctor; // 0x220

	public static UITransloadingMask transLoadingMask { get; }
	public static UIInvisLoadingMask invisLoadingMask { get; }

	// RVA: 0x224d1f4 VA: 0x75948651f4
	public static Boolean IsBlackLoadingVisible() { }
	// RVA: 0x224d2c8 VA: 0x75948652c8
	public Boolean IsBlackMaskShown() { }
	// RVA: 0x224d33c VA: 0x759486533c
	public static IEnumerator ShowBlackLoadingMask() { }
	// RVA: 0x224d468 VA: 0x7594865468
	public static ReentrantFloatRef RequestBlackLoadingOpt() { }
	// RVA: 0x224d638 VA: 0x7594865638
	public static Void HideBlackLoadingMask() { }
	// RVA: 0x224d788 VA: 0x7594865788
	public static IEnumerator GetHideBlackLoadingMaskEnumerator() { }
	// RVA: 0x224d3bc VA: 0x75948653bc
	private IEnumerator _ShowBlackLoadingMask() { }
	// RVA: 0x224d6dc VA: 0x75948656dc
	private IEnumerator _HideBlackLoadingMask() { }
	// RVA: 0x224d858 VA: 0x7594865858
	public static UITransloadingMask get_transLoadingMask() { }
	// RVA: 0x224d8dc VA: 0x75948658dc
	public static UIInvisLoadingMask get_invisLoadingMask() { }
	// RVA: 0x224d960 VA: 0x7594865960
	public static Void ShowFloatLoadingMask(UIFloatMask floatMask, Action callback) { }
	// RVA: 0x224dae8 VA: 0x7594865ae8
	public static Void HideFloatLoadingMask(UIFloatMask floatMask, Action callback) { }
	// RVA: 0x224dc58 VA: 0x7594865c58
	public static Void ShowTransLoadingMask() { }
	// RVA: 0x224dcbc VA: 0x7594865cbc
	public static Void HideTransLoadingMask(Action callback) { }
	// RVA: 0x224dd28 VA: 0x7594865d28
	private static CommonDialog _InstantiateCommonDialog(CommonDialog prefab, SafeParentComponent parent) { }
	// RVA: 0x224ded4 VA: 0x7594865ed4
	public Boolean IsCommonDialogsShowing() { }
	// RVA: 0x VA: 0x0
	public static DialogType ShowDialog() { }
	// RVA: 0x VA: 0x0
	public static DialogType ComplexShowDialog(ShowOptions showOptions) { }
	// RVA: 0x224df3c VA: 0x7594865f3c
	private CommonDialog _ShowDialog(Type dialogType, ShowOptions options) { }
	// RVA: 0x224e2a0 VA: 0x75948662a0
	private Boolean _DeduplicateDialogInstance(ShowOptions showRequest) { }
	// RVA: 0x224ea00 VA: 0x7594866a00
	public Void HideDialog(CommonDialog dialog, Action callback) { }
	// RVA: 0x224e5b4 VA: 0x75948665b4
	private Void _UpdatePanelDialogStatus(Action callback) { }
	// RVA: 0x224eae0 VA: 0x7594866ae0
	private Void _SetDialogStatusAsMarked() { }
	// RVA: 0x224f070 VA: 0x7594867070
	public static Void Alert(String content, Action onConfirm) { }
	// RVA: 0x224f114 VA: 0x7594867114
	private Void _Alert(String content, Action onConfirm) { }
	// RVA: 0x224f2dc VA: 0x75948672dc
	public static Void Alerts(List`1 alertList, Action onFinish) { }
	// RVA: 0x224f380 VA: 0x7594867380
	private Void _Alerts(List`1 alertList, Action onFinish) { }
	// RVA: 0x224f674 VA: 0x7594867674
	public static Void AlertsByResponse(IAlertResponse response, Action onFinish) { }
	// RVA: 0x224f8c4 VA: 0x75948678c4
	public static Void Toast(String content) { }
	// RVA: 0x224fd38 VA: 0x7594867d38
	private Void _TestBound3DLayoutForce() { }
	// RVA: 0x224fda4 VA: 0x7594867da4
	private Void _TestBound3DLayout() { }
	// RVA: 0x224fe0c VA: 0x7594867e0c
	public static Boolean IsGuidebookOpen() { }
	// RVA: 0x224fe94 VA: 0x7594867e94
	public static Void OpenGuidebook(IList`1 pageIds, Action onFinish) { }
	// RVA: 0x22500a4 VA: 0x75948680a4
	public static Void OpenGuidebook(String pageId, Action onFinish) { }
	// RVA: 0x22501c0 VA: 0x75948681c0
	public static Void OpenGuidebookExt(String[] pageids, Int32 forceRead, Action onFinish) { }
	// RVA: 0x224ff3c VA: 0x7594867f3c
	private Void _OpenGuidebook(IList`1 pageIds, Int32 forceRead, Action onFinish) { }
	// RVA: 0x2250278 VA: 0x7594868278
	public static UIBlocker BlockRaycast() { }
	// RVA: 0x225047c VA: 0x759486847c
	public static IEnumerator WrapWithBlockRaycast(IEnumerator routine) { }
	// RVA: 0x2250378 VA: 0x7594868378
	private UIBlocker _RequestRaycastBlocker() { }
	// RVA: 0x22505d0 VA: 0x75948685d0
	private Void _ReleaseRaycastBlocker(Int64 id) { }
	// RVA: 0x2250550 VA: 0x7594868550
	private Void _BlockRaycast() { }
	// RVA: 0x22506dc VA: 0x75948686dc
	private Void _UnblockRaycast() { }
	// RVA: 0x22507f0 VA: 0x75948687f0
	public static Void ShowReentrantLoading() { }
	// RVA: 0x22508d0 VA: 0x75948688d0
	public static Void HideReentrantLoading() { }
	// RVA: 0x22509b0 VA: 0x75948689b0
	private IEnumerator _HideReentrantLoadingCoroutine() { }
	// RVA: 0x2250a84 VA: 0x7594868a84
	private ReentrantFloatOpt _EnsureSceneLoading() { }
	// RVA: 0x2250be0 VA: 0x7594868be0
	private Boolean _IsSceneLoadingVisible() { }
	// RVA: 0x2250c84 VA: 0x7594868c84
	private IEnumerator _ShowSceneLoading() { }
	// RVA: 0x2250d58 VA: 0x7594868d58
	private IEnumerator _HideSceneLoading() { }
	// RVA: 0x2250e2c VA: 0x7594868e2c
	public static IEnumerator ShowSceneLoading(String loadingIllust) { }
	// RVA: 0x2250ef0 VA: 0x7594868ef0
	public static IEnumerator HideSceneLoading() { }
	// RVA: 0x2250fac VA: 0x7594868fac
	public static ReentrantFloatRef RequestSceneLoadingOpt() { }
	// RVA: 0x22510d0 VA: 0x75948690d0
	private static Void _StartHideSceneLoadingCoroutine() { }
	// RVA: 0x2251170 VA: 0x7594869170
	public static ReentrantFloatRef RequestSceneOrBlackLoading() { }
	// RVA: 0x2251210 VA: 0x7594869210
	public Boolean IsFullScreenMaskVisible() { }
	// RVA: 0x224e188 VA: 0x7594866188
	private CommonDialog _FindCommonDialogPrefab(Type dialogType) { }
	// RVA: 0x2251294 VA: 0x7594869294
	private Boolean _IsWindowActive() { }
	// RVA: 0x224da54 VA: 0x7594865a54
	private Void _SetWindowActive() { }
	// RVA: 0x2250758 VA: 0x7594868758
	private Void _SetWindowInactive() { }
	// RVA: 0x2251304 VA: 0x7594869304
	private IEnumerator _NextFrameCoroutine(Action action) { }
	// RVA: 0x224ebf4 VA: 0x7594866bf4
	public static Sprite ShotBlurredImage(Image outputImage) { }
	// RVA: 0x22514e0 VA: 0x75948694e0
	public static Sprite ShotBlurredImageWithOption(Image outputImage, ShotOption shotOption) { }
	// RVA: 0x2251828 VA: 0x7594869828
	public static List`1 FindViewableCameras(ShotOption shotOption) { }
	// RVA: 0x224ef6c VA: 0x7594866f6c
	private Void _ClearBlurMask() { }
	// RVA: 0x22513ec VA: 0x75948693ec
	private Sprite _ShotBlurredCamera(ShotOption shotOption) { }
	// RVA: 0x2251c74 VA: 0x7594869c74
	private Void _OnSceneUnloaded(Scene scene) { }
	// RVA: 0x2251d2c VA: 0x7594869d2c
	protected override Void OnInit() { }
	// RVA: 0x2251e04 VA: 0x7594869e04
	protected override Void OnDestroy() { }
	// RVA: 0x2251edc VA: 0x7594869edc
	public Void .ctor() { }
}
```
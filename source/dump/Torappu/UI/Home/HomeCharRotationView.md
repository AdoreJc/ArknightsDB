# HomeCharRotationView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _textCurrPresetName`

- `GameObject _pnlPresetLeftBtn`

- `GameObject _pnlPresetRightBtn`

- `Text _textCurrSkinNum`

- `Text _textTotalSkinNum`

- `Text _textCurrSkinName`

- `CanvasGroup _canvasSkinLeftBtn`

- `CanvasGroup _canvasSkinRightBtn`

- `Single _alphaSkinBtnDisabled`

- `RectTransform _charRotationListContainer`

- `HomeCharRotationListPanel _listPanelPrefab`

- `GameObject _pnlRotationListRaycast`

- `TwoStateToggle _setCharToggle`

- `UIAnimationLocation _charRotationListPnlAnimShow`

- `UICommonTrackPoint _presetDialogTrackPoint`

- `UICommonTrackPoint _homeBGTrackPoint`

- `UICommonTrackPoint _homeThemeTrackPoint`

- `GameObject _pnlRaycastRight`

- `CanvasGroup _canvasChangeThemeBtn`

- `CanvasGroup _canvasChangeBackgroundBtn`

- `CanvasGroup _canvasContainerTop`

- `GameObject _nowUsingPresetDecor`

- `UIStateFinder m_stateFinder`

- `Boolean m_cacheShowRotationList`

- `HomeCharRotationListPanel m_listPanel`

- `Boolean m_hasInited`

- `Int32 m_enterSeqNum`

- `UISwitchTween m_charRotationListPnlShowTween`

- `TrackPointViewProperty m_presetTrackProperty`

- `TrackPointViewProperty m_homeBGTrackProperty`

- `TrackPointViewProperty m_homeThemeTrackProperty`


## Properties

- `Boolean isRotationCharListTweening`


## Methods

- `Boolean get_isRotationCharListTweening()`

- `Void _RenderCharRotationPanel(HomeCharRotationViewModel)`

- `Void _InitIfNot()`

- `Void _SetRotationListActive(Boolean)`

- `Void _SetButtonsActive(Boolean)`

- `Void OnPresetLeftBtnClicked()`

- `Void OnPresetRightBtnClicked()`

- `Void OnSkinLeftBtnClicked()`

- `Void OnSkinRightBtnClicked()`

- `Void ChangeRotationList(Boolean)`

- `Void OpenChangeSecretaryState()`

- `Void OpenChangeBackgroundState()`

- `Void OpenChangeThemeState()`

- `Void OpenIllustEditState()`

- `Void OpenCharRotationPresetListViewDialog()`

- `Void OnSetDisplayBtnClicked()`

- `Void <_InitIfNot>b__37_0(Boolean)`

- `Void <_InitIfNot>b__37_1()`

- `Void <_InitIfNot>b__37_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationView : DataBinder`1, IHotfixable
{
	private const String TOTAL_SKIN_NUM_FORMAT; // 0x0
	private const String SKIN_NAME_FORMAT; // 0x0
	private Text _textCurrPresetName; // 0x20
	private GameObject _pnlPresetLeftBtn; // 0x28
	private GameObject _pnlPresetRightBtn; // 0x30
	private Text _textCurrSkinNum; // 0x38
	private Text _textTotalSkinNum; // 0x40
	private Text _textCurrSkinName; // 0x48
	private CanvasGroup _canvasSkinLeftBtn; // 0x50
	private CanvasGroup _canvasSkinRightBtn; // 0x58
	private Single _alphaSkinBtnDisabled; // 0x60
	private RectTransform _charRotationListContainer; // 0x68
	private HomeCharRotationListPanel _listPanelPrefab; // 0x70
	private GameObject _pnlRotationListRaycast; // 0x78
	private TwoStateToggle _setCharToggle; // 0x80
	private UIAnimationLocation _charRotationListPnlAnimShow; // 0x88
	private UICommonTrackPoint _presetDialogTrackPoint; // 0x98
	private UICommonTrackPoint _homeBGTrackPoint; // 0xa0
	private UICommonTrackPoint _homeThemeTrackPoint; // 0xa8
	private GameObject _pnlRaycastRight; // 0xb0
	private CanvasGroup _canvasChangeThemeBtn; // 0xb8
	private CanvasGroup _canvasChangeBackgroundBtn; // 0xc0
	private CanvasGroup _canvasContainerTop; // 0xc8
	private GameObject _nowUsingPresetDecor; // 0xd0
	private UIStateFinder m_stateFinder; // 0xd8
	private Boolean m_cacheShowRotationList; // 0xe8
	private HomeCharRotationListPanel m_listPanel; // 0xf0
	private Boolean m_hasInited; // 0xf8
	private Int32 m_enterSeqNum; // 0xfc
	private UISwitchTween m_charRotationListPnlShowTween; // 0x100
	private TrackPointViewProperty m_presetTrackProperty; // 0x108
	private TrackPointViewProperty m_homeBGTrackProperty; // 0x110
	private TrackPointViewProperty m_homeThemeTrackProperty; // 0x118
	private static DelegateBridge __Hotfix0_get_isRotationCharListTweening; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__RenderCharRotationPanel; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__SetRotationListActive; // 0x20
	private static DelegateBridge __Hotfix0__SetButtonsActive; // 0x28
	private static DelegateBridge __Hotfix0_OnPresetLeftBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnPresetRightBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnSkinLeftBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnSkinRightBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0_ChangeRotationList; // 0x50
	private static DelegateBridge __Hotfix0_OpenChangeSecretaryState; // 0x58
	private static DelegateBridge __Hotfix0_OpenChangeBackgroundState; // 0x60
	private static DelegateBridge __Hotfix0_OpenChangeThemeState; // 0x68
	private static DelegateBridge __Hotfix0_OpenIllustEditState; // 0x70
	private static DelegateBridge __Hotfix0_OpenCharRotationPresetListViewDialog; // 0x78
	private static DelegateBridge __Hotfix0_OnSetDisplayBtnClicked; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Boolean isRotationCharListTweening { get; }

	// RVA: 0x282d3fc VA: 0x7594e453fc
	public Boolean get_isRotationCharListTweening() { }
	// RVA: 0x282d478 VA: 0x7594e45478
	public override Void OnValueChanged(HomeCharRotationProperty property) { }
	// RVA: 0x282d924 VA: 0x7594e45924
	private Void _RenderCharRotationPanel(HomeCharRotationViewModel model) { }
	// RVA: 0x282d620 VA: 0x7594e45620
	private Void _InitIfNot() { }
	// RVA: 0x282dc48 VA: 0x7594e45c48
	private Void _SetRotationListActive(Boolean active) { }
	// RVA: 0x282dd00 VA: 0x7594e45d00
	private Void _SetButtonsActive(Boolean active) { }
	// RVA: 0x282ddb8 VA: 0x7594e45db8
	public Void OnPresetLeftBtnClicked() { }
	// RVA: 0x282dea4 VA: 0x7594e45ea4
	public Void OnPresetRightBtnClicked() { }
	// RVA: 0x282df90 VA: 0x7594e45f90
	public Void OnSkinLeftBtnClicked() { }
	// RVA: 0x282e07c VA: 0x7594e4607c
	public Void OnSkinRightBtnClicked() { }
	// RVA: 0x282e168 VA: 0x7594e46168
	public Void ChangeRotationList(Boolean show) { }
	// RVA: 0x282e278 VA: 0x7594e46278
	public Void OpenChangeSecretaryState() { }
	// RVA: 0x282e31c VA: 0x7594e4631c
	public Void OpenChangeBackgroundState() { }
	// RVA: 0x282e3c0 VA: 0x7594e463c0
	public Void OpenChangeThemeState() { }
	// RVA: 0x282e464 VA: 0x7594e46464
	public Void OpenIllustEditState() { }
	// RVA: 0x282e508 VA: 0x7594e46508
	public Void OpenCharRotationPresetListViewDialog() { }
	// RVA: 0x282e5ac VA: 0x7594e465ac
	public Void OnSetDisplayBtnClicked() { }
	// RVA: 0x282e650 VA: 0x7594e46650
	public Void .ctor() { }
	// RVA: 0x282e784 VA: 0x7594e46784
	private Void <_InitIfNot>b__37_0(Boolean isShow) { }
	// RVA: 0x282e798 VA: 0x7594e46798
	private Void <_InitIfNot>b__37_1() { }
	// RVA: 0x282e7a0 VA: 0x7594e467a0
	private Void <_InitIfNot>b__37_2() { }
}
```
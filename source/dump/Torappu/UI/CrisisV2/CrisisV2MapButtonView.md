# CrisisV2MapButtonView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Image _imgAreaBg`

- `Text _textCurrentScore`

- `UIAnimationLocation _animViewToggle`

- `GameObject _viewToggleGo`

- `GameObject _tempMapHintGo`

- `Text _textTempMapHint`

- `GameObject _btnStartNormalBgGo`

- `GameObject _btnStartHardBgGo`

- `GameObject _hardCoverBgGo`

- `UIAtlasImage _imgScoreHalftone`

- `Color _colorNormalScoreHalftone`

- `Color _colorHardScoreHalftone`

- `GameObject _btnRecordGo`

- `GameObject _displayRecordGo`

- `GameObject _missionCompletePartGo`

- `GameObject _missionNormalPartGo`

- `GameObject _missionClaimedPartGo`

- `Text _textMissionProgress`

- `GameObject _dailyMissionHintGo`

- `Text _textMissionExpire`

- `CrisisV2DiagramView _diagramPrefab`

- `RectTransform _diagramContainer`

- `Single _tweenDuration`

- `CanvasGroup _blackMask`

- `CanvasGroup _scrollTopMask`

- `CanvasGroup _mapButtonView`

- `CanvasGroup _dimensionListCanvasGroup`

- `SimpleLayoutContent _dimensionList`

- `Single _dimensionTweenDuration`

- `UICommonPageEffectHolder _effectHolder`

- `UIDynImage _imgStagePreview`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `String m_cachedAreaBgId`

- `AnimationSwitchTween m_toggleSwitchTween`

- `Boolean m_hasInited`

- `CrisisV2DiagramView m_diagramView`

- `FadeSwitchTween m_buttonViewSwitchTween`

- `FadeSwitchTween m_highlightMaskSwitchTween`

- `FadeSwitchTween m_dimensionSwitchTween`

- `FadeSwitchTween m_scrollTopMaskSwitchTween`

- `DimensionListAdapter m_dimensionAdapter`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateViewToggle(CrisisV2MapModel)`

- `Void EventOnBtnClearAll()`

- `Void EventOnBtnSwitchView()`

- `Void EventOnOpenMissionState()`

- `Void EventOnOpenStageDetailState()`

- `Void EventOnOpenAchieve()`

- `Void EventOnBtnDimension()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapButtonView : DataBinder`1
{
	private Image _imgAreaBg; // 0x20
	private Text _textCurrentScore; // 0x28
	private UIAnimationLocation _animViewToggle; // 0x30
	private GameObject _viewToggleGo; // 0x40
	private GameObject _tempMapHintGo; // 0x48
	private Text _textTempMapHint; // 0x50
	private GameObject _btnStartNormalBgGo; // 0x58
	private GameObject _btnStartHardBgGo; // 0x60
	private GameObject _hardCoverBgGo; // 0x68
	private UIAtlasImage _imgScoreHalftone; // 0x70
	private Color _colorNormalScoreHalftone; // 0x78
	private Color _colorHardScoreHalftone; // 0x88
	private GameObject _btnRecordGo; // 0x98
	private GameObject _displayRecordGo; // 0xa0
	private Text[] _textHighestScoreList; // 0xa8
	private GameObject _missionCompletePartGo; // 0xb0
	private GameObject _missionNormalPartGo; // 0xb8
	private GameObject _missionClaimedPartGo; // 0xc0
	private Text _textMissionProgress; // 0xc8
	private GameObject _dailyMissionHintGo; // 0xd0
	private Text _textMissionExpire; // 0xd8
	private CrisisV2DiagramView _diagramPrefab; // 0xe0
	private RectTransform _diagramContainer; // 0xe8
	private Single _tweenDuration; // 0xf0
	private CanvasGroup _blackMask; // 0xf8
	private CanvasGroup _scrollTopMask; // 0x100
	private CanvasGroup _mapButtonView; // 0x108
	private CanvasGroup _dimensionListCanvasGroup; // 0x110
	private SimpleLayoutContent _dimensionList; // 0x118
	private Single _dimensionTweenDuration; // 0x120
	private UICommonPageEffectHolder _effectHolder; // 0x128
	private UIDynImage _imgStagePreview; // 0x130
	private UIPageFinder m_pageFinder; // 0x138
	private UIStateFinder m_stateFinder; // 0x148
	private String m_cachedAreaBgId; // 0x158
	private AnimationSwitchTween m_toggleSwitchTween; // 0x160
	private Boolean m_hasInited; // 0x168
	private CrisisV2DiagramView m_diagramView; // 0x170
	private FadeSwitchTween m_buttonViewSwitchTween; // 0x178
	private FadeSwitchTween m_highlightMaskSwitchTween; // 0x180
	private FadeSwitchTween m_dimensionSwitchTween; // 0x188
	private FadeSwitchTween m_scrollTopMaskSwitchTween; // 0x190
	private DimensionListAdapter m_dimensionAdapter; // 0x198
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__UpdateViewToggle; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBtnClearAll; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBtnSwitchView; // 0x20
	private static DelegateBridge __Hotfix0_EventOnOpenMissionState; // 0x28
	private static DelegateBridge __Hotfix0_EventOnOpenStageDetailState; // 0x30
	private static DelegateBridge __Hotfix0_EventOnOpenAchieve; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBtnDimension; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2c03858 VA: 0x759521b858
	public override Void OnValueChanged(CrisisV2MapProp property) { }
	// RVA: 0x2c03fbc VA: 0x759521bfbc
	private Void _InitIfNot() { }
	// RVA: 0x2c042b0 VA: 0x759521c2b0
	private Void _UpdateViewToggle(CrisisV2MapModel mapModel) { }
	// RVA: 0x2c04504 VA: 0x759521c504
	public Void EventOnBtnClearAll() { }
	// RVA: 0x2c045a8 VA: 0x759521c5a8
	public Void EventOnBtnSwitchView() { }
	// RVA: 0x2c0464c VA: 0x759521c64c
	public Void EventOnOpenMissionState() { }
	// RVA: 0x2c046f0 VA: 0x759521c6f0
	public Void EventOnOpenStageDetailState() { }
	// RVA: 0x2c04794 VA: 0x759521c794
	public Void EventOnOpenAchieve() { }
	// RVA: 0x2c04838 VA: 0x759521c838
	public Void EventOnBtnDimension() { }
	// RVA: 0x2c048dc VA: 0x759521c8dc
	public Void .ctor() { }
}
```
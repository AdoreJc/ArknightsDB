# CrisisV2MapBagView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `TwoStateToggle _bagProgressBgToggle`

- `TwoStateToggle _dimensionBgToggle`

- `TwoStateToggle _nodeScoreBgToggle`

- `TwoStateToggle _bagScoreBgToggle`

- `GameObject _bagScoreGo`

- `Text _textNodeScoreCurrent`

- `Text _textNodeScoreTotal`

- `Text _textBagScore`

- `Color _colorUnselectScore`

- `Color _colorSelectCurrentScore`

- `Color _colorSelectTotalScore`

- `Color _colorSelectBagScore`

- `Color _colorFullBagScore`

- `Text _textDesc`

- `Color _colorUnselectDesc`

- `Color _colorSelectDesc`

- `GameObject _completedIconGo`

- `Slider _sliderProgerss`

- `Single _sliderTweenDuration`

- `CanvasGroup _alphaHandler`

- `Single _unreachAlpha`

- `GameObject _unreachMaskGo`

- `UIAtlasImage _imgDimension`

- `UIAtlasObject _dimensionAtlas`

- `UIAnimationLocation _animSwitch`

- `UIAnimationLocation _animFocus`

- `GameObject _panelTitle`

- `GameObject _panelBag`

- `GameObject _panelDetail`

- `CanvasGroup _highlightSwitchGroup`

- `CanvasGroup _highlightBreathGroup`

- `UIStateFinder m_stateFinder`

- `CrisisV2MapBagModel m_bagModel`

- `AnimationSwitchTween m_animSwitch`

- `Tween m_focusTween`

- `Int32 m_cacheInteractId`

- `FadeSwitchTween m_highlightSwitchTween`

- `Tween m_highlightBreathLightTween`

- `Tween m_sliderTween`


## Methods

- `Void _SetPos(Vector2, Vector2)`

- `Void Init(Vector2, Vector2)`

- `Void Render(CrisisV2MapBagModel, CrisisV2MapModel, Boolean, Boolean)`

- `Void _PlayFocusAnimIfNecessary(Boolean, Int32)`

- `Void _Render(CrisisV2MapBagModel, CrisisV2MapBagStatus, CrisisV2Progress)`

- `Void _RegisterTutorialGoIfNeed(String, String, String)`

- `Void _EnsureHighLightSwitchTween()`

- `Void _PlayBreathLightTween(Boolean)`

- `Void EventOnBagClick()`

- `Void EventOnOpenBagDetail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapBagView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _bagProgressBgToggle; // 0x18
	private TwoStateToggle _dimensionBgToggle; // 0x20
	private TwoStateToggle _nodeScoreBgToggle; // 0x28
	private TwoStateToggle _bagScoreBgToggle; // 0x30
	private GameObject _bagScoreGo; // 0x38
	private Text _textNodeScoreCurrent; // 0x40
	private Text _textNodeScoreTotal; // 0x48
	private Text _textBagScore; // 0x50
	private Color _colorUnselectScore; // 0x58
	private Color _colorSelectCurrentScore; // 0x68
	private Color _colorSelectTotalScore; // 0x78
	private Color _colorSelectBagScore; // 0x88
	private Color _colorFullBagScore; // 0x98
	private Text _textDesc; // 0xa8
	private Color _colorUnselectDesc; // 0xb0
	private Color _colorSelectDesc; // 0xc0
	private GameObject _completedIconGo; // 0xd0
	private Slider _sliderProgerss; // 0xd8
	private Single _sliderTweenDuration; // 0xe0
	private CanvasGroup _alphaHandler; // 0xe8
	private Single _unreachAlpha; // 0xf0
	private GameObject _unreachMaskGo; // 0xf8
	private UIAtlasImage _imgDimension; // 0x100
	private UIAtlasObject _dimensionAtlas; // 0x108
	private UIAnimationLocation _animSwitch; // 0x110
	private UIAnimationLocation _animFocus; // 0x120
	private GameObject _panelTitle; // 0x130
	private GameObject _panelBag; // 0x138
	private GameObject _panelDetail; // 0x140
	private CanvasGroup _highlightSwitchGroup; // 0x148
	private CanvasGroup _highlightBreathGroup; // 0x150
	private UIStateFinder m_stateFinder; // 0x158
	private CrisisV2MapBagModel m_bagModel; // 0x168
	private AnimationSwitchTween m_animSwitch; // 0x170
	private Tween m_focusTween; // 0x178
	private Int32 m_cacheInteractId; // 0x180
	private FadeSwitchTween m_highlightSwitchTween; // 0x188
	private Tween m_highlightBreathLightTween; // 0x190
	private Tween m_sliderTween; // 0x198
	private static DelegateBridge __Hotfix0__SetPos; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__PlayFocusAnimIfNecessary; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge __Hotfix0__RegisterTutorialGoIfNeed; // 0x28
	private static DelegateBridge __Hotfix0__EnsureHighLightSwitchTween; // 0x30
	private static DelegateBridge __Hotfix0__PlayBreathLightTween; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBagClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnOpenBagDetail; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2c02a14 VA: 0x759521aa14
	private Void _SetPos(Vector2 pos, Vector2 bagSize) { }
	// RVA: 0x2bfed7c VA: 0x7595216d7c
	public Void Init(Vector2 bagPos, Vector2 bagSize) { }
	// RVA: 0x2bff008 VA: 0x7595217008
	public Void Render(CrisisV2MapBagModel bagModel, CrisisV2MapModel mapModel, Boolean isVisisble, Boolean isHighLight) { }
	// RVA: 0x2c02d14 VA: 0x759521ad14
	private Void _PlayFocusAnimIfNecessary(Boolean isBagFocus, Int32 interactId) { }
	// RVA: 0x2c02e70 VA: 0x759521ae70
	private Void _Render(CrisisV2MapBagModel bagModel, CrisisV2MapBagStatus bagStatus, CrisisV2Progress nodeProgress) { }
	// RVA: 0x2c03368 VA: 0x759521b368
	private Void _RegisterTutorialGoIfNeed(String bagKey, String titleKey, String detailKey) { }
	// RVA: 0x2c034e0 VA: 0x759521b4e0
	private Void _EnsureHighLightSwitchTween() { }
	// RVA: 0x2c02ae8 VA: 0x759521aae8
	private Void _PlayBreathLightTween(Boolean isPlay) { }
	// RVA: 0x2c035c0 VA: 0x759521b5c0
	public Void EventOnBagClick() { }
	// RVA: 0x2c036cc VA: 0x759521b6cc
	public Void EventOnOpenBagDetail() { }
	// RVA: 0x2c037d8 VA: 0x759521b7d8
	public Void .ctor() { }
}
```
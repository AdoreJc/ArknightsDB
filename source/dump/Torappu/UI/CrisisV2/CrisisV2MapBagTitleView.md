# CrisisV2MapBagTitleView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `TwoStateToggle _bagProgressBgToggle`

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

- `UIAnimationLocation _animSwitch`

- `UIStateFinder m_stateFinder`

- `CrisisV2MapBagModel m_bagModel`

- `AnimationSwitchTween m_switchTween`

- `Tween m_sliderTween`


## Methods

- `Void _SetPos(Vector2, Vector2)`

- `Void Init(Vector2, Vector2)`

- `Void Render(CrisisV2MapBagModel, CrisisV2MapBagStatus, CrisisV2Progress, Boolean)`

- `Void EventOnBtnBagClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapBagTitleView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _bagProgressBgToggle; // 0x18
	private TwoStateToggle _nodeScoreBgToggle; // 0x20
	private TwoStateToggle _bagScoreBgToggle; // 0x28
	private GameObject _bagScoreGo; // 0x30
	private Text _textNodeScoreCurrent; // 0x38
	private Text _textNodeScoreTotal; // 0x40
	private Text _textBagScore; // 0x48
	private Color _colorUnselectScore; // 0x50
	private Color _colorSelectCurrentScore; // 0x60
	private Color _colorSelectTotalScore; // 0x70
	private Color _colorSelectBagScore; // 0x80
	private Color _colorFullBagScore; // 0x90
	private Text _textDesc; // 0xa0
	private Color _colorUnselectDesc; // 0xa8
	private Color _colorSelectDesc; // 0xb8
	private GameObject _completedIconGo; // 0xc8
	private Slider _sliderProgerss; // 0xd0
	private Single _sliderTweenDuration; // 0xd8
	private CanvasGroup _alphaHandler; // 0xe0
	private Single _unreachAlpha; // 0xe8
	private UIAnimationLocation _animSwitch; // 0xf0
	private UIStateFinder m_stateFinder; // 0x100
	private CrisisV2MapBagModel m_bagModel; // 0x110
	private AnimationSwitchTween m_switchTween; // 0x118
	private Tween m_sliderTween; // 0x120
	private static DelegateBridge __Hotfix0__SetPos; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBtnBagClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2c0220c VA: 0x759521a20c
	private Void _SetPos(Vector2 pos, Vector2 size) { }
	// RVA: 0x2c022e0 VA: 0x759521a2e0
	public Void Init(Vector2 bagPos, Vector2 bagSize) { }
	// RVA: 0x2c02408 VA: 0x759521a408
	public Void Render(CrisisV2MapBagModel bagModel, CrisisV2MapBagStatus bagStatus, CrisisV2Progress nodeProgress, Boolean isVisible) { }
	// RVA: 0x2c02888 VA: 0x759521a888
	public Void EventOnBtnBagClick() { }
	// RVA: 0x2c02994 VA: 0x759521a994
	public Void .ctor() { }
}
```
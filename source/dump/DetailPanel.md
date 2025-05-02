# DetailPanel

**Namespace:** ` `


## Fields

- `RectTransform _pnlRoot`

- `Image _imgMealName`

- `Text _textApNum`

- `Image _imgItemUp`

- `Text _textEffect`

- `Text _textDesc`

- `Text _textCost`

- `GameObject _pnlEat`

- `GameObject _pnlEaten`

- `Image _imgMeal`

- `UIAnimationLocation _animEat`

- `UIAnimationLocation _animLoop`

- `RectTransform _transCircle`

- `Single _circleTweenDuration`

- `Color _colorCostNormal`

- `Color _colorCostLack`

- `UIStateFinder m_finder`

- `Boolean m_inited`

- `UISwitchTween m_eatSwitchTween`

- `Tween m_loopTween`

- `Tween m_circleTween`

- `Boolean m_loopTweenPlaying`

- `Boolean m_cachedEaten`


## Methods

- `Void _InitIfNot()`

- `Void _PlayLoopTween(Boolean)`

- `Void Render(Act24sideEatViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DetailPanel : IHotfixable
{
	private const String FORMAT_PLUS_AP; // 0x0
	private RectTransform _pnlRoot; // 0x10
	private Image _imgMealName; // 0x18
	private Text _textApNum; // 0x20
	private Image _imgItemUp; // 0x28
	private Text _textEffect; // 0x30
	private Text _textDesc; // 0x38
	private Text _textCost; // 0x40
	private GameObject _pnlEat; // 0x48
	private GameObject _pnlEaten; // 0x50
	private Image _imgMeal; // 0x58
	private UIAnimationLocation _animEat; // 0x60
	private UIAnimationLocation _animLoop; // 0x70
	private RectTransform _transCircle; // 0x80
	private Single _circleTweenDuration; // 0x88
	private Color _colorCostNormal; // 0x8c
	private Color _colorCostLack; // 0x9c
	private UIStateFinder m_finder; // 0xb0
	private Boolean m_inited; // 0xc0
	private UISwitchTween m_eatSwitchTween; // 0xc8
	private Tween m_loopTween; // 0xd0
	private Tween m_circleTween; // 0xd8
	private Boolean m_loopTweenPlaying; // 0xe0
	private Boolean m_cachedEaten; // 0xe1
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__PlayLoopTween; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x329ae54 VA: 0x75958b2e54
	private Void _InitIfNot() { }
	// RVA: 0x329b0e4 VA: 0x75958b30e4
	private Void _PlayLoopTween(Boolean show) { }
	// RVA: 0x329a918 VA: 0x75958b2918
	public Void Render(Act24sideEatViewModel viewModel, Boolean isInit) { }
	// RVA: 0x329b23c VA: 0x75958b323c
	public Void .ctor() { }
}
```
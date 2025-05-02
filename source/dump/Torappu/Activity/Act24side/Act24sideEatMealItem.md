# Act24sideEatMealItem

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Image _imgMeal`

- `Image _imgItem`

- `Text _textMealName`

- `UIAnimationLocation _animSelected`

- `GameObject _pnlEaten`

- `Button _btnItem`

- `RectTransform _posHandler`

- `Single _posSelected`

- `Single _posTweenDuration`

- `Boolean m_inited`

- `UISwitchTween m_selectedSwitchTween`

- `TranslateSwitchTween m_selectedTranslateTween`

- `UIStateFinder m_finder`

- `String m_cachedMealId`


## Methods

- `Void _InitIfNot()`

- `Void _ChooseImgLike()`

- `Void Render(String, Act24sideMealViewModel, Act24sideEatViewModel, Boolean)`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideEatMealItem : MonoBehaviour, IHotfixable
{
	private Image _imgMeal; // 0x18
	private Image _imgItem; // 0x20
	private Text _textMealName; // 0x28
	private UIAnimationLocation _animSelected; // 0x30
	private GameObject[] _itemLikes; // 0x40
	private GameObject _pnlEaten; // 0x48
	private Button _btnItem; // 0x50
	private RectTransform _posHandler; // 0x58
	private Single _posSelected; // 0x60
	private Single _posTweenDuration; // 0x64
	private Boolean m_inited; // 0x68
	private UISwitchTween m_selectedSwitchTween; // 0x70
	private TranslateSwitchTween m_selectedTranslateTween; // 0x78
	private UIStateFinder m_finder; // 0x80
	private String m_cachedMealId; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__ChooseImgLike; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3298104 VA: 0x75958b0104
	private Void _InitIfNot() { }
	// RVA: 0x3298390 VA: 0x75958b0390
	private Void _ChooseImgLike() { }
	// RVA: 0x32984a0 VA: 0x75958b04a0
	public Void Render(String mealId, Act24sideMealViewModel mealViewModel, Act24sideEatViewModel eatViewModel, Boolean isInit) { }
	// RVA: 0x32986dc VA: 0x75958b06dc
	public Void OnClicked() { }
	// RVA: 0x32987f4 VA: 0x75958b07f4
	public Void .ctor() { }
}
```
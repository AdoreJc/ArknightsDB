# GroceryOrderResultShopItemView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GameObject _objEmpty`

- `GameObject _objNotEmpty`

- `Image _imgShopIcon`

- `Text _txtStrategy`

- `Text _txtCount`

- `Text _txtPrice`

- `Slider _slider`

- `UIAtlasImage _sliderImg`

- `UIAnimationLocation _animSelfShopIconLoop`

- `GameObject _objSplit`

- `CanvasGroup _canvasTxtCount`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `Tween m_loopSelfShopIconTween`

- `GroceryOrderCountTextTweener m_countTextTweener`

- `GroceryOrderResultSliderCountTweener m_sliderCountTweener`

- `GroceryOrderResultShopItemViewModel m_cachedModel`

- `FadeSwitchTween m_tweenTxtCount`


## Methods

- `Void Render(GroceryOrderResultShopItemViewModel, Boolean)`

- `Boolean NeedPlayTween()`

- `Void PlaySliderCountChangeTween()`

- `Void _InitIfNot()`

- `Void _PlaySelfIconLoopTween(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderResultShopItemView : MonoBehaviour, IHotfixable
{
	private GameObject _objEmpty; // 0x18
	private GameObject _objNotEmpty; // 0x20
	private Image _imgShopIcon; // 0x28
	private Text _txtStrategy; // 0x30
	private Text _txtCount; // 0x38
	private Text _txtPrice; // 0x40
	private Slider _slider; // 0x48
	private UIAtlasImage _sliderImg; // 0x50
	private UIAnimationLocation _animSelfShopIconLoop; // 0x58
	private GameObject _objSplit; // 0x68
	private CanvasGroup _canvasTxtCount; // 0x70
	private Boolean m_hasInited; // 0x78
	private UIStateFinder m_stateFinder; // 0x80
	private Tween m_loopSelfShopIconTween; // 0x90
	private const Single COUNT_CHANGE_DUR; // 0x0
	private GroceryOrderCountTextTweener m_countTextTweener; // 0x98
	private GroceryOrderResultSliderCountTweener m_sliderCountTweener; // 0xa0
	private GroceryOrderResultShopItemViewModel m_cachedModel; // 0xa8
	private FadeSwitchTween m_tweenTxtCount; // 0xb0
	private static readonly Color COLOR_OTHER_SLIDER; // 0x0
	private static readonly Color COLOR_MY_SLIDER; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_NeedPlayTween; // 0x28
	private static DelegateBridge __Hotfix0_PlaySliderCountChangeTween; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__PlaySelfIconLoopTween; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2894338 VA: 0x7594eac338
	public Void Render(GroceryOrderResultShopItemViewModel itemViewModel, Boolean isLastOne) { }
	// RVA: 0x289491c VA: 0x7594eac91c
	public Boolean NeedPlayTween() { }
	// RVA: 0x28949a4 VA: 0x7594eac9a4
	public Void PlaySliderCountChangeTween() { }
	// RVA: 0x2894bf0 VA: 0x7594eacbf0
	private Void _InitIfNot() { }
	// RVA: 0x2894fec VA: 0x7594eacfec
	private Void _PlaySelfIconLoopTween(Boolean show) { }
	// RVA: 0x28955bc VA: 0x7594ead5bc
	public Void .ctor() { }
	// RVA: 0x289563c VA: 0x7594ead63c
	private static Void .cctor() { }
}
```
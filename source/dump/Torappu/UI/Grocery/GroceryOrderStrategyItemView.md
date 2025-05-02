# GroceryOrderStrategyItemView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `CanvasGroup _canvasUnSelect`

- `Text _txtCount`

- `Text _txtStrategy`

- `CanvasGroup _canvasSelect`

- `Text _txtCountSelect`

- `Text _txtStrategySelect`

- `Image _imgMyShopIcon`

- `UIAnimationLocation _animSelectLoop`

- `Boolean m_hasInit`

- `String m_cachedGoodId`

- `Int32 m_cachedStrategyIndex`

- `UIStateFinder m_stateFinder`

- `Boolean m_loopTweenPlaying`

- `Tween m_loopSelectTween`

- `FadeSwitchTween m_unselectTween`

- `FadeSwitchTween m_selectTween`


## Methods

- `Void Render(GroceryOrderSelfShopStrategyItemViewModel)`

- `Void _InitIfNot()`

- `Void _PlaySelectLoopTween(Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderStrategyItemView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasUnSelect; // 0x18
	private Text _txtCount; // 0x20
	private Text _txtStrategy; // 0x28
	private CanvasGroup _canvasSelect; // 0x30
	private Text _txtCountSelect; // 0x38
	private Text _txtStrategySelect; // 0x40
	private Image _imgMyShopIcon; // 0x48
	private UIAnimationLocation _animSelectLoop; // 0x50
	private Boolean m_hasInit; // 0x60
	private String m_cachedGoodId; // 0x68
	private Int32 m_cachedStrategyIndex; // 0x70
	private UIStateFinder m_stateFinder; // 0x78
	private Boolean m_loopTweenPlaying; // 0x88
	private Tween m_loopSelectTween; // 0x90
	private FadeSwitchTween m_unselectTween; // 0x98
	private FadeSwitchTween m_selectTween; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__PlaySelectLoopTween; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2888cc8 VA: 0x7594ea0cc8
	public Void Render(GroceryOrderSelfShopStrategyItemViewModel itemViewModel) { }
	// RVA: 0x288d2a4 VA: 0x7594ea52a4
	private Void _InitIfNot() { }
	// RVA: 0x288d644 VA: 0x7594ea5644
	private Void _PlaySelectLoopTween(Boolean show) { }
	// RVA: 0x288d79c VA: 0x7594ea579c
	public Void OnClick() { }
	// RVA: 0x288d89c VA: 0x7594ea589c
	public Void .ctor() { }
}
```
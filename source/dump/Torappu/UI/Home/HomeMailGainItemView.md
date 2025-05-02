# HomeMailGainItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `SimpleLayoutContent _itemGridLayout`

- `Single _itemScaleFactor`

- `Image _blurBkg`

- `CanvasGroup _alphaHandler`

- `Shader _blurShader`

- `Boolean m_isShowing`

- `Sprite m_blurSprite`

- `Tween m_cachedTween`

- `ItemAdapter m_itemAdapter`

- `RectTransform m_rectTransform`

- `Boolean m_isInited`


## Properties

- `RectTransform rectTransform`


## Methods

- `RectTransform get_rectTransform()`

- `Void _InitIfNot()`

- `Void EventOnConfirmClicked()`

- `Void EventOnBlankClicked()`

- `Void Show()`

- `Void Hide()`

- `Void Render(List`1)`

- `Void OnEnable()`

- `Void OnDestroy()`

- `Void _UpdateAutoLayouts()`

- `Void _ClearTween()`

- `Void _ClearSprites()`

- `IEnumerator _ReupdateLayoutCoroutine()`

- `Void <Hide>b__21_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailGainItemView : MonoBehaviour
{
	private const Single TWEEN_DURATION; // 0x0
	private SimpleLayoutContent _itemGridLayout; // 0x18
	private Single _itemScaleFactor; // 0x20
	private Image _blurBkg; // 0x28
	private CanvasGroup _alphaHandler; // 0x30
	private RectTransform[] _autoLayouts; // 0x38
	private Shader _blurShader; // 0x40
	private Boolean m_isShowing; // 0x48
	private Sprite m_blurSprite; // 0x50
	private Tween m_cachedTween; // 0x58
	private ItemAdapter m_itemAdapter; // 0x60
	private List`1 m_itemModels; // 0x68
	private RectTransform m_rectTransform; // 0x70
	private Boolean m_isInited; // 0x78

	public RectTransform rectTransform { get; }

	// RVA: 0x2842d6c VA: 0x7594e5ad6c
	public RectTransform get_rectTransform() { }
	// RVA: 0x2842e14 VA: 0x7594e5ae14
	private Void _InitIfNot() { }
	// RVA: 0x2842f40 VA: 0x7594e5af40
	public Void EventOnConfirmClicked() { }
	// RVA: 0x2843058 VA: 0x7594e5b058
	public Void EventOnBlankClicked() { }
	// RVA: 0x284305c VA: 0x7594e5b05c
	public Void Show() { }
	// RVA: 0x2842f44 VA: 0x7594e5af44
	public Void Hide() { }
	// RVA: 0x2843308 VA: 0x7594e5b308
	public Void Render(List`1 itemModels) { }
	// RVA: 0x2843418 VA: 0x7594e5b418
	private Void OnEnable() { }
	// RVA: 0x28434dc VA: 0x7594e5b4dc
	private Void OnDestroy() { }
	// RVA: 0x2843368 VA: 0x7594e5b368
	private Void _UpdateAutoLayouts() { }
	// RVA: 0x28431d8 VA: 0x7594e5b1d8
	private Void _ClearTween() { }
	// RVA: 0x2843220 VA: 0x7594e5b220
	private Void _ClearSprites() { }
	// RVA: 0x2843468 VA: 0x7594e5b468
	private IEnumerator _ReupdateLayoutCoroutine() { }
	// RVA: 0x2843508 VA: 0x7594e5b508
	public Void .ctor() { }
	// RVA: 0x2843518 VA: 0x7594e5b518
	private Void <Hide>b__21_0() { }
}
```
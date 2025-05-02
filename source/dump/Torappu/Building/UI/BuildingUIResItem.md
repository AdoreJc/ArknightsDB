# BuildingUIResItem

**Namespace:** `Torappu.Building.UI`


## Fields

- `Text _textCount`

- `Text _textLimit`

- `Image _icon`

- `CanvasGroup _iconRipple`

- `Boolean _autoHide`

- `RectTransform _autoLayout`

- `GameObject _iconUp`

- `EffectOptions m_effectOptionsCache`

- `Tween m_iconRippleTween`

- `CanvasGroup m_alphaHandler`

- `RectTransform m_rippleTransCache`


## Properties

- `CanvasGroup alphaHandler`

- `RectTransform rippleIconTrans`


## Methods

- `CanvasGroup get_alphaHandler()`

- `RectTransform get_rippleIconTrans()`

- `Void Start()`

- `Void Render(Int32, Int32)`

- `Void StartRippleEffect()`

- `Void RenderWithEffect(EffectOptions)`

- `Void _TweenRippleSetter(Single)`

- `Void _TweenCountSetter(Single)`

- `Void _KillPreviousTweens()`

- `Void _ShowIconUp()`

- `Void _HideIconUp()`

- `Void <StartRippleEffect>b__24_1()`

- `Void <RenderWithEffect>b__25_4()`

- `Void <RenderWithEffect>b__25_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingUIResItem : MonoBehaviour
{
	private const Single ANIM_TEXT_DELAY; // 0x0
	private const Single ANIM_TEXT_DURATION; // 0x0
	private const Single ANIM_RIPPLE_DURATION; // 0x0
	private const Single ANIM_FADE_DURATION; // 0x0
	private const Single AUTO_SHOW_TIME; // 0x0
	private Text _textCount; // 0x18
	private Text _textLimit; // 0x20
	private Image _icon; // 0x28
	private CanvasGroup _iconRipple; // 0x30
	private Boolean _autoHide; // 0x38
	private RectTransform _autoLayout; // 0x40
	private GameObject _iconUp; // 0x48
	private EffectOptions m_effectOptionsCache; // 0x50
	private List`1 m_activeTweens; // 0x60
	private Tween m_iconRippleTween; // 0x68
	private CanvasGroup m_alphaHandler; // 0x70
	private RectTransform m_rippleTransCache; // 0x78

	protected CanvasGroup alphaHandler { get; }
	public RectTransform rippleIconTrans { get; }

	// RVA: 0x3d3e1fc VA: 0x75963561fc
	protected CanvasGroup get_alphaHandler() { }
	// RVA: 0x3d3e348 VA: 0x7596356348
	public RectTransform get_rippleIconTrans() { }
	// RVA: 0x3d3e3dc VA: 0x75963563dc
	private Void Start() { }
	// RVA: 0x3d3e538 VA: 0x7596356538
	public Void Render(Int32 count, Int32 maxCount) { }
	// RVA: 0x3d3e6b0 VA: 0x75963566b0
	public Void StartRippleEffect() { }
	// RVA: 0x3d3e95c VA: 0x759635695c
	public Void RenderWithEffect(EffectOptions options) { }
	// RVA: 0x3d3f378 VA: 0x7596357378
	private Void _TweenRippleSetter(Single val) { }
	// RVA: 0x3d3f3d0 VA: 0x75963573d0
	private Void _TweenCountSetter(Single val) { }
	// RVA: 0x3d3f220 VA: 0x7596357220
	private Void _KillPreviousTweens() { }
	// RVA: 0x3d3f2e8 VA: 0x75963572e8
	private Void _ShowIconUp() { }
	// RVA: 0x3d3e4a8 VA: 0x75963564a8
	private Void _HideIconUp() { }
	// RVA: 0x3d3f448 VA: 0x7596357448
	public Void .ctor() { }
	// RVA: 0x3d3f4d0 VA: 0x75963574d0
	private Void <StartRippleEffect>b__24_1() { }
	// RVA: 0x3d3f50c VA: 0x759635750c
	private Void <RenderWithEffect>b__25_4() { }
	// RVA: 0x3d3f528 VA: 0x7596357528
	private Void <RenderWithEffect>b__25_1() { }
}
```
# UIFollowEpSlider

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _epAnimImage`

- `Image _epBreakAnimImage`

- `CanvasGroup _epBreakAlpha`

- `Image _sliderFillBackImage`

- `Image _epIconImage`

- `Image _epColorImage`

- `Sequence m_tweenSequence`

- `Sequence m_breakTweenSequence`

- `Boolean m_inAutoRecovery`

- `ElementType m_elementType`


## Methods

- `Void SetElementType(ElementType)`

- `Void SetEpHitAnimation(ElementType)`

- `Void SetEpBreakAnimation(ElementType)`

- `Void SetSliderInRecovery(Boolean, ElementType)`

- `Void <SetEpHitAnimation>b__18_0()`

- `Void <SetEpBreakAnimation>b__19_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIFollowEpSlider : UIFollowSlider
{
	private Image _epAnimImage; // 0x48
	private Image _epBreakAnimImage; // 0x50
	private CanvasGroup _epBreakAlpha; // 0x58
	private Image _sliderFillBackImage; // 0x60
	private Image _epIconImage; // 0x68
	private Image _epColorImage; // 0x70
	private ElementUIData[] _elementDatas; // 0x78
	private Sequence m_tweenSequence; // 0x80
	private Sequence m_breakTweenSequence; // 0x88
	private const Single EP_ANIM_DURATION; // 0x0
	private const Single EP_ANIM_TO_SCALE; // 0x0
	private const Single EP_BREAK_ANIM_DURATION; // 0x0
	private const Single EP_BREAK_ANIM_FROM_SCALE; // 0x0
	private const Single EP_BREAK_ANIM_TO_SCALE; // 0x0
	private Boolean m_inAutoRecovery; // 0x90
	private ElementType m_elementType; // 0x94


	// RVA: 0x207de08 VA: 0x7594695e08
	public Void SetElementType(ElementType type) { }
	// RVA: 0x207df4c VA: 0x7594695f4c
	public Void SetEpHitAnimation(ElementType type) { }
	// RVA: 0x207e22c VA: 0x759469622c
	public Void SetEpBreakAnimation(ElementType type) { }
	// RVA: 0x207e5f8 VA: 0x75946965f8
	public Void SetSliderInRecovery(Boolean isInRecovery, ElementType recoveryType) { }
	// RVA: 0x207e6d8 VA: 0x75946966d8
	public Void .ctor() { }
	// RVA: 0x207e6e8 VA: 0x75946966e8
	private Void <SetEpHitAnimation>b__18_0() { }
	// RVA: 0x207e77c VA: 0x759469677c
	private Void <SetEpBreakAnimation>b__19_0() { }
}
```
# FifthAnnivExploreSideValueView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `RectTransform _rectTransformCurrent`

- `RectTransform _rectTransformDelta`

- `CanvasGroup _canvasGroupTextDelta`

- `Text _txtCurrent`

- `Text _txtDelta`

- `Single _tweenDuration`

- `Single _tweenDelay`

- `Single _txtFadeDuration`

- `Tween m_deltaTween`


## Methods

- `String _GetDeltaText(Boolean, Int32)`

- `Void _ShowDeltaAnim(Single, Single, Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreSideValueView : FifthAnnivExploreValueAbstractView
{
	private const String NEGATIVE_DELTA_NUM_FORMAT; // 0x0
	private const String POSITIVE_DELTA_NUM_FORMAT; // 0x0
	private RectTransform _rectTransformCurrent; // 0x18
	private RectTransform _rectTransformDelta; // 0x20
	private CanvasGroup _canvasGroupTextDelta; // 0x28
	private Text _txtCurrent; // 0x30
	private Text _txtDelta; // 0x38
	private Single _tweenDuration; // 0x40
	private Single _tweenDelay; // 0x44
	private Single _txtFadeDuration; // 0x48
	private Tween m_deltaTween; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GetDeltaText; // 0x8
	private static DelegateBridge __Hotfix0__ShowDeltaAnim; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x292f56c VA: 0x7594f4756c
	public override Void Render(FifthAnnivExploreValueViewConfig config, FifthAnnivExploreValueViewModel viewModel, Boolean showNum) { }
	// RVA: 0x292f7a4 VA: 0x7594f477a4
	private String _GetDeltaText(Boolean isPositiveDelta, Int32 deltaValue) { }
	// RVA: 0x292f898 VA: 0x7594f47898
	private Void _ShowDeltaAnim(Single oriScale, Single finScale, Int32 currentValue, Int32 deltaValue) { }
	// RVA: 0x292fce8 VA: 0x7594f47ce8
	public Void .ctor() { }
}
```
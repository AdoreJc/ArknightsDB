# Act13sidePrestigeProgressView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Text _textNextStage`

- `Image _imgSlider`

- `Single _sliderAnimDuration`

- `Ease _animEase`


## Properties

- `Single sliderVal`


## Methods

- `Void Render(String, String, Int32)`

- `Single get_sliderVal()`

- `Void set_sliderVal(Single)`

- `Tweener PlaySliderAnim(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sidePrestigeProgressView : MonoBehaviour, IHotfixable
{
	private Text _textNextStage; // 0x18
	private Image _imgSlider; // 0x20
	private Single _sliderAnimDuration; // 0x28
	private Ease _animEase; // 0x2c
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_get_sliderVal; // 0x8
	private static DelegateBridge __Hotfix0_set_sliderVal; // 0x10
	private static DelegateBridge __Hotfix0_PlaySliderAnim; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Single sliderVal { get; set; }

	// RVA: 0x34330a0 VA: 0x7595a4b0a0
	public Void Render(String actId, String orgId, Int32 prestigeCount) { }
	// RVA: 0x3443208 VA: 0x7595a5b208
	public Single get_sliderVal() { }
	// RVA: 0x344327c VA: 0x7595a5b27c
	public Void set_sliderVal(Single value) { }
	// RVA: 0x3443308 VA: 0x7595a5b308
	public Tweener PlaySliderAnim(Single targetVal) { }
	// RVA: 0x34434c4 VA: 0x7595a5b4c4
	public Void .ctor() { }
}
```
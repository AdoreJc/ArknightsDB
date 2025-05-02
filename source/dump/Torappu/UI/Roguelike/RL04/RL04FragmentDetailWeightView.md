# RL04FragmentDetailWeightView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `LayoutElement _elementLimitWeight`

- `Text _textLimitWeight`

- `LayoutElement _elementOverWeight`

- `Text _textOverWeight`

- `Slider _sliderWeight`

- `Slider _sliderWeightWithoutFragment`

- `UIAnimationLocation _loopAnim`


## Methods

- `Void Render(RL04FragmentDetailWeightViewModel)`

- `Void _TryPlayLoopAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentDetailWeightView : MonoBehaviour, IHotfixable
{
	private LayoutElement _elementLimitWeight; // 0x18
	private Text _textLimitWeight; // 0x20
	private LayoutElement _elementOverWeight; // 0x28
	private Text _textOverWeight; // 0x30
	private Slider _sliderWeight; // 0x38
	private Slider _sliderWeightWithoutFragment; // 0x40
	private Text[] _textCurrWeight; // 0x48
	private GameObject[] _panelNormal; // 0x50
	private GameObject[] _panelLimitWeight; // 0x58
	private GameObject[] _panelOverWeight; // 0x60
	private GameObject[] _panelNotOverWeight; // 0x68
	private UIAnimationLocation _loopAnim; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__TryPlayLoopAnim; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b21c10 VA: 0x7595139c10
	public Void Render(RL04FragmentDetailWeightViewModel model) { }
	// RVA: 0x2b22a2c VA: 0x759513aa2c
	private Void _TryPlayLoopAnim() { }
	// RVA: 0x2b22ad8 VA: 0x759513aad8
	public Void .ctor() { }
}
```
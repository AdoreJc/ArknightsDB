# CrisisV2DiagramDimensionItem

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Slider _highestTotal`

- `UIAtlasImage _totalColor`

- `GameObject _totalGo`

- `Slider _highestSingle`

- `GameObject _singleGo`

- `Slider _current`

- `UIAtlasImage _currentColor`

- `GameObject _currentGo`

- `RectTransform _currentScoreBorder`

- `RectTransform _highestTotalScoreBorder`

- `Tween m_highestTotalTween`

- `Tween m_highestSingleTween`

- `Tween m_currentTween`


## Methods

- `Void SetStyleConfig(StyleConfig)`

- `Void RenderScore(DimensionInput)`

- `Void _RenderScoreSlider(Slider, Single, Boolean, ref, TweenInput)`

- `Void _CorrectBorderWidth()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2DiagramDimensionItem : MonoBehaviour, IHotfixable
{
	private const Single BORDER_WIDTH; // 0x0
	private Slider _highestTotal; // 0x18
	private UIAtlasImage _totalColor; // 0x20
	private GameObject _totalGo; // 0x28
	private Slider _highestSingle; // 0x30
	private GameObject _singleGo; // 0x38
	private Slider _current; // 0x40
	private UIAtlasImage _currentColor; // 0x48
	private GameObject _currentGo; // 0x50
	private RectTransform _currentScoreBorder; // 0x58
	private RectTransform _highestTotalScoreBorder; // 0x60
	private Tween m_highestTotalTween; // 0x68
	private Tween m_highestSingleTween; // 0x70
	private Tween m_currentTween; // 0x78
	private static DelegateBridge __Hotfix0_SetStyleConfig; // 0x0
	private static DelegateBridge __Hotfix0_RenderScore; // 0x8
	private static DelegateBridge __Hotfix0__RenderScoreSlider; // 0x10
	private static DelegateBridge __Hotfix0__CorrectBorderWidth; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2bcd740 VA: 0x75951e5740
	public Void SetStyleConfig(StyleConfig config) { }
	// RVA: 0x2bcd948 VA: 0x75951e5948
	public Void RenderScore(DimensionInput input) { }
	// RVA: 0x2bcda48 VA: 0x75951e5a48
	private Void _RenderScoreSlider(Slider slider, Single endVal, Boolean needTween, ref Tween tween, TweenInput tweenInput) { }
	// RVA: 0x2bcd8a0 VA: 0x75951e58a0
	private Void _CorrectBorderWidth() { }
	// RVA: 0x2bcdd0c VA: 0x75951e5d0c
	public Void .ctor() { }
}
```
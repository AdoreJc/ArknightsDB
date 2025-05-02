# MagneticDotSliderView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `HorizontalLayoutGroup _dotLayoutGroup`

- `SimpleLayoutContent _dotItemList`

- `Single _dotWidth`

- `Text _txtCurValue`

- `Boolean m_hasInited`

- `Adapter m_dotItemListAdapter`

- `MagneticDotSliderViewModel m_model`

- `GrocerySellSliderController m_sliderController`

- `RectTransform m_layoutTransform`

- `Single m_cachedReachDotBias`


## Methods

- `Void InitView(GrocerySellSliderController)`

- `Single GetReachDotBias()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class MagneticDotSliderView : DataBinder`1
{
	private HorizontalLayoutGroup _dotLayoutGroup; // 0x20
	private SimpleLayoutContent _dotItemList; // 0x28
	private Single _dotWidth; // 0x30
	private Text _txtCurValue; // 0x38
	private Boolean m_hasInited; // 0x40
	private Adapter m_dotItemListAdapter; // 0x48
	private MagneticDotSliderViewModel m_model; // 0x50
	private GrocerySellSliderController m_sliderController; // 0x58
	private RectTransform m_layoutTransform; // 0x60
	private Single m_cachedReachDotBias; // 0x68
	private static DelegateBridge __Hotfix0_InitView; // 0x0
	private static DelegateBridge __Hotfix0_GetReachDotBias; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28a7238 VA: 0x7594ebf238
	public Void InitView(GrocerySellSliderController controller) { }
	// RVA: 0x28a72bc VA: 0x7594ebf2bc
	public Single GetReachDotBias() { }
	// RVA: 0x28a7324 VA: 0x7594ebf324
	public override Void OnValueChanged(MagneticDotSliderViewModelProperty property) { }
	// RVA: 0x28a7518 VA: 0x7594ebf518
	private Void _InitIfNot() { }
	// RVA: 0x28a779c VA: 0x7594ebf79c
	public Void .ctor() { }
}
```
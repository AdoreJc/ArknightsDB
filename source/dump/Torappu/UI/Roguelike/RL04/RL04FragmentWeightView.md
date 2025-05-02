# RL04FragmentWeightView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `LayoutElement _elementLimitWeight`

- `Text _textLimitWeight`

- `LayoutElement _elementOverWeight`

- `Text _textOverWeight`

- `Slider _sliderWeight`

- `Text _textWeightDesc`

- `GameObject _betterTips`

- `SimpleLayoutContent _content`

- `Adapter m_adapter`

- `Boolean m_hasInited`

- `RoguelikeFragmentDialogMode m_cachedMode`


## Methods

- `Void set_onCharCardClicked(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentWeightView : DataBinder`1, IHotfixable
{
	private LayoutElement _elementLimitWeight; // 0x20
	private Text _textLimitWeight; // 0x28
	private LayoutElement _elementOverWeight; // 0x30
	private Text _textOverWeight; // 0x38
	private Slider _sliderWeight; // 0x40
	private Text[] _textCurrWeight; // 0x48
	private GameObject[] _panelNormal; // 0x50
	private GameObject[] _panelLimitWeight; // 0x58
	private GameObject[] _panelOverWeight; // 0x60
	private GameObject[] _panelLimitOrOverWeight; // 0x68
	private Text _textWeightDesc; // 0x70
	private GameObject _betterTips; // 0x78
	private SimpleLayoutContent _content; // 0x80
	private Action`1 <onCharCardClicked>k__BackingField; // 0x88
	private Adapter m_adapter; // 0x90
	private Boolean m_hasInited; // 0x98
	private List`1 m_cachedCharCardList; // 0xa0
	private RoguelikeFragmentDialogMode m_cachedMode; // 0xa8
	private static DelegateBridge __Hotfix0_get_onCharCardClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onCharCardClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onCharCardClicked { get; set; }

	// RVA: 0x2b28de0 VA: 0x7595140de0
	private Action`1 get_onCharCardClicked() { }
	// RVA: 0x2b24838 VA: 0x759513c838
	public Void set_onCharCardClicked(Action`1 value) { }
	// RVA: 0x2b28e48 VA: 0x7595140e48
	public override Void OnValueChanged(RL04FragmentProperty property) { }
	// RVA: 0x2b29240 VA: 0x7595141240
	private Void _InitIfNot() { }
	// RVA: 0x2b293a4 VA: 0x75951413a4
	public Void .ctor() { }
}
```
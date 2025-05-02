# VoucherSkinHomeView

**Namespace:** `Torappu.UI.VoucherSkin`


## Fields

- `RectTransform _rulePartTransform`

- `GameObject _objSkinListPart`

- `SimpleLayoutContent _content`

- `GameObject _objNothingTipsPart`

- `GameObject _objTimeFinishPart`

- `Text _textTimeFinish`

- `RectTransform _transRuleContainer`

- `Text _textRule`

- `Animator _spreadAnim`

- `Boolean m_inited`

- `Boolean m_detailRuleTextInited`

- `GoodAdapter m_adapter`

- `Action <onBackPressClicked>k__BackingField`


## Properties

- `Action onBackPressClicked`


## Methods

- `Void set_onGoodClicked(Action`1)`

- `Action get_onBackPressClicked()`

- `Void set_onBackPressClicked(Action)`

- `Void ShowRuleDetailView(Boolean)`

- `Void Start()`

- `Void OnEnable()`

- `Void _InitIfNot()`

- `Void _ResetRuleView()`

- `Void _ShowNothingTips()`

- `Void <_InitIfNot>b__26_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoucherSkin
public class VoucherSkinHomeView : DataBinder`1
{
	private const String ANIMATOR_PARAM; // 0x0
	private RectTransform _rulePartTransform; // 0x20
	private GameObject _objSkinListPart; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private GameObject _objNothingTipsPart; // 0x38
	private GameObject _objTimeFinishPart; // 0x40
	private Text _textTimeFinish; // 0x48
	private RectTransform _transRuleContainer; // 0x50
	private Text _textRule; // 0x58
	private Animator _spreadAnim; // 0x60
	private Boolean m_inited; // 0x68
	private Boolean m_detailRuleTextInited; // 0x69
	private GoodAdapter m_adapter; // 0x70
	private Action`1 <onGoodClicked>k__BackingField; // 0x78
	private Action <onBackPressClicked>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_onGoodClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onGoodClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onBackPressClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onBackPressClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_ShowRuleDetailView; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_OnEnable; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__ResetRuleView; // 0x48
	private static DelegateBridge __Hotfix0__ShowNothingTips; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Action`1 onGoodClicked { get; set; }
	public Action onBackPressClicked { get; set; }

	// RVA: 0x22922f8 VA: 0x75948aa2f8
	public Action`1 get_onGoodClicked() { }
	// RVA: 0x22919e4 VA: 0x75948a99e4
	public Void set_onGoodClicked(Action`1 value) { }
	// RVA: 0x2292360 VA: 0x75948aa360
	public Action get_onBackPressClicked() { }
	// RVA: 0x2291a68 VA: 0x75948a9a68
	public Void set_onBackPressClicked(Action value) { }
	// RVA: 0x22923c8 VA: 0x75948aa3c8
	public override Void OnValueChanged(VoucherSkinHomeViewProperty property) { }
	// RVA: 0x22916c8 VA: 0x75948a96c8
	public Void ShowRuleDetailView(Boolean show) { }
	// RVA: 0x2292be0 VA: 0x75948aabe0
	private Void Start() { }
	// RVA: 0x2292c48 VA: 0x75948aac48
	private Void OnEnable() { }
	// RVA: 0x22927e8 VA: 0x75948aa7e8
	private Void _InitIfNot() { }
	// RVA: 0x2292ad0 VA: 0x75948aaad0
	private Void _ResetRuleView() { }
	// RVA: 0x22929bc VA: 0x75948aa9bc
	private Void _ShowNothingTips() { }
	// RVA: 0x2292d5c VA: 0x75948aad5c
	public Void .ctor() { }
	// RVA: 0x2292e98 VA: 0x75948aae98
	private Void <_InitIfNot>b__26_0() { }
}
```
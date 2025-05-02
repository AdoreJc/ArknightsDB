# TuningProductMenuView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductSlotImageItemView _eyeSlotItemView`

- `TuningProductSlotImageItemView _orcheItemView`

- `TuningProductSlotGroupItemView _slotUnknownGroupView`

- `GameObject _canNextStepBtnObj`

- `GameObject _cannotNextStepBtnObj`

- `Button _nextStepBtn`

- `GameObject _makeBtnObj`

- `Text _productTypeName`

- `Text _orcheName`

- `Text _formName`

- `Text _formNameFrontBrackets`

- `Text _formNameBehindBracket`

- `TuningProductSlotGroupItemView _descUnknownGroupView`

- `TuningProductSlotGroupItemView _productTypeDescGroupView`

- `TuningProductSlotGroupItemView _formDescGroupView`

- `TuningProductSlotGroupItemView _orcheDescGroupView`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _RenderCardSlotItem(TuningProductViewModel)`

- `Void _RenderCardDesc(TuningProductViewModel)`

- `Void BackToSelectFrag()`

- `Void NextStep()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductMenuView : DataBinder`1
{
	private const String UNKNOWN_FORM_DESC; // 0x0
	private List`1 _fragSlotItemViews; // 0x20
	private TuningProductSlotImageItemView _eyeSlotItemView; // 0x28
	private TuningProductSlotImageItemView _orcheItemView; // 0x30
	private TuningProductSlotGroupItemView _slotUnknownGroupView; // 0x38
	private GameObject _canNextStepBtnObj; // 0x40
	private GameObject _cannotNextStepBtnObj; // 0x48
	private Button _nextStepBtn; // 0x50
	private GameObject _makeBtnObj; // 0x58
	private Text _productTypeName; // 0x60
	private Text _orcheName; // 0x68
	private Text _formName; // 0x70
	private Text _formNameFrontBrackets; // 0x78
	private Text _formNameBehindBracket; // 0x80
	private TuningProductSlotGroupItemView _descUnknownGroupView; // 0x88
	private TuningProductSlotGroupItemView _productTypeDescGroupView; // 0x90
	private TuningProductSlotGroupItemView _formDescGroupView; // 0x98
	private TuningProductSlotGroupItemView _orcheDescGroupView; // 0xa0
	private UIStateFinder m_stateFinder; // 0xa8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderCardSlotItem; // 0x8
	private static DelegateBridge __Hotfix0__RenderCardDesc; // 0x10
	private static DelegateBridge __Hotfix0_BackToSelectFrag; // 0x18
	private static DelegateBridge __Hotfix0_NextStep; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23352fc VA: 0x759494d2fc
	public override Void OnValueChanged(TuningProductProperty property) { }
	// RVA: 0x2335544 VA: 0x759494d544
	private Void _RenderCardSlotItem(TuningProductViewModel model) { }
	// RVA: 0x23356f0 VA: 0x759494d6f0
	private Void _RenderCardDesc(TuningProductViewModel model) { }
	// RVA: 0x2335e90 VA: 0x759494de90
	public Void BackToSelectFrag() { }
	// RVA: 0x2335f34 VA: 0x759494df34
	public Void NextStep() { }
	// RVA: 0x2335fd8 VA: 0x759494dfd8
	public Void .ctor() { }
}
```
# Act29signDynChoiceView

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `Act29signExpandView _expandView`

- `Act29signChoiceConfirmBtnView _choiceConfirmBtn`

- `RectTransform _choiceConfirmBtnContainer`

- `Text _questionDescText`

- `GameObject _initDayOnlyReturnBtn`

- `Model m_expandViewModel`

- `Int32 m_expandIndex`

- `Boolean m_lockConfirm`


## Methods

- `Void set_confirmAction(Action`1)`

- `Void Render(Act29signDynViewModel)`

- `Void _OnConfirmClick(String)`

- `Void _RenderExpandView(Boolean)`

- `Void _EnsureConfirmBtnCount(Int32)`

- `Void _RenderConfirmBtn(Act29signDynViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signDynChoiceView : MonoBehaviour, IHotfixable
{
	private const Single EXPAND_DELAY; // 0x0
	private Act29signExpandView _expandView; // 0x18
	private Act29signChoiceConfirmBtnView _choiceConfirmBtn; // 0x20
	private RectTransform _choiceConfirmBtnContainer; // 0x28
	private Text _questionDescText; // 0x30
	private GameObject _initDayOnlyReturnBtn; // 0x38
	private Model m_expandViewModel; // 0x40
	private List`1 m_confirmBtnList; // 0x50
	private Int32 m_expandIndex; // 0x58
	private Boolean m_lockConfirm; // 0x5c
	private Action`1 <confirmAction>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_confirmAction; // 0x0
	private static DelegateBridge __Hotfix0_set_confirmAction; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__OnConfirmClick; // 0x18
	private static DelegateBridge __Hotfix0__RenderExpandView; // 0x20
	private static DelegateBridge __Hotfix0__EnsureConfirmBtnCount; // 0x28
	private static DelegateBridge __Hotfix0__RenderConfirmBtn; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`1 confirmAction { get; set; }

	// RVA: 0x325bab4 VA: 0x7595873ab4
	private Action`1 get_confirmAction() { }
	// RVA: 0x325b0d0 VA: 0x75958730d0
	public Void set_confirmAction(Action`1 value) { }
	// RVA: 0x325bb1c VA: 0x7595873b1c
	public Void Render(Act29signDynViewModel viewModel) { }
	// RVA: 0x325bf80 VA: 0x7595873f80
	private Void _OnConfirmClick(String btnOption) { }
	// RVA: 0x325bcfc VA: 0x7595873cfc
	private Void _RenderExpandView(Boolean isShow) { }
	// RVA: 0x325c140 VA: 0x7595874140
	private Void _EnsureConfirmBtnCount(Int32 count) { }
	// RVA: 0x325bdb4 VA: 0x7595873db4
	private Void _RenderConfirmBtn(Act29signDynViewModel viewModel) { }
	// RVA: 0x325c5e0 VA: 0x75958745e0
	public Void .ctor() { }
}
```
# Act29signDynSecondView

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `CanvasGroup _canvasGroup`

- `Act29signDynChoiceView _choiceView`

- `Act29signProgressView _progressView`

- `Act29signExpandView _expandView`

- `Config _itemConfig`

- `Image _dynRewardImage`

- `Image _initDayChoiceImage`

- `Text _intDayChoiceDescText`

- `FadeSwitchTween m_fadeSwitchTween`

- `Boolean m_hasInited`

- `Model m_expandViewModel`

- `Int32 m_expandIndex`

- `Action <returnBtnAction>k__BackingField`


## Properties

- `Action returnBtnAction`


## Methods

- `Void set_loadDynRewardSprite(Func`2)`

- `Void set_loadInitDayChoiceSprite(Func`2)`

- `Void set_setDelayFunc(Func`3)`

- `Void set_isDelayProcessing(Func`1)`

- `Action get_returnBtnAction()`

- `Void set_returnBtnAction(Action)`

- `Void _ConfigExpandViewItemState(Act29signDynViewModel)`

- `Void _ConfigExpandViewItemContent(Act29signDynViewModel)`

- `Void _ConfigInitDayChoiceContent(Act29signDynViewModel)`

- `Void _InitIfNot(Act29signDynViewModel)`

- `Void _RenderExpandView(Boolean)`

- `Void _InvokeReturnBtnAction()`

- `Void EventOnReturnBtnInvoke()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signDynSecondView : DataBinder`1
{
	private const Single EXPAND_DELAY; // 0x0
	private const Single CANCEL_DELAY; // 0x0
	private CanvasGroup _canvasGroup; // 0x20
	private Act29signDynChoiceView _choiceView; // 0x28
	private Act29signProgressView _progressView; // 0x30
	private Act29signExpandView _expandView; // 0x38
	private Act29signExpandViewItem[] _expandViewItemsList; // 0x40
	private Config _itemConfig; // 0x48
	private Image _dynRewardImage; // 0x98
	private Image _initDayChoiceImage; // 0xa0
	private Text _intDayChoiceDescText; // 0xa8
	private FadeSwitchTween m_fadeSwitchTween; // 0xb0
	private Boolean m_hasInited; // 0xb8
	private Model m_expandViewModel; // 0xbc
	private Int32 m_expandIndex; // 0xcc
	private Func`2 <loadDynRewardSprite>k__BackingField; // 0xd0
	private Func`2 <loadInitDayChoiceSprite>k__BackingField; // 0xd8
	private Func`3 <setDelayFunc>k__BackingField; // 0xe0
	private Func`1 <isDelayProcessing>k__BackingField; // 0xe8
	private Action <returnBtnAction>k__BackingField; // 0xf0
	private static DelegateBridge __Hotfix0_get_loadDynRewardSprite; // 0x0
	private static DelegateBridge __Hotfix0_set_loadDynRewardSprite; // 0x8
	private static DelegateBridge __Hotfix0_get_loadInitDayChoiceSprite; // 0x10
	private static DelegateBridge __Hotfix0_set_loadInitDayChoiceSprite; // 0x18
	private static DelegateBridge __Hotfix0_get_setDelayFunc; // 0x20
	private static DelegateBridge __Hotfix0_set_setDelayFunc; // 0x28
	private static DelegateBridge __Hotfix0_get_isDelayProcessing; // 0x30
	private static DelegateBridge __Hotfix0_set_isDelayProcessing; // 0x38
	private static DelegateBridge __Hotfix0_get_returnBtnAction; // 0x40
	private static DelegateBridge __Hotfix0_set_returnBtnAction; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0__ConfigExpandViewItemState; // 0x58
	private static DelegateBridge __Hotfix0__ConfigExpandViewItemContent; // 0x60
	private static DelegateBridge __Hotfix0__ConfigInitDayChoiceContent; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x70
	private static DelegateBridge __Hotfix0__RenderExpandView; // 0x78
	private static DelegateBridge __Hotfix0__InvokeReturnBtnAction; // 0x80
	private static DelegateBridge __Hotfix0_EventOnReturnBtnInvoke; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	private Func`2 loadDynRewardSprite { get; set; }
	private Func`2 loadInitDayChoiceSprite { get; set; }
	private Func`3 setDelayFunc { get; set; }
	private Func`1 isDelayProcessing { get; set; }
	private Action returnBtnAction { get; set; }

	// RVA: 0x325cf28 VA: 0x7595874f28
	private Func`2 get_loadDynRewardSprite() { }
	// RVA: 0x325b3e8 VA: 0x75958733e8
	public Void set_loadDynRewardSprite(Func`2 value) { }
	// RVA: 0x325cf90 VA: 0x7595874f90
	private Func`2 get_loadInitDayChoiceSprite() { }
	// RVA: 0x325b46c VA: 0x759587346c
	public Void set_loadInitDayChoiceSprite(Func`2 value) { }
	// RVA: 0x325cff8 VA: 0x7595874ff8
	private Func`3 get_setDelayFunc() { }
	// RVA: 0x325b1d8 VA: 0x75958731d8
	public Void set_setDelayFunc(Func`3 value) { }
	// RVA: 0x325d060 VA: 0x7595875060
	private Func`1 get_isDelayProcessing() { }
	// RVA: 0x325b25c VA: 0x759587325c
	public Void set_isDelayProcessing(Func`1 value) { }
	// RVA: 0x325d0c8 VA: 0x75958750c8
	private Action get_returnBtnAction() { }
	// RVA: 0x325ac2c VA: 0x7595872c2c
	public Void set_returnBtnAction(Action value) { }
	// RVA: 0x325d130 VA: 0x7595875130
	public override Void OnValueChanged(Act29signDynProperty property) { }
	// RVA: 0x325d4f4 VA: 0x75958754f4
	private Void _ConfigExpandViewItemState(Act29signDynViewModel viewModel) { }
	// RVA: 0x325d334 VA: 0x7595875334
	private Void _ConfigExpandViewItemContent(Act29signDynViewModel viewModel) { }
	// RVA: 0x325d75c VA: 0x759587575c
	private Void _ConfigInitDayChoiceContent(Act29signDynViewModel viewModel) { }
	// RVA: 0x325d240 VA: 0x7595875240
	private Void _InitIfNot(Act29signDynViewModel viewModel) { }
	// RVA: 0x325df14 VA: 0x7595875f14
	private Void _RenderExpandView(Boolean isShow) { }
	// RVA: 0x325dfd0 VA: 0x7595875fd0
	private Void _InvokeReturnBtnAction() { }
	// RVA: 0x325e06c VA: 0x759587606c
	public Void EventOnReturnBtnInvoke() { }
	// RVA: 0x325e1d4 VA: 0x75958761d4
	public Void .ctor() { }
}
```
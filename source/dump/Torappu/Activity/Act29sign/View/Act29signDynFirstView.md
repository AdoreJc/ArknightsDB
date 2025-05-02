# Act29signDynFirstView

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `CanvasGroup _canvasGroup`

- `Text _questionDescText`

- `Text _tipText`

- `FadeSwitchTween m_fadeSwitchTween`

- `Boolean m_hasInited`

- `Boolean m_lockChoice`


## Methods

- `Void set_loadDynRewardSprite(Func`2)`

- `Void set_loadInitDayChoiceSprite(Func`2)`

- `Void set_choiceBtnAction(Action`1)`

- `Void EventOnChoiceBtnClick(Int32)`

- `Void _InitIfNot(Act29signDynViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signDynFirstView : DataBinder`1
{
	private CanvasGroup _canvasGroup; // 0x20
	private Image[] _initDayChoiceImages; // 0x28
	private Image[] _dynRewardImages; // 0x30
	private Text[] _optionDescTexts; // 0x38
	private Text _questionDescText; // 0x40
	private Text _tipText; // 0x48
	private FadeSwitchTween m_fadeSwitchTween; // 0x50
	private Boolean m_hasInited; // 0x58
	private Boolean m_lockChoice; // 0x59
	private Func`2 <loadDynRewardSprite>k__BackingField; // 0x60
	private Func`2 <loadInitDayChoiceSprite>k__BackingField; // 0x68
	private Action`1 <choiceBtnAction>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_loadDynRewardSprite; // 0x0
	private static DelegateBridge __Hotfix0_set_loadDynRewardSprite; // 0x8
	private static DelegateBridge __Hotfix0_get_loadInitDayChoiceSprite; // 0x10
	private static DelegateBridge __Hotfix0_set_loadInitDayChoiceSprite; // 0x18
	private static DelegateBridge __Hotfix0_get_choiceBtnAction; // 0x20
	private static DelegateBridge __Hotfix0_set_choiceBtnAction; // 0x28
	private static DelegateBridge __Hotfix0_EventOnChoiceBtnClick; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Func`2 loadDynRewardSprite { get; set; }
	private Func`2 loadInitDayChoiceSprite { get; set; }
	private Action`1 choiceBtnAction { get; set; }

	// RVA: 0x325c650 VA: 0x7595874650
	private Func`2 get_loadDynRewardSprite() { }
	// RVA: 0x325b2e0 VA: 0x75958732e0
	public Void set_loadDynRewardSprite(Func`2 value) { }
	// RVA: 0x325c6b8 VA: 0x75958746b8
	private Func`2 get_loadInitDayChoiceSprite() { }
	// RVA: 0x325b364 VA: 0x7595873364
	public Void set_loadInitDayChoiceSprite(Func`2 value) { }
	// RVA: 0x325c720 VA: 0x7595874720
	private Action`1 get_choiceBtnAction() { }
	// RVA: 0x325b154 VA: 0x7595873154
	public Void set_choiceBtnAction(Action`1 value) { }
	// RVA: 0x325c788 VA: 0x7595874788
	public Void EventOnChoiceBtnClick(Int32 btnIndex) { }
	// RVA: 0x325c87c VA: 0x759587487c
	public override Void OnValueChanged(Act29signDynProperty property) { }
	// RVA: 0x325c944 VA: 0x7595874944
	private Void _InitIfNot(Act29signDynViewModel viewModel) { }
	// RVA: 0x325ce98 VA: 0x7595874e98
	public Void .ctor() { }
}
```
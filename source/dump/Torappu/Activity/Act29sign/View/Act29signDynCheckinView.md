# Act29signDynCheckinView

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `Act29signDynFirstView _firstView`

- `Act29signDynSecondView _secondView`

- `Act29signDynChoiceView _choiceView`

- `Act29signProgressView _progressView`

- `Act29signDynProperty m_property`

- `Boolean m_hasInited`

- `Act29signDynViewModel m_viewModel`

- `ActivityCommonCheckinViewModel m_upperViewModel`


## Methods

- `Void EventOnCloseBtnClick()`

- `Void _EnterSecondViewWithChoice(Int32)`

- `Void _EnterInitDayView()`

- `Void _EnterViewState(DynViewState)`

- `Void _RefreshData(ActivityCommonCheckinViewModel)`

- `Void _CloseDynViewOnly()`

- `Void _InitIfNot(ActivityCommonCheckinViewModel)`

- `Sprite _LoadDynRewardSprite(String)`

- `Sprite _LoadInitDayChoiceSprite(String)`

- `Void _SafeConfirmReward(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signDynCheckinView : ActivityCheckinEntryView
{
	private Act29signDynFirstView _firstView; // 0x50
	private Act29signDynSecondView _secondView; // 0x58
	private Act29signDynChoiceView _choiceView; // 0x60
	private Act29signProgressView _progressView; // 0x68
	private Act29signDynProperty m_property; // 0x70
	private Boolean m_hasInited; // 0x78
	private Act29signDynViewModel m_viewModel; // 0x80
	private ActivityCommonCheckinViewModel m_upperViewModel; // 0x88
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0_GetViewType; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCloseBtnClick; // 0x10
	private static DelegateBridge __Hotfix0__EnterSecondViewWithChoice; // 0x18
	private static DelegateBridge __Hotfix0__EnterInitDayView; // 0x20
	private static DelegateBridge __Hotfix0__EnterViewState; // 0x28
	private static DelegateBridge __Hotfix0__RefreshData; // 0x30
	private static DelegateBridge __Hotfix0__CloseDynViewOnly; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__LoadDynRewardSprite; // 0x48
	private static DelegateBridge __Hotfix0__LoadInitDayChoiceSprite; // 0x50
	private static DelegateBridge __Hotfix0__SafeConfirmReward; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x325a0a0 VA: 0x75958720a0
	public override Void RenderView(ActivityCommonCheckinViewModel upperViewModel) { }
	// RVA: 0x325a734 VA: 0x7595872734
	public override CheckinViewType GetViewType() { }
	// RVA: 0x325a79c VA: 0x759587279c
	public Void EventOnCloseBtnClick() { }
	// RVA: 0x325a808 VA: 0x7595872808
	private Void _EnterSecondViewWithChoice(Int32 choiceIndex) { }
	// RVA: 0x325a940 VA: 0x7595872940
	private Void _EnterInitDayView() { }
	// RVA: 0x325a9ac VA: 0x75958729ac
	private Void _EnterViewState(DynViewState state) { }
	// RVA: 0x325a5b4 VA: 0x75958725b4
	private Void _RefreshData(ActivityCommonCheckinViewModel upperViewModel) { }
	// RVA: 0x325acb0 VA: 0x7595872cb0
	private Void _CloseDynViewOnly() { }
	// RVA: 0x325a190 VA: 0x7595872190
	private Void _InitIfNot(ActivityCommonCheckinViewModel upperViewModel) { }
	// RVA: 0x325b4f0 VA: 0x75958734f0
	private Sprite _LoadDynRewardSprite(String option) { }
	// RVA: 0x325b6a0 VA: 0x75958736a0
	private Sprite _LoadInitDayChoiceSprite(String option) { }
	// RVA: 0x325b790 VA: 0x7595873790
	private Void _SafeConfirmReward(String option) { }
	// RVA: 0x325ba44 VA: 0x7595873a44
	public Void .ctor() { }
}
```
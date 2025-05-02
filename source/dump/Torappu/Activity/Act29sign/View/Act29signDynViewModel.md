# Act29signDynViewModel

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `String activityId`

- `Boolean needDynViewByOption`

- `DynViewState dynViewState`

- `DynCheckInDailyInfo m_currentCheckinInfo`

- `PlayerCheckinOnlyTypeActivity m_playerInfo`

- `DynamicCheckInData m_dynamicCheckInData`

- `Int32 <initDayChoiceByButton>k__BackingField`


## Properties

- `Int32 initDayChoiceByButton`

- `String chosenOptionOnInitDay`

- `String currentQuestionDesc`

- `Int32 currentDynShowDay`

- `Int32 progressShowDay`

- `String initOption`

- `String initDayQuestionDesc`

- `String initDayTip`

- `String initDayConfirmDesc`

- `Boolean isInitDay`

- `OptionInfo lastRecordOptionInfo`

- `String lastRecordOption`


## Methods

- `Int32 get_initDayChoiceByButton()`

- `Void set_initDayChoiceByButton(Int32)`

- `String get_chosenOptionOnInitDay()`

- `String get_currentQuestionDesc()`

- `Int32 get_currentDynShowDay()`

- `Int32 get_progressShowDay()`

- `String get_initOption()`

- `String get_initDayQuestionDesc()`

- `String get_initDayTip()`

- `String get_initDayConfirmDesc()`

- `Boolean get_isInitDay()`

- `OptionInfo get_lastRecordOptionInfo()`

- `String get_lastRecordOption()`

- `DynCheckInDailyInfo GetDynDailyInfo(Int32)`

- `OptionInfo GetDynOptionInfo(String)`

- `String GetInitDayChoiceDesc(String)`

- `Void LoadData(ActivityCommonCheckinViewModel)`

- `Void _LoadInitDayData()`

- `Void RefreshData(ActivityCommonCheckinViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signDynViewModel : IHotfixable
{
	public String activityId; // 0x10
	public Boolean needDynViewByOption; // 0x18
	public DynViewState dynViewState; // 0x1c
	private DynCheckInDailyInfo m_currentCheckinInfo; // 0x20
	private Dictionary`2 m_initDayChoiceDescDict; // 0x28
	private Dictionary`2 m_dynDailyInfoDict; // 0x30
	private PlayerCheckinOnlyTypeActivity m_playerInfo; // 0x38
	private Dictionary`2 m_normalCheckinDict; // 0x40
	private DynamicCheckInData m_dynamicCheckInData; // 0x48
	private Int32 <initDayChoiceByButton>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_initDayChoiceByButton; // 0x0
	private static DelegateBridge __Hotfix0_set_initDayChoiceByButton; // 0x8
	private static DelegateBridge __Hotfix0_get_chosenOptionOnInitDay; // 0x10
	private static DelegateBridge __Hotfix0_get_currentQuestionDesc; // 0x18
	private static DelegateBridge __Hotfix0_get_currentDynShowDay; // 0x20
	private static DelegateBridge __Hotfix0_get_progressShowDay; // 0x28
	private static DelegateBridge __Hotfix0_get_currentDynOptionList; // 0x30
	private static DelegateBridge __Hotfix0_get_optionsOnInitDay; // 0x38
	private static DelegateBridge __Hotfix0_get_initOption; // 0x40
	private static DelegateBridge __Hotfix0_get_initDayQuestionDesc; // 0x48
	private static DelegateBridge __Hotfix0_get_initDayTip; // 0x50
	private static DelegateBridge __Hotfix0_get_initDayConfirmDesc; // 0x58
	private static DelegateBridge __Hotfix0_get_isInitDay; // 0x60
	private static DelegateBridge __Hotfix0_get_lastRecordOptionInfo; // 0x68
	private static DelegateBridge __Hotfix0_get_lastRecordOption; // 0x70
	private static DelegateBridge __Hotfix0_get_dynOptionInfoDict; // 0x78
	private static DelegateBridge __Hotfix0_GetDynDailyInfo; // 0x80
	private static DelegateBridge __Hotfix0_GetDynOptionInfo; // 0x88
	private static DelegateBridge __Hotfix0_GetInitDayChoiceDesc; // 0x90
	private static DelegateBridge __Hotfix0_GetRewardList; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0xa0
	private static DelegateBridge __Hotfix0__LoadInitDayData; // 0xa8
	private static DelegateBridge __Hotfix0_RefreshData; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	private Int32 initDayChoiceByButton { get; set; }
	public String chosenOptionOnInitDay { get; }
	public String currentQuestionDesc { get; }
	public Int32 currentDynShowDay { get; }
	public Int32 progressShowDay { get; }
	public List`1 currentDynOptionList { get; }
	public List`1 optionsOnInitDay { get; }
	public String initOption { get; }
	public String initDayQuestionDesc { get; }
	public String initDayTip { get; }
	public String initDayConfirmDesc { get; }
	public Boolean isInitDay { get; }
	public OptionInfo lastRecordOptionInfo { get; }
	private String lastRecordOption { get; }
	private Dictionary`2 dynOptionInfoDict { get; }

	// RVA: 0x325e264 VA: 0x7595876264
	private Int32 get_initDayChoiceByButton() { }
	// RVA: 0x325a8c4 VA: 0x75958728c4
	public Void set_initDayChoiceByButton(Int32 value) { }
	// RVA: 0x325c498 VA: 0x7595874498
	public String get_chosenOptionOnInitDay() { }
	// RVA: 0x325bc68 VA: 0x7595873c68
	public String get_currentQuestionDesc() { }
	// RVA: 0x325b9cc VA: 0x75958739cc
	public Int32 get_currentDynShowDay() { }
	// RVA: 0x325d99c VA: 0x759587599c
	public Int32 get_progressShowDay() { }
	// RVA: 0x325b954 VA: 0x7595873954
	public List`1 get_currentDynOptionList() { }
	// RVA: 0x325cc28 VA: 0x7595874c28
	public List`1 get_optionsOnInitDay() { }
	// RVA: 0x325e2cc VA: 0x75958762cc
	public String get_initOption() { }
	// RVA: 0x325cda0 VA: 0x7595874da0
	public String get_initDayQuestionDesc() { }
	// RVA: 0x325ce1c VA: 0x7595874e1c
	public String get_initDayTip() { }
	// RVA: 0x325c41c VA: 0x759587441c
	public String get_initDayConfirmDesc() { }
	// RVA: 0x325ab90 VA: 0x7595872b90
	public Boolean get_isInitDay() { }
	// RVA: 0x325e360 VA: 0x7595876360
	public OptionInfo get_lastRecordOptionInfo() { }
	// RVA: 0x325e4a0 VA: 0x75958764a0
	private String get_lastRecordOption() { }
	// RVA: 0x325e428 VA: 0x7595876428
	private Dictionary`2 get_dynOptionInfoDict() { }
	// RVA: 0x325da10 VA: 0x7595875a10
	public DynCheckInDailyInfo GetDynDailyInfo(Int32 dayIndex) { }
	// RVA: 0x325b5e0 VA: 0x75958735e0
	public OptionInfo GetDynOptionInfo(String optionId) { }
	// RVA: 0x325ccd4 VA: 0x7595874cd4
	public String GetInitDayChoiceDesc(String option) { }
	// RVA: 0x325dd70 VA: 0x7595875d70
	public List`1 GetRewardList(Int32 dayIndex) { }
	// RVA: 0x325ad90 VA: 0x7595872d90
	public Void LoadData(ActivityCommonCheckinViewModel viewModel) { }
	// RVA: 0x325e584 VA: 0x7595876584
	private Void _LoadInitDayData() { }
	// RVA: 0x325aa54 VA: 0x7595872a54
	public Void RefreshData(ActivityCommonCheckinViewModel viewModel) { }
	// RVA: 0x325ad20 VA: 0x7595872d20
	public Void .ctor() { }
}
```
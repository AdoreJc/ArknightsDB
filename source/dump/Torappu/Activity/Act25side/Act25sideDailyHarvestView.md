# Act25sideDailyHarvestView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `GameObject _panelProcessing`

- `GameObject _panelDone`

- `Text _textTimer`

- `Text _rewardCount`

- `Text _rewardRatio`

- `Text _nextDayBonusRatio`

- `Text _titleText`

- `Slider _progressSlider`

- `GameObject _pauseObj`

- `GameObject _processObj`

- `GameObject _nextRatio`

- `Text _rewardFinishCount`

- `Action eventOnHarvest`

- `UIStateFinder m_stateFinder`

- `CountDownTask m_harvestTask`

- `Act25sideDailyHarvestViewModel m_cachedModel`

- `Act25SideData m_cachedCfg`

- `DailyFarmData m_cachendHarvestData`


## Methods

- `Void _RenderView(Act25sideDailyHarvestViewModel)`

- `Void _SetCountDown(Int64)`

- `Void _DealWithTimeout()`

- `Void _TickHarvestCountDown(TickValue)`

- `Void _RefreshSliderBar(TickValue)`

- `Void _RefreshPanel()`

- `Void _ProcessLastDay()`

- `Int32 _GetCurrentRatio()`

- `Void OnHarvestClick()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideDailyHarvestView : DataBinder`1
{
	private GameObject _panelProcessing; // 0x20
	private GameObject _panelDone; // 0x28
	private Text _textTimer; // 0x30
	private Text _rewardCount; // 0x38
	private Text _rewardRatio; // 0x40
	private Text _nextDayBonusRatio; // 0x48
	private Text _titleText; // 0x50
	private Slider _progressSlider; // 0x58
	private GameObject _pauseObj; // 0x60
	private GameObject _processObj; // 0x68
	private GameObject _nextRatio; // 0x70
	private Text _rewardFinishCount; // 0x78
	public Action eventOnHarvest; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private CountDownTask m_harvestTask; // 0x98
	private Act25sideDailyHarvestViewModel m_cachedModel; // 0xa0
	private Act25SideData m_cachedCfg; // 0xa8
	private DailyFarmData m_cachendHarvestData; // 0xb0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderView; // 0x8
	private static DelegateBridge __Hotfix0__SetCountDown; // 0x10
	private static DelegateBridge __Hotfix0__DealWithTimeout; // 0x18
	private static DelegateBridge __Hotfix0__TickHarvestCountDown; // 0x20
	private static DelegateBridge __Hotfix0__RefreshSliderBar; // 0x28
	private static DelegateBridge __Hotfix0__RefreshPanel; // 0x30
	private static DelegateBridge __Hotfix0__ProcessLastDay; // 0x38
	private static DelegateBridge __Hotfix0__GetCurrentRatio; // 0x40
	private static DelegateBridge __Hotfix0_OnHarvestClick; // 0x48
	private static DelegateBridge __Hotfix0_Update; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x32802a8 VA: 0x75958982a8
	public override Void OnValueChanged(Act25sideDailyHarvestProperty property) { }
	// RVA: 0x3280378 VA: 0x7595898378
	private Void _RenderView(Act25sideDailyHarvestViewModel viewModel) { }
	// RVA: 0x32808f0 VA: 0x75958988f0
	private Void _SetCountDown(Int64 remainSecs) { }
	// RVA: 0x3280c20 VA: 0x7595898c20
	private Void _DealWithTimeout() { }
	// RVA: 0x3280a8c VA: 0x7595898a8c
	private Void _TickHarvestCountDown(TickValue tickValue) { }
	// RVA: 0x3280cd4 VA: 0x7595898cd4
	private Void _RefreshSliderBar(TickValue tickValue) { }
	// RVA: 0x32804d8 VA: 0x75958984d8
	private Void _RefreshPanel() { }
	// RVA: 0x3280d9c VA: 0x7595898d9c
	private Void _ProcessLastDay() { }
	// RVA: 0x3280850 VA: 0x7595898850
	private Int32 _GetCurrentRatio() { }
	// RVA: 0x3280e2c VA: 0x7595898e2c
	public Void OnHarvestClick() { }
	// RVA: 0x3280ebc VA: 0x7595898ebc
	private Void Update() { }
	// RVA: 0x3280f38 VA: 0x7595898f38
	public Void .ctor() { }
}
```
# Act25sideHarvestButtonView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `GameObject _panelProcessing`

- `GameObject _panelDone`

- `GameObject _objMax`

- `UIAnimationLocation _processAnim`

- `UIAnimationLocation _harvestAnim`

- `Text _processText`

- `Button _btn`

- `GameObject _processDots`

- `GameObject _endDots`

- `Action eventOnHarvest`

- `CountDownTask m_harvestTask`

- `Act25sideDailyHarvestViewModel m_cachedModel`

- `Tween m_processTween`

- `Tween m_harvestTween`


## Methods

- `Void _SetCountDown()`

- `Void _DealWithTimeout()`

- `Void _ResetAnim()`

- `Void _TryStartAnim(Boolean)`

- `Void _RefreshPanel(Act25sideDailyHarvestViewModel)`

- `Void _ProcessLastDay(Act25sideDailyHarvestViewModel)`

- `Void OnHarvestClick()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideHarvestButtonView : DataBinder`1
{
	private GameObject _panelProcessing; // 0x20
	private GameObject _panelDone; // 0x28
	private GameObject _objMax; // 0x30
	private UIAnimationLocation _processAnim; // 0x38
	private UIAnimationLocation _harvestAnim; // 0x48
	private Text _processText; // 0x58
	private Button _btn; // 0x60
	private GameObject _processDots; // 0x68
	private GameObject _endDots; // 0x70
	public Action eventOnHarvest; // 0x78
	private CountDownTask m_harvestTask; // 0x80
	private Act25sideDailyHarvestViewModel m_cachedModel; // 0x88
	private Tween m_processTween; // 0x90
	private Tween m_harvestTween; // 0x98
	private static DelegateBridge __Hotfix0__SetCountDown; // 0x0
	private static DelegateBridge __Hotfix0__DealWithTimeout; // 0x8
	private static DelegateBridge __Hotfix0__ResetAnim; // 0x10
	private static DelegateBridge __Hotfix0__TryStartAnim; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__RefreshPanel; // 0x28
	private static DelegateBridge __Hotfix0__ProcessLastDay; // 0x30
	private static DelegateBridge __Hotfix0_OnHarvestClick; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3280fc8 VA: 0x7595898fc8
	private Void _SetCountDown() { }
	// RVA: 0x3281110 VA: 0x7595899110
	private Void _DealWithTimeout() { }
	// RVA: 0x3281274 VA: 0x7595899274
	private Void _ResetAnim() { }
	// RVA: 0x328132c VA: 0x759589932c
	private Void _TryStartAnim(Boolean isAvailable) { }
	// RVA: 0x32814a0 VA: 0x75958994a0
	public override Void OnValueChanged(Act25sideDailyHarvestProperty property) { }
	// RVA: 0x328117c VA: 0x759589917c
	private Void _RefreshPanel(Act25sideDailyHarvestViewModel viewModel) { }
	// RVA: 0x32815dc VA: 0x75958995dc
	private Void _ProcessLastDay(Act25sideDailyHarvestViewModel viewModel) { }
	// RVA: 0x3281740 VA: 0x7595899740
	public Void OnHarvestClick() { }
	// RVA: 0x32817d0 VA: 0x75958997d0
	private Void Update() { }
	// RVA: 0x328184c VA: 0x759589984c
	public Void .ctor() { }
}
```
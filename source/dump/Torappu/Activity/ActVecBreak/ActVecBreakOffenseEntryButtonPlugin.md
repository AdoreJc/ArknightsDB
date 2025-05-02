# ActVecBreakOffenseEntryButtonPlugin

**Namespace:** `Torappu.Activity.ActVecBreak`


## Fields

- `GameObject _closedMask`

- `ActVecBreakOffenseEntryStatusView _noProgressView`

- `ActVecBreakOffenseEntryStatusView _inProgressView`

- `ActVecBreakOffenseEntryStatusView _stepCompleteView`

- `ActVecBreakOffenseEntryStatusView _allCompleteView`

- `GameObject m_trackPoint`

- `RectTransform _trackPointContainer`

- `GameObject _newProgressTrackPoint`

- `Button _buttonSelf`

- `ActVecBreakOffenseEntryViewModel m_viewModel`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateStateView(ActVecBreakOffenseEntryViewModel)`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActVecBreak
public class ActVecBreakOffenseEntryButtonPlugin : TemplateActivityCommonPlugin
{
	private GameObject _closedMask; // 0x28
	private ActVecBreakOffenseEntryStatusView _noProgressView; // 0x30
	private ActVecBreakOffenseEntryStatusView _inProgressView; // 0x38
	private ActVecBreakOffenseEntryStatusView _stepCompleteView; // 0x40
	private ActVecBreakOffenseEntryStatusView _allCompleteView; // 0x48
	private GameObject m_trackPoint; // 0x50
	private RectTransform _trackPointContainer; // 0x58
	private GameObject _newProgressTrackPoint; // 0x60
	private Button _buttonSelf; // 0x68
	private ActVecBreakOffenseEntryViewModel m_viewModel; // 0x70
	private Boolean m_isInited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge __Hotfix0__UpdateStateView; // 0x10
	private static DelegateBridge __Hotfix0_OnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30d557c VA: 0x75956ed57c
	private Void _InitIfNot() { }
	// RVA: 0x30d5704 VA: 0x75956ed704
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x30d59b8 VA: 0x75956ed9b8
	private Void _UpdateStateView(ActVecBreakOffenseEntryViewModel offenseEntryViewModel) { }
	// RVA: 0x30d5ce0 VA: 0x75956edce0
	public Void OnClicked() { }
	// RVA: 0x30d5e7c VA: 0x75956ede7c
	public Void .ctor() { }
}
```
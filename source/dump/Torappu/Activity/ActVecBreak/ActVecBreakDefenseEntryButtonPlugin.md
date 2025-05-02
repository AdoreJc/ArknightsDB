# ActVecBreakDefenseEntryButtonPlugin

**Namespace:** `Torappu.Activity.ActVecBreak`


## Fields

- `GameObject _closedMask`

- `Button _buttonSelf`

- `GameObject _lockedMask`

- `Text _lockedHint`

- `GameObject m_trackPoint`

- `RectTransform _trackPointContainer`

- `GameObject _newProgressTrackPoint`

- `ActVecBreakDefenseEntryViewModel m_viewModel`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActVecBreak
public class ActVecBreakDefenseEntryButtonPlugin : TemplateActivityCommonPlugin
{
	private GameObject _closedMask; // 0x28
	private Button _buttonSelf; // 0x30
	private GameObject _lockedMask; // 0x38
	private Text _lockedHint; // 0x40
	private GameObject m_trackPoint; // 0x48
	private RectTransform _trackPointContainer; // 0x50
	private GameObject _newProgressTrackPoint; // 0x58
	private ActVecBreakDefenseEntryViewModel m_viewModel; // 0x60
	private Boolean m_isInited; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge __Hotfix0_OnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30d3fd8 VA: 0x75956ebfd8
	private Void _InitIfNot() { }
	// RVA: 0x30d4160 VA: 0x75956ec160
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x30d4488 VA: 0x75956ec488
	public Void OnClicked() { }
	// RVA: 0x30d4624 VA: 0x75956ec624
	public Void .ctor() { }
}
```
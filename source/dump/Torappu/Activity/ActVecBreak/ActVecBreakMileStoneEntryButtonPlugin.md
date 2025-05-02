# ActVecBreakMileStoneEntryButtonPlugin

**Namespace:** `Torappu.Activity.ActVecBreak`


## Fields

- `Button _buttonSelf`

- `Text _mileStoneLevelText`

- `UIAtlasImage _mileStoneLevelProgressBar`

- `GameObject _maxLevelTag`

- `RectTransform _trackPointContainer`

- `GameObject _newProgressTrackPointPrefab`

- `GameObject m_newProgresstrackPoint`

- `TemplateActivityMilestoneGroupViewModel m_viewModel`

- `Boolean m_isEntryPluginInited`

- `Boolean m_isMileStoneEnable`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateVecBreakMileStoneLevel()`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActVecBreak
public class ActVecBreakMileStoneEntryButtonPlugin : AbstractTemplateActivityEntryMilestonePlugin
{
	private Button _buttonSelf; // 0x50
	private Text _mileStoneLevelText; // 0x58
	private UIAtlasImage _mileStoneLevelProgressBar; // 0x60
	private GameObject _maxLevelTag; // 0x68
	private RectTransform _trackPointContainer; // 0x70
	private GameObject _newProgressTrackPointPrefab; // 0x78
	private GameObject m_newProgresstrackPoint; // 0x80
	private TemplateActivityMilestoneGroupViewModel m_viewModel; // 0x88
	private Boolean m_isEntryPluginInited; // 0x90
	private Boolean m_isMileStoneEnable; // 0x91
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__UpdateVecBreakMileStoneLevel; // 0x10
	private static DelegateBridge __Hotfix0_OnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30d4694 VA: 0x75956ec694
	protected override Void OnViewModelRefresh(TemplateActivityMilestoneGroupViewModel viewModel) { }
	// RVA: 0x30d489c VA: 0x75956ec89c
	private Void _InitIfNot() { }
	// RVA: 0x30d4aa8 VA: 0x75956ecaa8
	private Void _UpdateVecBreakMileStoneLevel() { }
	// RVA: 0x30d4d2c VA: 0x75956ecd2c
	public Void OnClicked() { }
	// RVA: 0x30d4e48 VA: 0x75956ece48
	public Void .ctor() { }
}
```
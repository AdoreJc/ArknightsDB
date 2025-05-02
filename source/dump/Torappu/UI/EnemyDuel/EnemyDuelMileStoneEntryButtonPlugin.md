# EnemyDuelMileStoneEntryButtonPlugin

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Button _buttonSelf`

- `Text _mileStoneLevelText`

- `GameObject _maxLevelTag`

- `UICommonTrackPoint _newProgressTrack`

- `UIStateFinder m_stateFinder`

- `Boolean m_isMileStoneEnable`

- `Boolean m_isEntryPluginInited`

- `TrackPointViewProperty m_trackUpdatedProp`

- `TemplateActivityMilestoneGroupViewModel m_viewModel`


## Methods

- `Void _InitIfNot()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelMileStoneEntryButtonPlugin : AbstractTemplateActivityEntryMilestonePlugin
{
	private Button _buttonSelf; // 0x50
	private Text _mileStoneLevelText; // 0x58
	private GameObject _maxLevelTag; // 0x60
	private UICommonTrackPoint _newProgressTrack; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private Boolean m_isMileStoneEnable; // 0x80
	private Boolean m_isEntryPluginInited; // 0x81
	private TrackPointViewProperty m_trackUpdatedProp; // 0x88
	private TemplateActivityMilestoneGroupViewModel m_viewModel; // 0x90
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x294f9b8 VA: 0x7594f679b8
	protected override Void OnViewModelRefresh(TemplateActivityMilestoneGroupViewModel viewModel) { }
	// RVA: 0x294fd94 VA: 0x7594f67d94
	private Void _InitIfNot() { }
	// RVA: 0x294fef8 VA: 0x7594f67ef8
	public Void OnClick() { }
	// RVA: 0x294ffbc VA: 0x7594f67fbc
	public Void .ctor() { }
}
```
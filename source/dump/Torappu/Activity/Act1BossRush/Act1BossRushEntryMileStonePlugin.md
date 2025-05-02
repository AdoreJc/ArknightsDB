# Act1BossRushEntryMileStonePlugin

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `UICommonTrackPoint _newMileStoneTrackPoint`

- `Slider _mileStoneProgress`

- `Text _txtMileStoneLv`

- `GameObject _objMileStoneProgressing`

- `Text _textMileStoneExp`

- `GameObject _objMileStoneMax`

- `Boolean m_isInited`

- `String m_actId`

- `TrackPointViewProperty m_milestoneTrackProperty`


## Methods

- `Void OpenMilestone()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushEntryMileStonePlugin : TemplateActivityCommonPlugin
{
	private UICommonTrackPoint _newMileStoneTrackPoint; // 0x28
	private Slider _mileStoneProgress; // 0x30
	private Text _txtMileStoneLv; // 0x38
	private GameObject _objMileStoneProgressing; // 0x40
	private Text _textMileStoneExp; // 0x48
	private GameObject _objMileStoneMax; // 0x50
	private Boolean m_isInited; // 0x58
	private String m_actId; // 0x60
	private TrackPointViewProperty m_milestoneTrackProperty; // 0x68
	private const String MILESTONE_PROCESS; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_OpenMilestone; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x318f6c0 VA: 0x75957a76c0
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x318fa98 VA: 0x75957a7a98
	public Void OpenMilestone() { }
	// RVA: 0x318f9b0 VA: 0x75957a79b0
	private Void _InitIfNot() { }
	// RVA: 0x318fb80 VA: 0x75957a7b80
	public Void .ctor() { }
}
```
# Act13sideEntryButtonPlugin

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `GameObject _activeMissionButton`

- `GameObject _lockedMissionButton`

- `GameObject _activePrestigeButton`

- `GameObject _lockedPrestigeButton`

- `Text _lockedCond1`

- `Text _lockedCond2`

- `UICommonTrackPoint _newTrackPoint`

- `UICommonTrackPoint _newMissionTrackPoint`

- `TrackPointViewProperty m_property`

- `TrackPointViewProperty m_newProperty`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OpenMission()`

- `Void OpenPrestigeState()`

- `Void OpenArchive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideEntryButtonPlugin : TemplateActivityCommonPlugin
{
	private GameObject _activeMissionButton; // 0x28
	private GameObject _lockedMissionButton; // 0x30
	private GameObject _activePrestigeButton; // 0x38
	private GameObject _lockedPrestigeButton; // 0x40
	private Text _lockedCond1; // 0x48
	private Text _lockedCond2; // 0x50
	private UICommonTrackPoint _newTrackPoint; // 0x58
	private UICommonTrackPoint _newMissionTrackPoint; // 0x60
	private OrgPrestigeStatus[] _orgPrestigeList; // 0x68
	private TrackPointViewProperty m_property; // 0x70
	private TrackPointViewProperty m_newProperty; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OpenMission; // 0x8
	private static DelegateBridge __Hotfix0_OpenPrestigeState; // 0x10
	private static DelegateBridge __Hotfix0_OpenArchive; // 0x18
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3428650 VA: 0x7595a40650
	private Void _InitIfNot() { }
	// RVA: 0x3428788 VA: 0x7595a40788
	public Void OpenMission() { }
	// RVA: 0x3428810 VA: 0x7595a40810
	public Void OpenPrestigeState() { }
	// RVA: 0x3428898 VA: 0x7595a40898
	public Void OpenArchive() { }
	// RVA: 0x3428a5c VA: 0x7595a40a5c
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3428ebc VA: 0x7595a40ebc
	public Void .ctor() { }
}
```
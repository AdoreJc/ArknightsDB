# Act1BossRushEntryMissionButtonPlugin

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `UICommonTrackPoint _newMissionTrackPoint`

- `Boolean m_isInited`

- `TrackPointViewProperty m_missionTrackProperty`


## Methods

- `Void OpenMission()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushEntryMissionButtonPlugin : TemplateActivityCommonPlugin
{
	private UICommonTrackPoint _newMissionTrackPoint; // 0x28
	private Boolean m_isInited; // 0x30
	private TrackPointViewProperty m_missionTrackProperty; // 0x38
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_OpenMission; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3190d98 VA: 0x75957a8d98
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3190ffc VA: 0x75957a8ffc
	public Void OpenMission() { }
	// RVA: 0x3190f0c VA: 0x75957a8f0c
	private Void _InitIfNot() { }
	// RVA: 0x31910e4 VA: 0x75957a90e4
	public Void .ctor() { }
}
```
# Act1MainSSExploreView

**Namespace:** `Torappu.Activity.Act1mainss`


## Fields

- `UICommonTrackPoint _trackPoint`

- `UICommonTrackPoint _missionTrackPoint`

- `Text _lockedText`

- `GameObject _missionBtn`

- `GameObject _lockedPart`

- `GameObject _unlockedPart`

- `GameObject _inTimeLockedPart`

- `GameObject _notInTimeLockedPart`

- `Act1MainSSExploreTrackPoint m_trackPointModel`

- `TrackPointViewProperty m_property`

- `TrackPointViewProperty m_missionProperty`

- `Act1MainSSHomeExploreViewModel m_cacheViewModel`


## Methods

- `Void OnOpenPage()`

- `Void OnOpenMission()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1mainss
public class Act1MainSSExploreView : TemplateActivityCommonPlugin
{
	private UICommonTrackPoint _trackPoint; // 0x28
	private UICommonTrackPoint _missionTrackPoint; // 0x30
	private Text _lockedText; // 0x38
	private GameObject _missionBtn; // 0x40
	private GameObject _lockedPart; // 0x48
	private GameObject _unlockedPart; // 0x50
	private GameObject _inTimeLockedPart; // 0x58
	private GameObject _notInTimeLockedPart; // 0x60
	private Act1MainSSExploreTrackPoint m_trackPointModel; // 0x68
	private TrackPointViewProperty m_property; // 0x70
	private TrackPointViewProperty m_missionProperty; // 0x78
	private Act1MainSSHomeExploreViewModel m_cacheViewModel; // 0x80
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_OnOpenPage; // 0x8
	private static DelegateBridge __Hotfix0_OnOpenMission; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3393c4c VA: 0x75959abc4c
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3393ee0 VA: 0x75959abee0
	public Void OnOpenPage() { }
	// RVA: 0x3393fa0 VA: 0x75959abfa0
	public Void OnOpenMission() { }
	// RVA: 0x339417c VA: 0x75959ac17c
	public Void .ctor() { }
}
```
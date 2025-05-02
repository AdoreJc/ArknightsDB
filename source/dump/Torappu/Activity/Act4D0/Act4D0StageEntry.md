# Act4D0StageEntry

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `UIActTrackPoint _activityTrackPoint`

- `UIActTrackPoint _mileStoneTrackPoint`

- `Act4D0EntryStageObjContainer _stageContainer`

- `Text _stoneText`

- `GameObject _topMenu`

- `Transform _entryTopMenu`

- `Text _remainText`

- `Text _detailText`

- `GameObject _bannedPart`

- `Int32 _hourOffset`

- `TrackPointViewProperty m_activityRedPoint`

- `TrackPointViewProperty m_mileStoneRedPoint`

- `Boolean m_isInited`

- `CommonTopMenu m_topMenu`


## Methods

- `GameObject GetTopMenu()`

- `Void InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0StageEntry : ActivityStageSingleComponent
{
	private UIActTrackPoint _activityTrackPoint; // 0x20
	private UIActTrackPoint _mileStoneTrackPoint; // 0x28
	private Act4D0EntryStageObjContainer _stageContainer; // 0x30
	private Text _stoneText; // 0x38
	private GameObject _topMenu; // 0x40
	private Transform _entryTopMenu; // 0x48
	private Text _remainText; // 0x50
	private Text _detailText; // 0x58
	private GameObject _bannedPart; // 0x60
	private Int32 _hourOffset; // 0x68
	private TrackPointViewProperty m_activityRedPoint; // 0x70
	private TrackPointViewProperty m_mileStoneRedPoint; // 0x78
	private Boolean m_isInited; // 0x80
	private CommonTopMenu m_topMenu; // 0x88
	private static DelegateBridge __Hotfix0_GetTopMenu; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31daca4 VA: 0x75957f2ca4
	public GameObject GetTopMenu() { }
	// RVA: 0x31dad0c VA: 0x75957f2d0c
	public Void InitData() { }
	// RVA: 0x31dbc64 VA: 0x75957f3c64
	public Void .ctor() { }
}
```
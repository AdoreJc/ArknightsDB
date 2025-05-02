# Act3D0StageEntry

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Image _buttonImg`

- `Image _backImg`

- `Image _boxImg`

- `Text _timeInfo`

- `Text _stateInfo`

- `UIActTrackPoint _actTrackPoint`

- `Button _mileStoneButton`

- `Button _gachaBoxButton`

- `RectTransform _topMenuContainer`

- `UICommonTrackPoint _favorUpTrackPoint`

- `GameObject _favorUpObj`

- `GameObject _noFavorUpObj`

- `TrackPointViewProperty _mileStoneTrackPoint`

- `TrackPointViewProperty m_favorTrackPoint`

- `CommonTopMenu m_topMenu`

- `Boolean m_isInited`


## Methods

- `Void OnBanAct()`

- `Void RefreshTrackPoint()`

- `Void InitData(String)`

- `Void EventOnReplicateClicked()`

- `Void EventOnFavorUpClicked()`

- `Void EventOnDetailClicked()`

- `Void EventOnMileStoneClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0StageEntry : ActivityStageSingleComponent
{
	private Image _buttonImg; // 0x20
	private Image _backImg; // 0x28
	private Image _boxImg; // 0x30
	private Text _timeInfo; // 0x38
	private Text _stateInfo; // 0x40
	private UIActTrackPoint _actTrackPoint; // 0x48
	private Button _mileStoneButton; // 0x50
	private Button _gachaBoxButton; // 0x58
	private RectTransform _topMenuContainer; // 0x60
	private UICommonTrackPoint _favorUpTrackPoint; // 0x68
	private GameObject _favorUpObj; // 0x70
	private GameObject _noFavorUpObj; // 0x78
	private TrackPointViewProperty _mileStoneTrackPoint; // 0x80
	private TrackPointViewProperty m_favorTrackPoint; // 0x88
	private CommonTopMenu m_topMenu; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0_OnBanAct; // 0x0
	private static DelegateBridge __Hotfix0_RefreshTrackPoint; // 0x8
	private static DelegateBridge __Hotfix0_InitData; // 0x10
	private static DelegateBridge __Hotfix0_EventOnReplicateClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnFavorUpClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnDetailClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnMileStoneClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3229868 VA: 0x7595841868
	public Void OnBanAct() { }
	// RVA: 0x3229f30 VA: 0x7595841f30
	public Void RefreshTrackPoint() { }
	// RVA: 0x322a1ec VA: 0x75958421ec
	public Void InitData(String defaultBoxId) { }
	// RVA: 0x322accc VA: 0x7595842ccc
	public Void EventOnReplicateClicked() { }
	// RVA: 0x322ad8c VA: 0x7595842d8c
	public Void EventOnFavorUpClicked() { }
	// RVA: 0x322ae50 VA: 0x7595842e50
	public Void EventOnDetailClicked() { }
	// RVA: 0x322af10 VA: 0x7595842f10
	public Void EventOnMileStoneClicked() { }
	// RVA: 0x322afd0 VA: 0x7595842fd0
	public Void .ctor() { }
}
```
# DailyMissionSimpleView

**Namespace:** `Torappu.UI.Mission`


## Fields

- `DailyMissionRewardTask _reward`

- `Transform _rewardContainer`

- `Transform _rightPanel`

- `DailyMissionConfirmAllTask _confirmAll`

- `RectTransform _scrollView`

- `Single _topPosition`

- `DailyMissionTask _task`

- `Transform _taskContainer`

- `DailyOrWeekly _dataType`

- `MissionAllClear _missionAllClear`

- `DailyMissionConfirmAllTask m_missionConfirmAll`

- `RewardListAdapter m_rewardAdapter`

- `TaskListAdapter m_taskAdapter`

- `AsyncGameObjectLoader m_objLoader`


## Methods

- `Void OnEnable()`

- `Void OnDisable()`

- `Void UpdateTime(Single)`

- `Boolean <>xLuaBaseProxy_IsToBeShown(MissionModel)`

- `Void <>xLuaBaseProxy_RefreshView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class DailyMissionSimpleView : MissionSinglePage, ITimeWatcher
{
	private const Int32 REWARD_PER_FRAME; // 0x0
	private const Int32 TASK_PER_FRAME; // 0x0
	private DailyMissionRewardTask _reward; // 0x30
	private Transform _rewardContainer; // 0x38
	private Transform _rightPanel; // 0x40
	private DailyMissionConfirmAllTask _confirmAll; // 0x48
	private RectTransform _scrollView; // 0x50
	private Single _topPosition; // 0x58
	private DailyMissionTask _task; // 0x60
	private Transform _taskContainer; // 0x68
	private DailyOrWeekly _dataType; // 0x70
	private MissionAllClear _missionAllClear; // 0x78
	private DailyMissionConfirmAllTask m_missionConfirmAll; // 0x80
	private RewardListAdapter m_rewardAdapter; // 0x88
	private TaskListAdapter m_taskAdapter; // 0x90
	private AsyncGameObjectLoader m_objLoader; // 0x98
	private static DelegateBridge __Hotfix0_IsToBeShown; // 0x0
	private static DelegateBridge __Hotfix0__RewardTaskSortingFunc; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0_OnDisable; // 0x18
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x20
	private static DelegateBridge __Hotfix0_RefreshView; // 0x28
	private static DelegateBridge __Hotfix0__ParseRewardListData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x273a854 VA: 0x7594d52854
	public override Boolean IsToBeShown(MissionModel stateBean) { }
	// RVA: 0x273a8e4 VA: 0x7594d528e4
	private static Int32 _RewardTaskSortingFunc(Data lhs, Data rhs) { }
	// RVA: 0x273a998 VA: 0x7594d52998
	private Void OnEnable() { }
	// RVA: 0x273aa08 VA: 0x7594d52a08
	private Void OnDisable() { }
	// RVA: 0x273aa78 VA: 0x7594d52a78
	public Void UpdateTime(Single delta) { }
	// RVA: 0x273ab0c VA: 0x7594d52b0c
	protected override Void RefreshView() { }
	// RVA: 0x273b028 VA: 0x7594d53028
	private IList`1 _ParseRewardListData(out Boolean allClear) { }
	// RVA: 0x273b8ac VA: 0x7594d538ac
	public Void .ctor() { }
	// RVA: 0x273b924 VA: 0x7594d53924
	private Boolean <>xLuaBaseProxy_IsToBeShown(MissionModel P0) { }
	// RVA: 0x273b92c VA: 0x7594d5392c
	private Void <>xLuaBaseProxy_RefreshView() { }
}
```
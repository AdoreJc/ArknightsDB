# BuildingTrainingState

**Namespace:** `Torappu.Building.UI.Train`


## Fields

- `BuildingTrainingStateBean _stateBean`

- `TwoStateToggle _traineeState`

- `TwoStateToggle _trainerState`

- `UIAtlasImage _traineeHeadIcon`

- `BuildingTrainingTrainerStatusView _trainerStatus`

- `GameObject _trainingPart`

- `GameObject _finishTrainingPart`

- `GameObject _emptyPart`

- `TwoStateToggle _panelTraineeToggle`

- `BuildingTrainingTrainerBonusView _bonusView`

- `Boolean m_updateFlag`


## Methods

- `Void _InitData()`

- `Void OnUpgradeFinish()`

- `IEnumerator _TrainingSucessCoroutine(String, String, Int32)`

- `Void OnDestroy()`

- `Void EventOnOpenSelectPage()`

- `Void EventOnTrainer()`

- `Void EventOnLvlUp(Int32)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Train
public class BuildingTrainingState : State
{
	private BuildingTrainingStateBean _stateBean; // 0x50
	private TwoStateToggle _traineeState; // 0x58
	private TwoStateToggle _trainerState; // 0x60
	private UIAtlasImage _traineeHeadIcon; // 0x68
	private BuildingTrainingTrainerStatusView _trainerStatus; // 0x70
	private GameObject _trainingPart; // 0x78
	private GameObject _finishTrainingPart; // 0x80
	private GameObject _emptyPart; // 0x88
	private TwoStateToggle _panelTraineeToggle; // 0x90
	private BuildingTrainingTrainerBonusView _bonusView; // 0x98
	private Boolean m_updateFlag; // 0xa0
	private static DelegateBridge __Hotfix0_OnResume; // 0x0
	private static DelegateBridge __Hotfix0__InitData; // 0x8
	private static DelegateBridge __Hotfix0_OnUpgradeFinish; // 0x10
	private static DelegateBridge __Hotfix0__TrainingSucessCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0_OnExit; // 0x30
	private static DelegateBridge __Hotfix0_EventOnOpenSelectPage; // 0x38
	private static DelegateBridge __Hotfix0_EventOnTrainer; // 0x40
	private static DelegateBridge __Hotfix0_EventOnLvlUp; // 0x48
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3d7a538 VA: 0x7596392538
	protected override Void OnResume() { }
	// RVA: 0x3d7a5ac VA: 0x75963925ac
	private Void _InitData() { }
	// RVA: 0x3d7b0a0 VA: 0x75963930a0
	public Void OnUpgradeFinish() { }
	// RVA: 0x3d7b75c VA: 0x759639375c
	private IEnumerator _TrainingSucessCoroutine(String charId, String skillId, Int32 skillLevel) { }
	// RVA: 0x3d7b874 VA: 0x7596393874
	protected override Void OnEnter() { }
	// RVA: 0x3d7ba24 VA: 0x7596393a24
	private Void OnDestroy() { }
	// RVA: 0x3d7bb80 VA: 0x7596393b80
	protected override Void OnExit() { }
	// RVA: 0x3d7bcdc VA: 0x7596393cdc
	public Void EventOnOpenSelectPage() { }
	// RVA: 0x3d7bdf8 VA: 0x7596393df8
	public Void EventOnTrainer() { }
	// RVA: 0x3d7be68 VA: 0x7596393e68
	public Void EventOnLvlUp(Int32 index) { }
	// RVA: 0x3d7bff0 VA: 0x7596393ff0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d7c058 VA: 0x7596394058
	public Void .ctor() { }
	// RVA: 0x3d7c0c8 VA: 0x75963940c8
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3d7c0d0 VA: 0x75963940d0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d7c0d8 VA: 0x75963940d8
	private Void <>xLuaBaseProxy_OnExit() { }
}
```
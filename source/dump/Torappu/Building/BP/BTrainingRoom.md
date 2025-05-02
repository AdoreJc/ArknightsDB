# BTrainingRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `PiecewiseProgressBar _progressBar`

- `GameObject _isFinish`

- `Text _stateText`

- `Animator _shiningAnimator`

- `Image _startImage`

- `Image _finishImage`

- `PlayerBuildingTraining m_trainingViewModel`

- `LevelUpSnapshot m_trainSnapshot`

- `CountDownTask m_countDown`


## Methods

- `Void _InitData(Object)`

- `Void Update()`

- `Void _UpdateCountDownStatus()`

- `Void <_UpdateCountDownStatus>b__11_0(TickValue)`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnRoomDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BTrainingRoom : BFunctionRoom
{
	private PiecewiseProgressBar _progressBar; // 0x88
	private GameObject _isFinish; // 0x90
	private Text _stateText; // 0x98
	private Animator _shiningAnimator; // 0xa0
	private Image _startImage; // 0xa8
	private Image _finishImage; // 0xb0
	private PlayerBuildingTraining m_trainingViewModel; // 0xb8
	private LevelUpSnapshot m_trainSnapshot; // 0xc0
	private CountDownTask m_countDown; // 0xf0
	private static DelegateBridge __Hotfix0__InitData; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__UpdateCountDownStatus; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnRoomDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3d203e4 VA: 0x75963383e4
	private Void _InitData(Object _object) { }
	// RVA: 0x3d20c44 VA: 0x7596338c44
	private Void Update() { }
	// RVA: 0x3d209f4 VA: 0x75963389f4
	private Void _UpdateCountDownStatus() { }
	// RVA: 0x3d20cc0 VA: 0x7596338cc0
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d20e68 VA: 0x7596338e68
	protected override Void OnRoomDestroy() { }
	// RVA: 0x3d20fe0 VA: 0x7596338fe0
	public Void .ctor() { }
	// RVA: 0x3d2108c VA: 0x759633908c
	private Void <_UpdateCountDownStatus>b__11_0(TickValue tick) { }
	// RVA: 0x3d21100 VA: 0x7596339100
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d21108 VA: 0x7596339108
	private Void <>xLuaBaseProxy_OnRoomDestroy() { }
}
```
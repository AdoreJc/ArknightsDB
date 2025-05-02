# BUpgradePanel

**Namespace:** `Torappu.Building.BP`


## Fields

- `Text _restTimeLabel`

- `PiecewiseProgressBar _progressBar`

- `GameObject _inprogressLabel`

- `GameObject _completeLabel`

- `Single _progressBarWidthFactor`

- `Single _completeBGVerticalOffset`

- `RoomSlotModel m_model`

- `CountDownTask m_cdTask`

- `Boolean m_needUpdateBarScale`

- `GameObject m_completeBGInstance`

- `Action onComplete`

- `RoomSlotModelListener m_modelListener`


## Methods

- `Void add_onComplete(Action)`

- `Void remove_onComplete(Action)`

- `Void Setup(RoomSlotModel)`

- `Void _OnTimeTick(TickValue)`

- `Void _OnTimeout()`

- `Void _ClearRoomModel()`

- `Void _ClearCountDownTask()`

- `Void Update()`

- `Void OnDestroy()`

- `Void UpdateRestTime(RoomSlotModel)`

- `Void _DetachCompleteBG()`

- `Void _AttachCompleteBG()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BUpgradePanel : MonoBehaviour
{
	private Text _restTimeLabel; // 0x18
	private PiecewiseProgressBar _progressBar; // 0x20
	private GameObject _inprogressLabel; // 0x28
	private GameObject _completeLabel; // 0x30
	private Single _progressBarWidthFactor; // 0x38
	private Single _completeBGVerticalOffset; // 0x3c
	private RoomSlotModel m_model; // 0x40
	private CountDownTask m_cdTask; // 0x48
	private Boolean m_needUpdateBarScale; // 0x50
	private GameObject m_completeBGInstance; // 0x58
	private Action onComplete; // 0x60
	private RoomSlotModelListener m_modelListener; // 0x68


	// RVA: 0x3d187cc VA: 0x75963307cc
	public Void add_onComplete(Action value) { }
	// RVA: 0x3d18730 VA: 0x7596330730
	public Void remove_onComplete(Action value) { }
	// RVA: 0x3d18868 VA: 0x7596330868
	public Void Setup(RoomSlotModel room) { }
	// RVA: 0x3d18cf4 VA: 0x7596330cf4
	private Void _OnTimeTick(TickValue tickValue) { }
	// RVA: 0x3d18e58 VA: 0x7596330e58
	private Void _OnTimeout() { }
	// RVA: 0x3d18ad0 VA: 0x7596330ad0
	private Void _ClearRoomModel() { }
	// RVA: 0x3d19180 VA: 0x7596331180
	private Void _ClearCountDownTask() { }
	// RVA: 0x3d191d0 VA: 0x75963311d0
	private Void Update() { }
	// RVA: 0x3d19348 VA: 0x7596331348
	private Void OnDestroy() { }
	// RVA: 0x3d18b48 VA: 0x7596330b48
	public Void UpdateRestTime(RoomSlotModel slotModel) { }
	// RVA: 0x3d18c6c VA: 0x7596330c6c
	private Void _DetachCompleteBG() { }
	// RVA: 0x3d18ef0 VA: 0x7596330ef0
	private Void _AttachCompleteBG() { }
	// RVA: 0x3d19370 VA: 0x7596331370
	public Void .ctor() { }
}
```
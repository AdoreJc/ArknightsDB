# TaskMgr

**Namespace:** ` `


## Fields

- `HGDownloader m_context`

- `Boolean m_isEmpty`

- `Boolean m_isTerminating`

- `Boolean m_isInited`

- `DownloadTask m_pendingTask`

- `Int64 <taskId>k__BackingField`

- `Int64 <lastTaskStatus>k__BackingField`

- `WorkState <currentState>k__BackingField`

- `TaskHandler <activeTask>k__BackingField`


## Properties

- `Boolean isEmpty`

- `Int64 taskId`

- `Int64 lastTaskStatus`

- `WorkState currentState`

- `TaskHandler activeTask`


## Methods

- `Boolean get_isEmpty()`

- `DownloadTask GetPendingTask()`

- `Boolean HasPendingTask()`

- `Int64 get_taskId()`

- `Void set_taskId(Int64)`

- `Int64 get_lastTaskStatus()`

- `Void set_lastTaskStatus(Int64)`

- `WorkState get_currentState()`

- `Void set_currentState(WorkState)`

- `TaskHandler get_activeTask()`

- `Void set_activeTask(TaskHandler)`

- `Void RequestNewTask(DownloadTask)`

- `Void TryStartPendingTask()`

- `Void MarkDownloadFinish()`

- `Void StartDecompress()`

- `Void MarkInited()`

- `Void MarkComplete()`

- `Void MarkPaused(Int64)`

- `Void NotifyDownloadResumed()`

- `Void FinishTask()`

- `Void CancelCurrent()`

- `Void ResumeCurrent()`

- `Void EnableCurrentMobileData()`

- `Boolean UpdateTaskStatus(out)`

- `Void NotifyTaskError(TaskHandler, Int64)`

- `Void TrySyncDownloadProgress()`

- `Void TrySyncDecompressProg()`

- `Void UpdateTaskStatusOnly_MarkTaskEmpty()`

- `Boolean _CheckIfAllowNewTask()`

- `Void _MarkTerminating()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TaskMgr
{
	private HGDownloader m_context; // 0x10
	private Boolean m_isEmpty; // 0x18
	private Boolean m_isTerminating; // 0x19
	private Boolean m_isInited; // 0x1a
	private DownloadTask m_pendingTask; // 0x20
	private Int64 <taskId>k__BackingField; // 0x40
	private Int64 <lastTaskStatus>k__BackingField; // 0x48
	private WorkState <currentState>k__BackingField; // 0x50
	private TaskHandler <activeTask>k__BackingField; // 0x58

	public Boolean isEmpty { get; }
	public Int64 taskId { get; set; }
	public Int64 lastTaskStatus { get; set; }
	public WorkState currentState { get; set; }
	public TaskHandler activeTask { get; set; }

	// RVA: 0x3751dcc VA: 0x7595d69dcc
	public Boolean get_isEmpty() { }
	// RVA: 0x3751dd4 VA: 0x7595d69dd4
	public DownloadTask GetPendingTask() { }
	// RVA: 0x3751324 VA: 0x7595d69324
	public Boolean HasPendingTask() { }
	// RVA: 0x3751de0 VA: 0x7595d69de0
	public Int64 get_taskId() { }
	// RVA: 0x3751de8 VA: 0x7595d69de8
	private Void set_taskId(Int64 value) { }
	// RVA: 0x3751df0 VA: 0x7595d69df0
	public Int64 get_lastTaskStatus() { }
	// RVA: 0x3751df8 VA: 0x7595d69df8
	private Void set_lastTaskStatus(Int64 value) { }
	// RVA: 0x3751e00 VA: 0x7595d69e00
	public WorkState get_currentState() { }
	// RVA: 0x3751e08 VA: 0x7595d69e08
	private Void set_currentState(WorkState value) { }
	// RVA: 0x3751e10 VA: 0x7595d69e10
	public TaskHandler get_activeTask() { }
	// RVA: 0x3751e18 VA: 0x7595d69e18
	private Void set_activeTask(TaskHandler value) { }
	// RVA: 0x3751e20 VA: 0x7595d69e20
	public Void .ctor(HGDownloader context) { }
	// RVA: 0x37509dc VA: 0x7595d689dc
	public Void RequestNewTask(DownloadTask task) { }
	// RVA: 0x375138c VA: 0x7595d6938c
	public Void TryStartPendingTask() { }
	// RVA: 0x375157c VA: 0x7595d6957c
	public Void MarkDownloadFinish() { }
	// RVA: 0x37515b0 VA: 0x7595d695b0
	public Void StartDecompress() { }
	// RVA: 0x37518d8 VA: 0x7595d698d8
	public Void MarkInited() { }
	// RVA: 0x37515c8 VA: 0x7595d695c8
	public Void MarkComplete() { }
	// RVA: 0x3751758 VA: 0x7595d69758
	public Void MarkPaused(Int64 pauseCode) { }
	// RVA: 0x3751798 VA: 0x7595d69798
	public Void NotifyDownloadResumed() { }
	// RVA: 0x3751654 VA: 0x7595d69654
	public Void FinishTask() { }
	// RVA: 0x3750ac4 VA: 0x7595d68ac4
	public Void CancelCurrent() { }
	// RVA: 0x3750f24 VA: 0x7595d68f24
	public Void ResumeCurrent() { }
	// RVA: 0x3750fcc VA: 0x7595d68fcc
	public Void EnableCurrentMobileData() { }
	// RVA: 0x3750c28 VA: 0x7595d68c28
	public Boolean UpdateTaskStatus(out Int64 taskStatus) { }
	// RVA: 0x375150c VA: 0x7595d6950c
	public Void NotifyTaskError(TaskHandler target, Int64 errorCode) { }
	// RVA: 0x37517b0 VA: 0x7595d697b0
	public Void TrySyncDownloadProgress() { }
	// RVA: 0x37517f8 VA: 0x7595d697f8
	public Void TrySyncDecompressProg() { }
	// RVA: 0x3751ef8 VA: 0x7595d69ef8
	private Void UpdateTaskStatusOnly_MarkTaskEmpty() { }
	// RVA: 0x3751ec4 VA: 0x7595d69ec4
	private Boolean _CheckIfAllowNewTask() { }
	// RVA: 0x3751ee4 VA: 0x7595d69ee4
	private Void _MarkTerminating() { }
}
```
# PersistentResRecover

**Namespace:** `Torappu.Resource`


## Fields

- `String m_localResFolder`

- `Status m_status`

- `Object m_lock`


## Properties

- `Boolean isCancelled`


## Methods

- `Boolean get_isCancelled()`

- `Void Cancel()`

- `Void set_progress(KeyValuePair`2)`

- `IEnumerator StartTaskCoroutine(Options)`

- `PersistentResInfo _FuncWorker(List`1, HotUpdateInfo)`

- `Boolean _CheckIfLocalABValid(ABInfo)`

- `Boolean _CheckIfLocalABExists(ABInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource
public class PersistentResRecover : IHotfixable
{
	private String m_localResFolder; // 0x10
	private Status m_status; // 0x18
	private Object m_lock; // 0x30
	private static DelegateBridge __Hotfix0_get_isCancelled; // 0x0
	private static DelegateBridge __Hotfix0_Cancel; // 0x8
	private static DelegateBridge __Hotfix0_get_progress; // 0x10
	private static DelegateBridge __Hotfix0_set_progress; // 0x18
	private static DelegateBridge __Hotfix0_get_currentTask; // 0x20
	private static DelegateBridge __Hotfix0_StartTaskCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__StartNewTask; // 0x30
	private static DelegateBridge __Hotfix0__FuncWorker; // 0x38
	private static DelegateBridge __Hotfix0__CheckIfLocalABValid; // 0x40
	private static DelegateBridge __Hotfix0__CheckIfLocalABExists; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Boolean isCancelled { get; }
	public KeyValuePair`2 progress { get; set; }
	public WaitForAsyncTask`1 currentTask { get; }

	// RVA: 0x3740068 VA: 0x7595d58068
	public Boolean get_isCancelled() { }
	// RVA: 0x3740180 VA: 0x7595d58180
	public Void Cancel() { }
	// RVA: 0x3740288 VA: 0x7595d58288
	public KeyValuePair`2 get_progress() { }
	// RVA: 0x37403c4 VA: 0x7595d583c4
	public Void set_progress(KeyValuePair`2 value) { }
	// RVA: 0x37404ec VA: 0x7595d584ec
	public WaitForAsyncTask`1 get_currentTask() { }
	// RVA: 0x3740554 VA: 0x7595d58554
	public IEnumerator StartTaskCoroutine(Options options) { }
	// RVA: 0x3740658 VA: 0x7595d58658
	private WaitForAsyncTask`1 _StartNewTask(HotUpdateInfo localInfo) { }
	// RVA: 0x37408c0 VA: 0x7595d588c0
	private PersistentResInfo _FuncWorker(List`1 abInfoList, HotUpdateInfo localInfo) { }
	// RVA: 0x3740eb0 VA: 0x7595d58eb0
	private Boolean _CheckIfLocalABValid(ABInfo abInfo) { }
	// RVA: 0x3740db8 VA: 0x7595d58db8
	private Boolean _CheckIfLocalABExists(ABInfo abInfo) { }
	// RVA: 0x374106c VA: 0x7595d5906c
	public Void .ctor() { }
}
```
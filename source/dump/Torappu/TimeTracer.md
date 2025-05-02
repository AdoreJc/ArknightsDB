# TimeTracer

**Namespace:** `Torappu`


## Fields

- `Single _timeScale`

- `Int32 m_groupIdTail`

- `Int64 m_selfFrameCnt`

- `Int32 m_unityFrameCnt`


## Methods

- `Void Update()`

- `Int32 _RegisterGroup()`

- `Void _UnregisterGroup(Int32)`

- `Void _SetGroupActive(Int32, Boolean)`

- `Void _WatchOnGroup(ITimeWatcher, Int32)`

- `Void _UnWatchOnGroup(ITimeWatcher, Int32)`

- `Boolean _AddInvokeNextFrame(Behaviour, Action)`

- `Void _UpdateInvokeNextFrame()`

- `CallbackWithActiveMono _GetActionWithActiveMono(Behaviour, Action)`

- `Void _RecycleActionWithActiveMono(CallbackWithActiveMono)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TimeTracer : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private const Int32 DEFAULT_GROUP; // 0x0
	public const Int32 INVALID_GROUP; // 0x0
	private Single _timeScale; // 0x18
	private ListDict`2 m_timeWatcherGroup; // 0x20
	private Int32 m_groupIdTail; // 0x28
	private List`1 m_watchersBuffer; // 0x30
	private List`1 m_timeTasks; // 0x38
	private Int64 m_selfFrameCnt; // 0x40
	private Int32 m_unityFrameCnt; // 0x48
	private Queue`1 m_callbackPool; // 0x50
	private List`1 m_invokeNextFrame; // 0x58
	private static DelegateBridge __Hotfix0_Watch; // 0x0
	private static DelegateBridge __Hotfix0_UnWatch; // 0x8
	private static DelegateBridge __Hotfix0_RegisterGroup; // 0x10
	private static DelegateBridge __Hotfix0_UnregisterGroup; // 0x18
	private static DelegateBridge __Hotfix0_PauseGroup; // 0x20
	private static DelegateBridge __Hotfix0_ResumeGroup; // 0x28
	private static DelegateBridge __Hotfix0_StartTimeTask; // 0x30
	private static DelegateBridge __Hotfix0_IsValidGroup; // 0x38
	private static DelegateBridge __Hotfix0_InvokeNextFrame; // 0x40
	private static DelegateBridge __Hotfix0_OnInit; // 0x48
	private static DelegateBridge __Hotfix0_Update; // 0x50
	private static DelegateBridge __Hotfix0__RegisterGroup; // 0x58
	private static DelegateBridge __Hotfix0__UnregisterGroup; // 0x60
	private static DelegateBridge __Hotfix0__SetGroupActive; // 0x68
	private static DelegateBridge __Hotfix0__WatchOnGroup; // 0x70
	private static DelegateBridge __Hotfix0__UnWatchOnGroup; // 0x78
	private static DelegateBridge __Hotfix0__AddInvokeNextFrame; // 0x80
	private static DelegateBridge __Hotfix0__UpdateInvokeNextFrame; // 0x88
	private static DelegateBridge __Hotfix0__GetActionWithActiveMono; // 0x90
	private static DelegateBridge __Hotfix0__RecycleActionWithActiveMono; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x3108604 VA: 0x7595720604
	public static Void Watch(ITimeWatcher watcher, Int32 groupId) { }
	// RVA: 0x3108914 VA: 0x7595720914
	public static Void UnWatch(ITimeWatcher watcher, Int32 groupId) { }
	// RVA: 0x3108af8 VA: 0x7595720af8
	public static Int32 RegisterGroup() { }
	// RVA: 0x3108ca0 VA: 0x7595720ca0
	public static Void UnregisterGroup(Int32 groupId) { }
	// RVA: 0x3108e20 VA: 0x7595720e20
	public static Void PauseGroup(Int32 groupId) { }
	// RVA: 0x3108fcc VA: 0x7595720fcc
	public static Void ResumeGroup(Int32 groupId) { }
	// RVA: 0x31090b0 VA: 0x75957210b0
	public static Boolean StartTimeTask(Action task, Single delay) { }
	// RVA: 0x310924c VA: 0x759572124c
	public static Boolean IsValidGroup(Int32 groupId) { }
	// RVA: 0x31092b8 VA: 0x75957212b8
	public static Boolean InvokeNextFrame(Behaviour mono, Action action) { }
	// RVA: 0x310955c VA: 0x759572155c
	protected override Void OnInit() { }
	// RVA: 0x31096c8 VA: 0x75957216c8
	private Void Update() { }
	// RVA: 0x3108bd0 VA: 0x7595720bd0
	private Int32 _RegisterGroup() { }
	// RVA: 0x3108d80 VA: 0x7595720d80
	private Void _UnregisterGroup(Int32 groupId) { }
	// RVA: 0x3108f04 VA: 0x7595720f04
	private Void _SetGroupActive(Int32 groupId, Boolean isActive) { }
	// RVA: 0x3108700 VA: 0x7595720700
	private Void _WatchOnGroup(ITimeWatcher watcher, Int32 groupId) { }
	// RVA: 0x3108a10 VA: 0x7595720a10
	private Void _UnWatchOnGroup(ITimeWatcher watcher, Int32 groupId) { }
	// RVA: 0x31093d8 VA: 0x75957213d8
	private Boolean _AddInvokeNextFrame(Behaviour mono, Action action) { }
	// RVA: 0x3109c7c VA: 0x7595721c7c
	private Void _UpdateInvokeNextFrame() { }
	// RVA: 0x310a2d8 VA: 0x75957222d8
	private CallbackWithActiveMono _GetActionWithActiveMono(Behaviour mono, Action action) { }
	// RVA: 0x310a4a0 VA: 0x75957224a0
	private Void _RecycleActionWithActiveMono(CallbackWithActiveMono inst) { }
	// RVA: 0x310a57c VA: 0x759572257c
	public Void .ctor() { }
}
```
# StateMachine

**Namespace:** `Torappu`


## Fields

- `Boolean m_switchLocked`

- `Int32 m_defaultStateId`

- `IBlackboard m_blackboard`

- `Int32 <currentStateId>k__BackingField`

- `IStateNode <currentState>k__BackingField`


## Properties

- `Int32 currentStateId`

- `IStateNode currentState`

- `Boolean isRunning`

- `Boolean isLocked`


## Methods

- `Int32 get_currentStateId()`

- `Void set_currentStateId(Int32)`

- `IStateNode get_currentState()`

- `Void set_currentState(IStateNode)`

- `Boolean get_isRunning()`

- `Boolean get_isLocked()`

- `Void RegisterState(Int32, IStateNode, Boolean)`

- `Void Start(Int32)`

- `Void Stop()`

- `Void Tick(FP)`

- `Void SwitchState(Int32)`

- `Void SetDefaultState(Int32)`

- `Int32 GetDefaultState()`

- `IStateNode GetStateNode(Int32)`

- `Void _SwitchStateInternal(Int32, Boolean)`

- `Void _FinishSwitchState()`

- `Boolean _CheckValidState(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StateMachine
{
	public const Int32 DEFAULT_STATE; // 0x0
	public const Int32 TERMINAL_STATE; // 0x0
	public Action`1 onStarted; // 0x10
	public Action`2 onStateChanged; // 0x18
	public Action`1 onTerminated; // 0x20
	private Boolean m_switchLocked; // 0x28
	private Int32 m_defaultStateId; // 0x2c
	private Dictionary`2 m_states; // 0x30
	private Queue`1 m_pendingQueue; // 0x38
	protected IBlackboard m_blackboard; // 0x40
	private Int32 <currentStateId>k__BackingField; // 0x48
	private IStateNode <currentState>k__BackingField; // 0x50

	public Int32 currentStateId { get; set; }
	public IStateNode currentState { get; set; }
	public virtual String stateDebugString { get; }
	protected virtual Boolean manageBlackboard { get; }
	public Boolean isRunning { get; }
	public Boolean isLocked { get; }

	// RVA: 0x3500784 VA: 0x7595b18784
	public Int32 get_currentStateId() { }
	// RVA: 0x350078c VA: 0x7595b1878c
	private Void set_currentStateId(Int32 value) { }
	// RVA: 0x3500794 VA: 0x7595b18794
	public IStateNode get_currentState() { }
	// RVA: 0x350079c VA: 0x7595b1879c
	private Void set_currentState(IStateNode value) { }
	// RVA: 0x35007a4 VA: 0x7595b187a4
	public virtual String get_stateDebugString() { }
	// RVA: 0x35007c4 VA: 0x7595b187c4
	protected virtual Boolean get_manageBlackboard() { }
	// RVA: 0x35007cc VA: 0x7595b187cc
	public Boolean get_isRunning() { }
	// RVA: 0x3500844 VA: 0x7595b18844
	public Boolean get_isLocked() { }
	// RVA: 0x350084c VA: 0x7595b1884c
	public Void RegisterState(Int32 stateId, IStateNode state, Boolean asDefault) { }
	// RVA: 0x35008d4 VA: 0x7595b188d4
	public Void Start(Int32 stateId) { }
	// RVA: 0x3500db4 VA: 0x7595b18db4
	public Void Stop() { }
	// RVA: 0x3500dc0 VA: 0x7595b18dc0
	public Void Tick(FP deltaTime) { }
	// RVA: 0x3500e7c VA: 0x7595b18e7c
	public Void SwitchState(Int32 newStateId) { }
	// RVA: 0x3500e84 VA: 0x7595b18e84
	public Void SetDefaultState(Int32 stateId) { }
	// RVA: 0x3500eac VA: 0x7595b18eac
	public Int32 GetDefaultState() { }
	// RVA: 0x3500eb4 VA: 0x7595b18eb4
	public IStateNode GetStateNode(Int32 stateId) { }
	// RVA: 0x3500f2c VA: 0x7595b18f2c
	protected Void .ctor(IBlackboard blackboard) { }
	// RVA: 0x3501028 VA: 0x7595b19028
	protected virtual Void OnStateChanged(Int32 newStateId, Int32 oldStateId) { }
	// RVA: 0x3501044 VA: 0x7595b19044
	protected virtual Void OnStart() { }
	// RVA: 0x350111c VA: 0x7595b1911c
	protected virtual Void OnTick(FP deltaTime) { }
	// RVA: 0x35011e4 VA: 0x7595b191e4
	protected virtual Void OnTerminate(Int32 lastStateId) { }
	// RVA: 0x3500948 VA: 0x7595b18948
	private Void _SwitchStateInternal(Int32 newStateId, Boolean force) { }
	// RVA: 0x35012ec VA: 0x7595b192ec
	private Void _FinishSwitchState() { }
	// RVA: 0x35007d4 VA: 0x7595b187d4
	private Boolean _CheckValidState(Int32 state) { }
}
```
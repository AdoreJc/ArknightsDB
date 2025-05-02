# ManualResetEventSlim

**Namespace:** `System.Threading`


## Fields

- `Object m_lock`

- `ManualResetEvent m_eventObj`

- `Int32 m_combinedState`


## Properties

- `WaitHandle WaitHandle`

- `Boolean IsSet`

- `Int32 SpinCount`

- `Int32 Waiters`


## Methods

- `WaitHandle get_WaitHandle()`

- `Boolean get_IsSet()`

- `Void set_IsSet(Boolean)`

- `Int32 get_SpinCount()`

- `Void set_SpinCount(Int32)`

- `Int32 get_Waiters()`

- `Void set_Waiters(Int32)`

- `Void Initialize(Boolean, Int32)`

- `Void EnsureLockObjectCreated()`

- `Boolean LazyInitializeEvent()`

- `Void Set()`

- `Void Set(Boolean)`

- `Boolean Wait(Int32, CancellationToken)`

- `Void Dispose()`

- `Void ThrowIfDisposed()`

- `Void UpdateStateAtomically(Int32, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
public class ManualResetEventSlim : IDisposable
{
	private const Int32 DEFAULT_SPIN_SP; // 0x0
	private Object m_lock; // 0x10
	private ManualResetEvent m_eventObj; // 0x18
	private Int32 m_combinedState; // 0x20
	private const Int32 SignalledState_BitMask; // 0x0
	private const Int32 SignalledState_ShiftCount; // 0x0
	private const Int32 Dispose_BitMask; // 0x0
	private const Int32 SpinCountState_BitMask; // 0x0
	private const Int32 SpinCountState_ShiftCount; // 0x0
	private const Int32 SpinCountState_MaxValue; // 0x0
	private const Int32 NumWaitersState_BitMask; // 0x0
	private const Int32 NumWaitersState_ShiftCount; // 0x0
	private const Int32 NumWaitersState_MaxValue; // 0x0
	private static Action`1 s_cancellationTokenCallback; // 0x0

	public WaitHandle WaitHandle { get; }
	public Boolean IsSet { get; set; }
	public Int32 SpinCount { get; set; }
	private Int32 Waiters { get; set; }

	// RVA: 0x61195ac VA: 0x75987315ac
	public WaitHandle get_WaitHandle() { }
	// RVA: 0x61197b4 VA: 0x75987317b4
	public Boolean get_IsSet() { }
	// RVA: 0x6119818 VA: 0x7598731818
	private Void set_IsSet(Boolean value) { }
	// RVA: 0x6119910 VA: 0x7598731910
	public Int32 get_SpinCount() { }
	// RVA: 0x6119978 VA: 0x7598731978
	private Void set_SpinCount(Int32 value) { }
	// RVA: 0x61199ac VA: 0x75987319ac
	private Int32 get_Waiters() { }
	// RVA: 0x6119a08 VA: 0x7598731a08
	private Void set_Waiters(Int32 value) { }
	// RVA: 0x6119a9c VA: 0x7598731a9c
	public Void .ctor(Boolean initialState) { }
	// RVA: 0x6119bc8 VA: 0x7598731bc8
	public Void .ctor(Boolean initialState, Int32 spinCount) { }
	// RVA: 0x6119b18 VA: 0x7598731b18
	private Void Initialize(Boolean initialState, Int32 spinCount) { }
	// RVA: 0x6119ce8 VA: 0x7598731ce8
	private Void EnsureLockObjectCreated() { }
	// RVA: 0x611964c VA: 0x759873164c
	private Boolean LazyInitializeEvent() { }
	// RVA: 0x6119df4 VA: 0x7598731df4
	public Void Set() { }
	// RVA: 0x6119dfc VA: 0x7598731dfc
	private Void Set(Boolean duringCancellation) { }
	// RVA: 0x611a000 VA: 0x7598732000
	public Boolean Wait(Int32 millisecondsTimeout, CancellationToken cancellationToken) { }
	// RVA: 0x611a648 VA: 0x7598732648
	public Void Dispose() { }
	// RVA: 0x611a6b4 VA: 0x75987326b4
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x61195e8 VA: 0x75987315e8
	private Void ThrowIfDisposed() { }
	// RVA: 0x611a7b4 VA: 0x75987327b4
	private static Void CancellationTokenCallback(Object obj) { }
	// RVA: 0x6119838 VA: 0x7598731838
	private Void UpdateStateAtomically(Int32 newBits, Int32 updateBitsMask) { }
	// RVA: 0x611996c VA: 0x759873196c
	private static Int32 ExtractStatePortionAndShiftRight(Int32 state, Int32 mask, Int32 rightBitShiftCount) { }
	// RVA: 0x6119810 VA: 0x7598731810
	private static Int32 ExtractStatePortion(Int32 state, Int32 mask) { }
	// RVA: 0x611a92c VA: 0x759873292c
	private static Void .cctor() { }
}
```
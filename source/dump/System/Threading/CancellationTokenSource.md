# CancellationTokenSource

**Namespace:** `System.Threading`


## Fields

- `ManualResetEvent _kernelEvent`

- `Int32 _state`

- `Int32 _threadIDExecutingCallbacks`

- `Boolean _disposed`

- `CancellationCallbackInfo _executingCallback`

- `Timer _timer`


## Properties

- `Boolean IsCancellationRequested`

- `CancellationToken Token`


## Methods

- `Boolean get_IsCancellationRequested()`

- `CancellationToken get_Token()`

- `Void Cancel()`

- `Void Cancel(Boolean)`

- `Void CancelAfter(Int32)`

- `Void Dispose()`

- `Void NotifyCancellation(Boolean)`

- `Void ExecuteCallbackHandlers(Boolean)`

- `Void CancellationCallbackCoreWork_OnSyncContext(Object)`

- `Void CancellationCallbackCoreWork(CancellationCallbackCoreWorkArguments)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
public class CancellationTokenSource : IDisposable
{
	internal static readonly CancellationTokenSource s_canceledSource; // 0x0
	internal static readonly CancellationTokenSource s_neverCanceledSource; // 0x8
	private static readonly Int32 s_nLists; // 0x10
	private ManualResetEvent _kernelEvent; // 0x10
	private SparselyPopulatedArray`1[] _registeredCallbacksLists; // 0x18
	private const Int32 CannotBeCanceled; // 0x0
	private const Int32 NotCanceledState; // 0x0
	private const Int32 NotifyingState; // 0x0
	private const Int32 NotifyingCompleteState; // 0x0
	private Int32 _state; // 0x20
	private Int32 _threadIDExecutingCallbacks; // 0x24
	private Boolean _disposed; // 0x28
	private CancellationCallbackInfo _executingCallback; // 0x30
	private Timer _timer; // 0x38
	private static readonly TimerCallback s_timerCallback; // 0x18

	public Boolean IsCancellationRequested { get; }
	internal Boolean IsCancellationCompleted { get; }
	internal Boolean IsDisposed { get; }
	internal Int32 ThreadIDExecutingCallbacks { get; set; }
	public CancellationToken Token { get; }
	internal CancellationCallbackInfo ExecutingCallback { get; }

	// RVA: 0x6118a0c VA: 0x7598730a0c
	public Boolean get_IsCancellationRequested() { }
	// RVA: 0x611aefc VA: 0x7598732efc
	internal Boolean get_IsCancellationCompleted() { }
	// RVA: 0x611b158 VA: 0x7598733158
	internal Boolean get_IsDisposed() { }
	// RVA: 0x611af18 VA: 0x7598732f18
	internal Int32 get_ThreadIDExecutingCallbacks() { }
	// RVA: 0x611b160 VA: 0x7598733160
	internal Void set_ThreadIDExecutingCallbacks(Int32 value) { }
	// RVA: 0x611b184 VA: 0x7598733184
	public CancellationToken get_Token() { }
	// RVA: 0x611b208 VA: 0x7598733208
	internal CancellationCallbackInfo get_ExecutingCallback() { }
	// RVA: 0x611b220 VA: 0x7598733220
	public Void .ctor() { }
	// RVA: 0x611b254 VA: 0x7598733254
	public Void Cancel() { }
	// RVA: 0x611b270 VA: 0x7598733270
	public Void Cancel(Boolean throwOnFirstException) { }
	// RVA: 0x611b348 VA: 0x7598733348
	public Void CancelAfter(Int32 millisecondsDelay) { }
	// RVA: 0x611b534 VA: 0x7598733534
	private static Void TimerCallbackLogic(Object obj) { }
	// RVA: 0x611b64c VA: 0x759873364c
	public Void Dispose() { }
	// RVA: 0x611b6b8 VA: 0x75987336b8
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x611b1b4 VA: 0x75987331b4
	internal Void ThrowIfDisposed() { }
	// RVA: 0x611b754 VA: 0x7598733754
	private static Void ThrowObjectDisposedException() { }
	// RVA: 0x6118e30 VA: 0x7598730e30
	internal CancellationTokenRegistration InternalRegister(Action`1 callback, Object stateForCallback, SynchronizationContext targetSyncContext, ExecutionContext executionContext) { }
	// RVA: 0x611b298 VA: 0x7598733298
	private Void NotifyCancellation(Boolean throwOnFirstException) { }
	// RVA: 0x611b848 VA: 0x7598733848
	private Void ExecuteCallbackHandlers(Boolean throwOnFirstException) { }
	// RVA: 0x611be24 VA: 0x7598733e24
	private Void CancellationCallbackCoreWork_OnSyncContext(Object obj) { }
	// RVA: 0x611bd68 VA: 0x7598733d68
	private Void CancellationCallbackCoreWork(CancellationCallbackCoreWorkArguments args) { }
	// RVA: 0x611bfa8 VA: 0x7598733fa8
	public static CancellationTokenSource CreateLinkedTokenSource(CancellationToken token1, CancellationToken token2) { }
	// RVA: 0x611c304 VA: 0x7598734304
	internal static CancellationTokenSource CreateLinkedTokenSource(CancellationToken token) { }
	// RVA: 0x611af30 VA: 0x7598732f30
	internal Void WaitForCallbackToComplete(CancellationCallbackInfo callbackInfo) { }
	// RVA: 0x611c3dc VA: 0x75987343dc
	private static Void .cctor() { }
}
```
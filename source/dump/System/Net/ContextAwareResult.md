# ContextAwareResult

**Namespace:** `System.Net`


## Fields

- `ExecutionContext _context`

- `Object _lock`

- `StateFlags _flags`


## Methods

- `Void SafeCaptureIdentity()`

- `Void CleanupInternal()`

- `Boolean CaptureOrComplete(ref, Boolean)`

- `Void CompleteCallback()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class ContextAwareResult : LazyAsyncResult
{
	private ExecutionContext _context; // 0x40
	private Object _lock; // 0x48
	private StateFlags _flags; // 0x50


	// RVA: 0x6413854 VA: 0x7598a2b854
	private Void SafeCaptureIdentity() { }
	// RVA: 0x6413858 VA: 0x7598a2b858
	private Void CleanupInternal() { }
	// RVA: 0x641385c VA: 0x7598a2b85c
	internal Void .ctor(Object myObject, Object myState, AsyncCallback myCallBack) { }
	// RVA: 0x6413864 VA: 0x7598a2b864
	internal Void .ctor(Boolean captureIdentity, Boolean forceCaptureContext, Object myObject, Object myState, AsyncCallback myCallBack) { }
	// RVA: 0x64138b4 VA: 0x7598a2b8b4
	internal Void .ctor(Boolean captureIdentity, Boolean forceCaptureContext, Boolean threadSafeContextCopy, Object myObject, Object myState, AsyncCallback myCallBack) { }
	// RVA: 0x641392c VA: 0x7598a2b92c
	internal Object StartPostingAsyncOp() { }
	// RVA: 0x6413934 VA: 0x7598a2b934
	internal Object StartPostingAsyncOp(Boolean lockCapture) { }
	// RVA: 0x6413b0c VA: 0x7598a2bb0c
	internal Boolean FinishPostingAsyncOp() { }
	// RVA: 0x6413f64 VA: 0x7598a2bf64
	protected override Void Cleanup() { }
	// RVA: 0x6413b50 VA: 0x7598a2bb50
	private Boolean CaptureOrComplete(ref ExecutionContext cachedContext, Boolean returnContext) { }
	// RVA: 0x6414228 VA: 0x7598a2c228
	protected override Void Complete(IntPtr userToken) { }
	// RVA: 0x6414538 VA: 0x7598a2c538
	private Void CompleteCallback() { }
}
```
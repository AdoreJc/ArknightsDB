# SynchronizationContext

**Namespace:** `System.Threading`


## Fields

- `SynchronizationContextProperties _props`


## Methods

- `Boolean IsWaitNotificationRequired()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
public class SynchronizationContext
{
	private SynchronizationContextProperties _props; // 0x10
	private static Type s_cachedPreparedType1; // 0x0
	private static Type s_cachedPreparedType2; // 0x8
	private static Type s_cachedPreparedType3; // 0x10
	private static Type s_cachedPreparedType4; // 0x18
	private static Type s_cachedPreparedType5; // 0x20

	public static SynchronizationContext Current { get; }
	internal static SynchronizationContext CurrentNoFlow { get; }
	internal static SynchronizationContext CurrentExplicit { get; }

	// RVA: 0x6121990 VA: 0x7598739990
	public Void .ctor() { }
	// RVA: 0x6121998 VA: 0x7598739998
	public Boolean IsWaitNotificationRequired() { }
	// RVA: 0x61219a4 VA: 0x75987399a4
	public virtual Void Send(SendOrPostCallback d, Object state) { }
	// RVA: 0x61219cc VA: 0x75987399cc
	public virtual Void Post(SendOrPostCallback d, Object state) { }
	// RVA: 0x6121a5c VA: 0x7598739a5c
	public virtual Void OperationStarted() { }
	// RVA: 0x6121a60 VA: 0x7598739a60
	public virtual Void OperationCompleted() { }
	// RVA: 0x6121a64 VA: 0x7598739a64
	public virtual Int32 Wait(IntPtr[] waitHandles, Boolean waitAll, Int32 millisecondsTimeout) { }
	// RVA: 0x6121ac8 VA: 0x7598739ac8
	protected static Int32 WaitHelper(IntPtr[] waitHandles, Boolean waitAll, Int32 millisecondsTimeout) { }
	// RVA: 0x6121b54 VA: 0x7598739b54
	public static Void SetSynchronizationContext(SynchronizationContext syncContext) { }
	// RVA: 0x6118da4 VA: 0x7598730da4
	public static SynchronizationContext get_Current() { }
	// RVA: 0x6121be8 VA: 0x7598739be8
	internal static SynchronizationContext get_CurrentNoFlow() { }
	// RVA: 0x6121b9c VA: 0x7598739b9c
	private static SynchronizationContext GetThreadLocalContext() { }
	// RVA: 0x6121d88 VA: 0x7598739d88
	public virtual SynchronizationContext CreateCopy() { }
	// RVA: 0x6121de4 VA: 0x7598739de4
	internal static SynchronizationContext get_CurrentExplicit() { }
}
```
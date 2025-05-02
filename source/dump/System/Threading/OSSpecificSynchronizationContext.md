# OSSpecificSynchronizationContext

**Namespace:** `System.Threading`


## Fields

- `Object m_OSSynchronizationContext`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
internal class OSSpecificSynchronizationContext : SynchronizationContext
{
	private Object m_OSSynchronizationContext; // 0x18
	private static readonly ConditionalWeakTable`2 s_ContextCache; // 0x0


	// RVA: 0x6121f50 VA: 0x7598739f50
	private Void .ctor(Object osContext) { }
	// RVA: 0x6121c24 VA: 0x7598739c24
	public static OSSpecificSynchronizationContext Get() { }
	// RVA: 0x6121f84 VA: 0x7598739f84
	public override SynchronizationContext CreateCopy() { }
	// RVA: 0x6121ff8 VA: 0x7598739ff8
	public override Void Send(SendOrPostCallback d, Object state) { }
	// RVA: 0x6122038 VA: 0x759873a038
	public override Void Post(SendOrPostCallback d, Object state) { }
	// RVA: 0x6121de8 VA: 0x7598739de8
	private static Void InvocationEntry(IntPtr arg) { }
	// RVA: 0x6121f80 VA: 0x7598739f80
	private static Object GetOSContext() { }
	// RVA: 0x61222a8 VA: 0x759873a2a8
	private static Void PostInternal(Object osSynchronizationContext, IntPtr callback, IntPtr arg) { }
	// RVA: 0x61222d4 VA: 0x759873a2d4
	private static Void .cctor() { }
}
```
# TimerQueue

**Namespace:** ` `


## Fields

- `IntPtr m_ThisHandle`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class TimerQueue : Queue
{
	private IntPtr m_ThisHandle; // 0x18
	private readonly TimerNode m_Timers; // 0x20


	// RVA: 0x6433bfc VA: 0x7598a4bbfc
	internal Void .ctor(Int32 durationMilliseconds) { }
	// RVA: 0x643546c VA: 0x7598a4d46c
	internal override Timer CreateTimer(Callback callback, Object context) { }
	// RVA: 0x6434f30 VA: 0x7598a4cf30
	internal Boolean Fire(out Int32 nextExpiration) { }
}
```
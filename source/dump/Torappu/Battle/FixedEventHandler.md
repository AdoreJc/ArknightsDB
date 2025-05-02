# FixedEventHandler

**Namespace:** `Torappu.Battle`


## Fields

- `CoroutineId m_coroutine`


## Methods

- `Void Clear()`

- `Void QueueEvent(T, UInt32, UInt32, Action`1)`

- `Void _DealPendingActions()`

- `Int32 _CompareEvent(PendingEvent, PendingEvent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FixedEventHandler`1
{
	private List`1 m_pendingActions; // 0x0
	private CoroutineId m_coroutine; // 0x0


	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Void QueueEvent(T target, UInt32 secondaryCompareUid, UInt32 thirdCompareWeight, Action`1 callback) { }
	// RVA: 0x VA: 0x0
	private Void _DealPendingActions() { }
	// RVA: 0x VA: 0x0
	private Int32 _CompareEvent(PendingEvent lhs, PendingEvent rhs) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```
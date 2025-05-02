# TimerNode

**Namespace:** ` `


## Fields

- `TimerState m_TimerState`

- `Callback m_Callback`

- `Object m_Context`

- `Object m_QueueLock`

- `TimerNode next`

- `TimerNode prev`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class TimerNode : Timer
{
	private TimerState m_TimerState; // 0x18
	private Callback m_Callback; // 0x20
	private Object m_Context; // 0x28
	private Object m_QueueLock; // 0x30
	private TimerNode next; // 0x38
	private TimerNode prev; // 0x40

	internal override Boolean HasExpired { get; }
	internal TimerNode Next { get; set; }
	internal TimerNode Prev { get; set; }

	// RVA: 0x64356c4 VA: 0x7598a4d6c4
	internal Void .ctor(Callback callback, Object context, Int32 durationMilliseconds, Object queueLock) { }
	// RVA: 0x643543c VA: 0x7598a4d43c
	internal Void .ctor() { }
	// RVA: 0x6435aa4 VA: 0x7598a4daa4
	internal override Boolean get_HasExpired() { }
	// RVA: 0x6435ab4 VA: 0x7598a4dab4
	internal TimerNode get_Next() { }
	// RVA: 0x6435abc VA: 0x7598a4dabc
	internal Void set_Next(TimerNode value) { }
	// RVA: 0x6435ac4 VA: 0x7598a4dac4
	internal TimerNode get_Prev() { }
	// RVA: 0x6435acc VA: 0x7598a4dacc
	internal Void set_Prev(TimerNode value) { }
	// RVA: 0x6435ad4 VA: 0x7598a4dad4
	internal override Boolean Cancel() { }
	// RVA: 0x6435740 VA: 0x7598a4d740
	internal Boolean Fire() { }
}
```
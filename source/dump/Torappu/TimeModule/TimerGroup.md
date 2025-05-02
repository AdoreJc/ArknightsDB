# TimerGroup

**Namespace:** `Torappu.TimeModule`


## Fields

- `Single m_internalTime`

- `Int64 m_lastFrameCount`


## Properties

- `Boolean thisFrameTicked`


## Methods

- `Boolean get_thisFrameTicked()`

- `Int32 AddTimer(Action, Action, Single, Int32)`

- `Void ClearAll()`

- `Void ClearTimer(Int32)`

- `Timer FindTimer(Int32)`

- `Single GetLeftTime(Timer)`

- `Void Tick(Single)`

- `Int32 _AddTimerInternal(Action, Action, Single, Int32)`

- `Void _ClearTimerInternal(Timer)`

- `Timer _CreateTimer()`

- `Void _RemoveTimer(Timer)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.TimeModule
public class TimerGroup
{
	private readonly Dictionary`2 m_timers; // 0x10
	private readonly Heap`1 m_activeTimers; // 0x18
	private readonly IntHashSet m_pendingToActiveTimerIds; // 0x20
	private readonly LocalGenericPool`1 m_timerPool; // 0x28
	private Single m_internalTime; // 0x30
	private Int64 m_lastFrameCount; // 0x38

	public Boolean thisFrameTicked { get; }

	// RVA: 0x678e728 VA: 0x7598da6728
	public Boolean get_thisFrameTicked() { }
	// RVA: 0x678e78c VA: 0x7598da678c
	public Int32 AddTimer(Action timerMethod, Action callbackOnRemoved, Single interval, Int32 loopCnt) { }
	// RVA: 0x678e89c VA: 0x7598da689c
	public Void ClearAll() { }
	// RVA: 0x678e934 VA: 0x7598da6934
	public Void ClearTimer(Int32 timerId) { }
	// RVA: 0x678e95c VA: 0x7598da695c
	public Timer FindTimer(Int32 timerId) { }
	// RVA: 0x678ea94 VA: 0x7598da6a94
	public Single GetLeftTime(Timer timer) { }
	// RVA: 0x678eb1c VA: 0x7598da6b1c
	public Void Tick(Single deltaTime) { }
	// RVA: 0x678e790 VA: 0x7598da6790
	private Int32 _AddTimerInternal(Action timerMethod, Action callbackOnRemoved, Single interval, Int32 loopCnt) { }
	// RVA: 0x678e9d4 VA: 0x7598da69d4
	private Void _ClearTimerInternal(Timer timer) { }
	// RVA: 0x678f594 VA: 0x7598da7594
	private Timer _CreateTimer() { }
	// RVA: 0x678f4ec VA: 0x7598da74ec
	private Void _RemoveTimer(Timer timer) { }
	// RVA: 0x678f684 VA: 0x7598da7684
	public Void .ctor() { }
}
```
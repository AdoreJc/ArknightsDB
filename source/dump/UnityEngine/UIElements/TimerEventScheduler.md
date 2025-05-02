# TimerEventScheduler

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Boolean m_TransactionMode`

- `Int32 m_LastUpdatedIndex`


## Methods

- `Void Schedule(ScheduledItem)`

- `Boolean RemovedScheduledItemAt(Int32)`

- `Void Unschedule(ScheduledItem)`

- `Boolean PrivateUnSchedule(ScheduledItem)`

- `Void UpdateScheduledEvents()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class TimerEventScheduler : IScheduler
{
	private readonly List`1 m_ScheduledItems; // 0x10
	private Boolean m_TransactionMode; // 0x18
	private readonly List`1 m_ScheduleTransactions; // 0x20
	private readonly HashSet`1 m_UnscheduleTransactions; // 0x28
	internal Boolean disableThrottling; // 0x30
	private Int32 m_LastUpdatedIndex; // 0x34


	// RVA: 0x69435dc VA: 0x7598f5b5dc
	public Void Schedule(ScheduledItem item) { }
	// RVA: 0x69437bc VA: 0x7598f5b7bc
	private Boolean RemovedScheduledItemAt(Int32 index) { }
	// RVA: 0x694383c VA: 0x7598f5b83c
	public Void Unschedule(ScheduledItem item) { }
	// RVA: 0x69439e0 VA: 0x7598f5b9e0
	private Boolean PrivateUnSchedule(ScheduledItem sItem) { }
	// RVA: 0x6943a80 VA: 0x7598f5ba80
	public Void UpdateScheduledEvents() { }
	// RVA: 0x6943d90 VA: 0x7598f5bd90
	public Void .ctor() { }
}
```
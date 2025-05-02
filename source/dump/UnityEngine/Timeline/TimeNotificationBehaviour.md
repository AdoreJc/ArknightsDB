# TimeNotificationBehaviour

**Namespace:** `UnityEngine.Timeline`


## Fields

- `Double m_PreviousTime`

- `Boolean m_NeedSortNotifications`

- `Playable m_TimeSource`


## Properties

- `Playable timeSource`


## Methods

- `Void set_timeSource(Playable)`

- `Void AddNotification(Double, INotification, NotificationFlags)`

- `Void SortNotifications()`

- `Void TriggerNotificationsInRange(Double, Double, FrameData, Playable, Boolean)`

- `Void SyncDurationWithExternalSource(Playable)`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
public class TimeNotificationBehaviour : PlayableBehaviour
{
	private readonly List`1 m_Notifications; // 0x10
	private Double m_PreviousTime; // 0x18
	private Boolean m_NeedSortNotifications; // 0x20
	private Playable m_TimeSource; // 0x28

	public Playable timeSource { set; }

	// RVA: 0x6830204 VA: 0x7598e48204
	public Void set_timeSource(Playable value) { }
	// RVA: 0x683020c VA: 0x7598e4820c
	public static ScriptPlayable`1 Create(PlayableGraph graph, Double duration, DirectorWrapMode loopMode) { }
	// RVA: 0x6830328 VA: 0x7598e48328
	public Void AddNotification(Double time, INotification payload, NotificationFlags flags) { }
	// RVA: 0x6830464 VA: 0x7598e48464
	public override Void OnGraphStart(Playable playable) { }
	// RVA: 0x683074c VA: 0x7598e4874c
	public override Void OnBehaviourPause(Playable playable, FrameData info) { }
	// RVA: 0x6830980 VA: 0x7598e48980
	public override Void PrepareFrame(Playable playable, FrameData info) { }
	// RVA: 0x6830628 VA: 0x7598e48628
	private Void SortNotifications() { }
	// RVA: 0x6830fa0 VA: 0x7598e48fa0
	private static Boolean CanRestoreNotification(NotificationEntry e, FrameData info, Double currentTime, Double previousTime) { }
	// RVA: 0x6830de0 VA: 0x7598e48de0
	private Void TriggerNotificationsInRange(Double start, Double end, FrameData info, Playable playable, Boolean checkState) { }
	// RVA: 0x6830cdc VA: 0x7598e48cdc
	private Void SyncDurationWithExternalSource(Playable playable) { }
	// RVA: 0x68308f8 VA: 0x7598e488f8
	private static Void Trigger_internal(Playable playable, PlayableOutput output, ref NotificationEntry e) { }
	// RVA: 0x6830ffc VA: 0x7598e48ffc
	private static Void Restore_internal(ref NotificationEntry e) { }
	// RVA: 0x683101c VA: 0x7598e4901c
	public Void .ctor() { }
}
```
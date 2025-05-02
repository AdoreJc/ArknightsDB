# WaitForSpineEvent

**Namespace:** `Spine.Unity`


## Fields

- `EventData m_TargetEvent`

- `String m_EventName`

- `AnimationState m_AnimationState`

- `Boolean m_WasFired`

- `Boolean m_unsubscribeAfterFiring`


## Properties

- `Boolean WillUnsubscribeAfterFiring`


## Methods

- `Void Subscribe(AnimationState, EventData, Boolean)`

- `Void SubscribeByName(AnimationState, String, Boolean)`

- `Void HandleAnimationStateEventByName(TrackEntry, Event)`

- `Void HandleAnimationStateEvent(TrackEntry, Event)`

- `Boolean get_WillUnsubscribeAfterFiring()`

- `Void set_WillUnsubscribeAfterFiring(Boolean)`

- `WaitForSpineEvent NowWaitFor(AnimationState, EventData, Boolean)`

- `WaitForSpineEvent NowWaitFor(AnimationState, String, Boolean)`

- `Void Clear(AnimationState)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class WaitForSpineEvent : IEnumerator
{
	private EventData m_TargetEvent; // 0x10
	private String m_EventName; // 0x18
	private AnimationState m_AnimationState; // 0x20
	private Boolean m_WasFired; // 0x28
	private Boolean m_unsubscribeAfterFiring; // 0x29

	public Boolean WillUnsubscribeAfterFiring { get; set; }
	private Object System.Collections.IEnumerator.Current { get; }

	// RVA: 0x621d600 VA: 0x7598835600
	private Void Subscribe(AnimationState state, EventData eventDataReference, Boolean unsubscribe) { }
	// RVA: 0x621d740 VA: 0x7598835740
	private Void SubscribeByName(AnimationState state, String eventName, Boolean unsubscribe) { }
	// RVA: 0x621d88c VA: 0x759883588c
	public Void .ctor(AnimationState state, EventData eventDataReference, Boolean unsubscribeAfterFiring) { }
	// RVA: 0x621d8d0 VA: 0x75988358d0
	public Void .ctor(SkeletonAnimation skeletonAnimation, EventData eventDataReference, Boolean unsubscribeAfterFiring) { }
	// RVA: 0x621d91c VA: 0x759883591c
	public Void .ctor(AnimationState state, String eventName, Boolean unsubscribeAfterFiring) { }
	// RVA: 0x621d960 VA: 0x7598835960
	public Void .ctor(SkeletonAnimation skeletonAnimation, String eventName, Boolean unsubscribeAfterFiring) { }
	// RVA: 0x621d9ac VA: 0x75988359ac
	private Void HandleAnimationStateEventByName(TrackEntry trackEntry, Event e) { }
	// RVA: 0x621da80 VA: 0x7598835a80
	private Void HandleAnimationStateEvent(TrackEntry trackEntry, Event e) { }
	// RVA: 0x621db48 VA: 0x7598835b48
	public Boolean get_WillUnsubscribeAfterFiring() { }
	// RVA: 0x621db50 VA: 0x7598835b50
	public Void set_WillUnsubscribeAfterFiring(Boolean value) { }
	// RVA: 0x621db5c VA: 0x7598835b5c
	public WaitForSpineEvent NowWaitFor(AnimationState state, EventData eventDataReference, Boolean unsubscribeAfterFiring) { }
	// RVA: 0x621dd10 VA: 0x7598835d10
	public WaitForSpineEvent NowWaitFor(AnimationState state, String eventName, Boolean unsubscribeAfterFiring) { }
	// RVA: 0x621dc38 VA: 0x7598835c38
	private Void Clear(AnimationState state) { }
	// RVA: 0x621ddec VA: 0x7598835dec
	private Boolean System.Collections.IEnumerator.MoveNext() { }
	// RVA: 0x621de9c VA: 0x7598835e9c
	private Void System.Collections.IEnumerator.Reset() { }
	// RVA: 0x621dea4 VA: 0x7598835ea4
	private Object System.Collections.IEnumerator.get_Current() { }
}
```
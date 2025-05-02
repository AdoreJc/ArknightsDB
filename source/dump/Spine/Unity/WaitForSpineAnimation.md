# WaitForSpineAnimation

**Namespace:** `Spine.Unity`


## Fields

- `Boolean m_WasFired`


## Methods

- `WaitForSpineAnimation NowWaitFor(TrackEntry, AnimationEventTypes)`

- `Void SafeSubscribe(TrackEntry, AnimationEventTypes)`

- `Void HandleComplete(TrackEntry)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class WaitForSpineAnimation : IEnumerator
{
	private Boolean m_WasFired; // 0x10

	private Object System.Collections.IEnumerator.Current { get; }

	// RVA: 0x621d258 VA: 0x7598835258
	public Void .ctor(TrackEntry trackEntry, AnimationEventTypes eventsToWaitFor) { }
	// RVA: 0x621d460 VA: 0x7598835460
	public WaitForSpineAnimation NowWaitFor(TrackEntry trackEntry, AnimationEventTypes eventsToWaitFor) { }
	// RVA: 0x621d478 VA: 0x7598835478
	private Boolean System.Collections.IEnumerator.MoveNext() { }
	// RVA: 0x621d528 VA: 0x7598835528
	private Void System.Collections.IEnumerator.Reset() { }
	// RVA: 0x621d530 VA: 0x7598835530
	private Object System.Collections.IEnumerator.get_Current() { }
	// RVA: 0x621d28c VA: 0x759883528c
	protected Void SafeSubscribe(TrackEntry trackEntry, AnimationEventTypes eventsToWaitFor) { }
	// RVA: 0x621d538 VA: 0x7598835538
	private Void HandleComplete(TrackEntry trackEntry) { }
}
```